# 量子セルオートマトン

★量子セルオートマトン、および古典セルオートマトンのコードを配置しました。  
code for the Quantum Cellular Automata(QCA) and the Classical Cellular Automata(CCA)  

## 目次

[01 1次元古典セルオートマトン <ECA> : 1D Classical Cellular Automata](./CCA_in_1dim_ECA.ipynb)

[02 2次元古典セルオートマトン <Conway's Game of Life>: 2D Classical Cellular Automata](./CCA_in_2dim_GameOfLife.ipynb)

[03-1 1次元量子セルオートマトン <qECA> シミュレータ: 1D Quantum Cellular Automata Simulator Qisit>=1.0](./QCA_in_1dim_sim_MPS.ipynb)

[03-2 1次元量子セルオートマトン <qECA> IBM Quantum実機   : 1D Quantum Cellular Automata IBMQ Qisit>=1.0](./QCA_in_1dim_IBMQ.ipynb)

[04-1 2次元量子セルオートマトン <Quantum Game of Life> シミュレータ : 2D Quantum Cellular Automata Simulator Qisit>=1.0](./QCA_in_2dim_sim_MPS.ipynb)  
    -> [量子ライフゲーム上の特徴的なパターン12種類:12 characteristic patterns in Quantum Game of Life](./patternsInTheQGoL)  

[04-2 2次元量子セルオートマトン <Quantum Game of Life> IBM Quantum実機/ibm_runtime : 2D Quantum Cellular Automata Qisit>=1.0](./QCA_in_2dim_IBMQ_ibmRuntime.ipynb)  
    -> 2024年9月最新ライブラリ(qiskit_ibm_runtime)使用。2024/9/27時点では量子回路の深さ制限により実行不可だったが、  
       2024/10/2時点では5セル平方2ステップで実行可能となった。  
    -> Using the latest library (qiskit_ibm_runtime) as of September 2024 with 5-cell square 2-step.

[04-3 2次元量子セルオートマトン <Quantum Game of Life> IBM Quantum実機/ibm_provider:2D Quantum Cellular Automata Qisit>=1.0](./QCA_in_2dim_IBMQ_ibmProvider.ipynb)  
    -> 2024年9月時点では廃止予定の旧ライブラリ(qiskit_ibm_provider)であれば実機での実行可能(3平方4ステップ)。  
    -> using the deprecated old library (qiskit_ibm_provider) with a 3-cell square 4-step.  



[test] (../2024-B-06-final-report-quantum-computing.pdf)
