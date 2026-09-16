<div align="center">
<h1>Jingnan Huang</h1>
<p>Research & Engineering Archive | Quantitative Systems</p>
<hr style="height:1px;border-width:0;color:gray;background-color:gray">
</div>

<table>
<tr>
<td valign="top" width="35%">
<h3>Profile</h3>
<p>
<strong>Sales & Trading Senior Analyst</strong><br>
<a href="https://www.utefa.com/">@ UTEFA</a>
</p>
<p>
<strong>University of Toronto</strong><br>
B.A.Sc Computer Engineering + PEY Co-op<br>
<em style="font-size:12px">Minor in Eng Business</em><br>
<span style="color:gray; font-size:12px">Exp. Apr 2029</span>
</p>
<br>
<h3>Coordinates</h3>
<code>📧 jingnan.huang@mail.utoronto.ca</code><br>
<code>🔗 linkedin.com/in/jingnan-huang-buezw</code><br>
<code>🐙 github.com/Buezw</code>
<br><br>
<h3>Research Focus</h3>
<img src="https://img.shields.io/badge/Market_Microstructure-white?style=flat-square&color=white&labelColor=black">
<img src="https://img.shields.io/badge/Market_Making-white?style=flat-square&color=white&labelColor=black">
<img src="https://img.shields.io/badge/Low_Latency_Systems-white?style=flat-square&color=white&labelColor=black">
<img src="https://img.shields.io/badge/FPGA_Acceleration-white?style=flat-square&color=white&labelColor=black">
<br><br>
<h3>Tech Stack</h3>
<img src="https://img.shields.io/badge/C++17-000000?style=flat-square&logo=c%2B%2B&logoColor=white">
<img src="https://img.shields.io/badge/CUDA-000000?style=flat-square&logo=nvidia&logoColor=white">
<img src="https://img.shields.io/badge/Python-000000?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Verilog-white?style=flat-square&color=eee&labelColor=999">
<img src="https://img.shields.io/badge/SQL-white?style=flat-square&color=eee&labelColor=999">
<img src="https://img.shields.io/badge/Linux-000000?style=flat-square&logo=linux&logoColor=white">
<img src="https://img.shields.io/badge/Docker-000000?style=flat-square&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Git-000000?style=flat-square&logo=git&logoColor=white">
</td>
<td valign="top" width="65%">
<h2>Selected Projects <span style="font-size:12px; font-weight:normal; color:gray">ALPHA & SYSTEMS</span></h2>

<p><strong>HFT Order Book Engine</strong> <code>C11</code> <code>Low-Latency</code><br>
Matching engine core (~4,700 LOC, no malloc / no floating-point) extracted from a bare-metal RISC-V FPGA project into a platform-independent, differentially-tested implementation. Depth-sweep benchmarking (10&ndash;400 price levels, p50/p99 latency) quantified 1.38x&ndash;2.49x speedups; full ASan/UBSan/TSan coverage in CI.<br>
<a href="https://github.com/Buezw/HFT-Research">[View Source]</a></p>
<hr style="border: 1px dashed #ccc;">
<p><strong>Avellaneda&ndash;Stoikov Market-Making Simulator</strong> <code>Python</code> <code>Market Microstructure</code><br>
From-scratch implementation of the Avellaneda&ndash;Stoikov (2008) closed-form model (inventory-skewed reservation price, optimal spread) in vectorized NumPy Monte Carlo. Replicated the paper's experiment (30% terminal PnL volatility reduction), added adverse-selection stress tests and a Cont&ndash;Kukanov&ndash;Stoikov order-flow-imbalance signal.<br>
<a href="#">[View Source]</a></p>
<hr style="border: 1px dashed #ccc;">
<p><strong>Multi-Factor Portfolio Risk Analytics Engine</strong> <code>Python</code> <code>Quant Risk</code><br>
Risk decomposition engine on the covariance identity &Sigma; = B&Sigma;<sub>F</sub>B<sup>&#8868;</sup> + D (MCTR, systematic/idiosyncratic splits, parametric CVaR with Kupiec POF backtesting), backed by a hand-written six-factor Fama&ndash;French/Carhart regression engine with Ridge fallback and an interactive Streamlit/Plotly terminal.<br>
<a href="#">[View Source]</a></p>
<br>
<h2>Archives <span style="font-size:12px; font-weight:normal; color:gray">MI / EL / RL</span></h2>
<table role="presentation">
<tr>
<td width="50%">
<strong>Market Insights (MI)</strong><br>
<ul>
<li><a href="#">Reservation Price & Optimal Spread (Avellaneda&ndash;Stoikov)</a> <span style="font-size:10px; border:1px solid red; color:red; padding:0 2px;">MACRO</span></li>
<li><a href="#">Order Flow Imbalance as a Quoting Signal</a></li>
<li><a href="#">CVaR Backtesting with the Kupiec POF Test</a></li>
</ul>
</td>
<td width="50%">
<strong>Engineering Logs (EL)</strong><br>
<ul>
<li><a href="#">Depth-Sweep Latency Benchmarking (p50/p99)</a> <span style="font-size:10px; border:1px solid black; color:black; padding:0 2px;">DEV</span></li>
<li><a href="#">Lock-Free SPSC Ring Buffers for Order Ingestion</a></li>
<li><a href="#">Differential Testing vs. Invariant-Based Testing</a></li>
</ul>
</td>
</tr>
</table>
</td>
</tr>
</table>
<div align="center">
<p style="font-size:12px; color:gray">
© 2026 Jingnan Huang | RESEARCH & ENGINEERING
</p>
</div>
