# Hi there 👋 

## This is the collection of LLM4SE Benchmarks (Still under construction...)

📝 The organization of papers refers to our survey  
["Assessing and Advancing Benchmarks for Evaluating Large Language Models in Software Engineering Tasks"](https://arxiv.org/pdf/2505.08903). 

🚀 Welcome to submit issues to include your **LLM4SE benchmarks**!  
[![Submit Issue](https://img.shields.io/badge/Submit-Issue-blue?logo=github)](../../issues)

If you find our survey useful for your research, please cite the following paper:

```bibtex
@article{LLM4SEBenchmark,
  title={Assessing and Advancing Benchmarks for Evaluating Large Language Models in Software Engineering Tasks},
  author={Xing Hu, Feifei Niu, Junkai Chen, Xin Zhou, Junwei Zhang, Junda He, Xin Xia, David Lo},
  year={2025},
  journal={arXiv preprint arXiv:2505.08903},
  url={[http://arxiv.org/abs/2303.18223](https://arxiv.org/pdf/2505.08903)}
}
```


## Benchmark List

**Requirements and Design**
<table>
  <tr>
    <th>Task</th>
    <th>Benchmarks</th>
    <th>Year</th>
    <th>Evaluation Metrics</th>
    <th>Paper</th>
    <th>Link</th>
  </tr>
  <!-- Elicitation -->
  <tr>
    <td rowspan="4"><b>Elicitation</b></td>
    <td>NFR-Review</td>
    <td>2018</td>
    <td>-</td>
    <td><a href="https://tinyurl.com/y7tj9lkq">Paper</a></td>
    <td><a href="https://tinyurl.com/y7tj9lkq">Link</a></td>
  </tr>
  <tr>
    <td>Rahman and Zhu</td>
    <td>2024</td>
    <td>Readability, Understandability, Specificability, Technical-aspects</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>Habib et al.</td>
    <td>2025</td>
    <td>Precision, Recall, and F</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>Voria et al.</td>
    <td>2025</td>
    <td>Precision, Recall, F, Accuracy, BLUE, ROUGE, METEOR, Brevity Penalty, Length Ratio</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://figshare.com/s/46661b70336a46d66ac8">Link</a></td>
  </tr>

  <!-- Analysis -->
  <tr>
    <td rowspan="10"><b>Analysis</b></td>
    <td>PROMISE NFR</td>
    <td>2007</td>
    <td>-</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://terapromise.csc.ncsu.edu/!/#repo/view/head/requirements/nfr">Link</a></td>
  </tr>
  <tr>
    <td>SecReq</td>
    <td>2010</td>
    <td>-</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>PURE</td>
    <td>2017</td>
    <td>-</td>
    <td><a href="#">Paper</a></td>
    <td><a href="http://fmt.isti.cnr.it/nlreqdataset/">Link</a></td>
  </tr>
  <tr>
    <td>Dalpiaz et al.</td>
    <td>2019</td>
    <td>Precision, Recall, F1-score, AUC</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>ReqEval</td>
    <td>2020</td>
    <td>Precision, Recall, F2, Success rate</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>NFR-SO</td>
    <td>2022</td>
    <td>F1</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>DAMIR</td>
    <td>2022</td>
    <td>Precision, Recall, F2, Success rate</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>Gärtner and Göhlich</td>
    <td>2024</td>
    <td>Accuracy, Precision, Recall, F</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>Preda et al.</td>
    <td>2024</td>
    <td>Precision, Recall, F</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://zenodo.org/records/10817760">Link</a></td>
  </tr>
  <tr>
    <td>Koltoff et al.</td>
    <td>2024</td>
    <td>Precision, Recall, F, Accuracy</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://zenodo.org/records/10652222">Link</a></td>
  </tr>

  <!-- Specification & Validation -->
  <tr>
    <td rowspan="9"><b>Specification & Validation</b></td>
    <td>Jdoctor</td>
    <td>2018</td>
    <td>Precision, Recall, F</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/albertogoffi/toradocu">Link</a></td>
  </tr>
  <tr>
    <td>DocTer</td>
    <td>2022</td>
    <td>Precision, Recall, F1</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>Poudel et al.</td>
    <td>2023</td>
    <td>F2 and MAP</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://tinyurl.com/RSA-Results">Link</a></td>
  </tr>
  <tr>
    <td>Mandal et al.</td>
    <td>2023</td>
    <td>Precision, Recall, F1</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>SV-Benchmarks</td>
    <td>2024</td>
    <td>-</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>SpecGenBench</td>
    <td>2024</td>
    <td>#Passes, Success Probability, #Verifier Calls, User Rating</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>Reinpold et al.</td>
    <td>2024</td>
    <td>Precision, Recall, F</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>Krishna et al.</td>
    <td>2024</td>
    <td>Unambiguous, understandable, correctness, verifiable, consistency, non-redundancy, completeness, conciseness</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>OSVBench</td>
    <td>2025</td>
    <td>Pass@N, Syntax Error, Semantic Error</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/lishangyu-hkust/OSVBench">Link</a></td>
  </tr>

  <!-- Management -->
  <tr>
    <td rowspan="2"><b>Management</b></td>
    <td>Wang et al.</td>
    <td>2020</td>
    <td>Precision, Recall, F1</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/MeloFancy/DeepCoref">Link</a></td>
  </tr>
  <tr>
    <td>Helmeczi et al.</td>
    <td>2023</td>
    <td>Accuracy, F1</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
</table>

**Coding Assistant**
<table>
  <tr>
    <th>Task</th>
    <th>Benchmarks</th>
    <th>Year</th>
    <th>Evaluation Metrics</th>
    <th>Paper</th>
    <th>Link</th>
  </tr>

  <tr>
    <td rowspan="102"><b>Code Generation and Recommendation</b></td>
    <td>Lin et al.</td>
    <td>2013</td>
    <td>BLEU, CodeBLEU</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>Leetcode</td>
    <td>2015</td>
    <td>Passing Test Cases, Runtime, Memory Usage</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://leetcode.com">Link</a></td>
  </tr>
  <tr>
    <td>ExampleCheck</td>
    <td>2018</td>
    <td>misuse rate</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>CONCODE</td>
    <td>2018</td>
    <td>BLEU</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/sriniiyer/concode">Link</a></td>
  </tr>
  <tr>
    <td>CoNaLa</td>
    <td>2018</td>
    <td>precision, recall, TPR</td>
    <td><a href="#">Paper</a></td>
    <td><a href="http://conala-corpus.github.io/">Link</a></td>
  </tr>
  <tr>
    <td>NL2Bash</td>
    <td>2018</td>
    <td>manual, BLEU</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/TellinaTool/nl2bash/tree/master/data">Link</a></td>
  </tr>
  <tr>
    <td>Spider</td>
    <td>2018</td>
    <td>Component Matching, Execution Accuracy</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://yale-lily.github.io/spider">Link</a></td>
  </tr>
  <tr>
    <td>CodeSearchNet</td>
    <td>2020</td>
    <td>NDCG, MRR</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/github/CodeSearchNet">Link</a></td>
  </tr>
  <tr>
    <td>APPS</td>
    <td>2021</td>
    <td>Test Case Average, Strict Accuracy</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/hendrycks/apps">Link</a></td>
  </tr>
  <tr>
    <td>MBPP</td>
    <td>2021</td>
    <td>% solved</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://huggingface.co/datasets/google-research-datasets/mbpp">Link</a></td>
  </tr>
  <tr>
    <td>CodeXGLUE</td>
    <td>2021</td>
    <td>EM, ES</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/microsoft/CodeXGLUE">Link</a></td>
  </tr>
  <tr>
    <td>HumanEval</td>
    <td>2021</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/openai/human-eval">Link</a></td>
  </tr>
  <tr>
    <td>miniF2F</td>
    <td>2021</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/openai/miniF2F/tree/v1">Link</a></td>
  </tr>
  <tr>
    <td>Lyra</td>
    <td>2021</td>
    <td>BLEU, AST match</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/LIANGQINGYUAN/Lyra">Link</a></td>
  </tr>
  <tr>
    <td>FC2Code</td>
    <td>2022</td>
    <td>BLEU</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/LiuZeJie97/Code-Generation-FromFlowcharts-with-Texts-A-Benchmark-Dataset-and-AnApproach">Link</a></td>
  </tr>
  <tr>
    <td>CodeContests</td>
    <td>2022</td>
    <td>n@k, Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/google-deepmind/code_contests">Link</a></td>
  </tr>
  <tr>
    <td>AixBench</td>
    <td>2022</td>
    <td>Correctness, Maintainability, Pass@1</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/aixcoder-plugin/nl2code-dataset">Link</a></td>
  </tr>
  <tr>
    <td>ReCode</td>
    <td>2022</td>
    <td>robust Pass@k, drop@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/amazon-science/recode">Link</a></td>
  </tr>
  <tr>
    <td>SecurityEval</td>
    <td>2022</td>
    <td>percentage</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/s2e-lab/SecurityEval">Link</a></td>
  </tr>
  <tr>
    <td>MathEquations</td>
    <td>2022</td>
    <td>Functional accuracy</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/ejones313/codex-cog-biases">Link</a></td>
  </tr>
  <tr>
    <td>MBXP</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/amazon-research/mxeval">Link</a></td>
  </tr>
  <tr>
    <td>NumpyEval</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/microsoft/PyCodeGPT">Link</a></td>
  </tr>
  <tr>
    <td>PandasEval</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/microsoft/PyCodeGPT">Link</a></td>
  </tr>
  <tr>
    <td>TorchData-Eval</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/microsoft/PyCodeGPT/tree/main/apicoder">Link</a></td>
  </tr>
  <tr>
    <td>MonkeyEval</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/microsoft/PyCodeGPT/tree/main/apicoder">Link</a></td>
  </tr>
  <tr>
    <td>BeatNumEval</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/microsoft/PyCodeGPT/tree/main/apicoder">Link</a></td>
  </tr>
  <tr>
    <td>MTPB</td>
    <td>2022</td>
    <td>Pass Rate, PPL</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/salesforce/CodeGen/tree/main">Link</a></td>
  </tr>
  <tr>
    <td>Multi-HumanEval</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/amazon-research/mxeval">Link</a></td>
  </tr>
  <tr>
    <td>DSP</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/microsoft/DataScienceProblems">Link</a></td>
  </tr>
  <tr>
    <td>ExeDS</td>
    <td>2022</td>
    <td>BLEU, CodeBLEU, EM</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/Jun-jie-Huang/ExeDS">Link</a></td>
  </tr>
  <tr>
    <td>XLCoST</td>
    <td>2022</td>
    <td>BLEU, CodeBLEU, MRR</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/reddy-lab-code-research/XLCoST">Link</a></td>
  </tr>
  <tr>
    <td>Qing et al.</td>
    <td>2023</td>
    <td>Success Rate</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>ClassEval</td>
    <td>2023</td>
    <td>Pass@k, DEP(F), DEP(M)</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/FudanSELab/ClassEval">Link</a></td>
  </tr>
  <tr>
    <td>TACO</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/FlagOpen/TACO">Link</a></td>
  </tr>
  <tr>
    <td>xCodeEval</td>
    <td>2023</td>
    <td>F1, Pass@k, Accuracy</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/ntunlp/xCodeEval">Link</a></td>
  </tr>
  <tr>
    <td>CodeApex</td>
    <td>2023</td>
    <td>AC@1, AC@all, AC Rate</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://apex.sjtu.edu.cn/codeapex/">Link</a></td>
  </tr>
  <tr>
    <td>CloverBench</td>
    <td>2023</td>
    <td>Accept@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/ChuyueSun/Clover">Link</a></td>
  </tr>
  <tr>
    <td>Mastropaolo et al.</td>
    <td>2023</td>
    <td>CodeBLEU, Levenshtein Distance</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/antonio-mastropaolo/robustness-copilot">Link</a></td>
  </tr>
  <tr>
    <td>CoderEval</td>
    <td>2023</td>
    <td>Pass@k, Acc@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/CoderEval/CoderEval">Link</a></td>
  </tr>
  <tr>
    <td>EvalPlus</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/evalplus/evalplus">Link</a></td>
  </tr>
  <tr>
    <td>Shapkin et al.</td>
    <td>2023</td>
    <td>CodeBLEU, Accuracy</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>CrossCode-Bench</td>
    <td>2023</td>
    <td>EM, BLEU, ROUGE-L</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/NougatCA/CrossCodeBench">Link</a></td>
  </tr>
  <tr>
    <td>MultiPL-E</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="http://github.com/nuprl/MultiPL-E">Link</a></td>
  </tr>
  <tr>
    <td>StudentEval</td>
    <td>2023</td>
    <td>Pass@1</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://huggingface.co/datasets/wellesley-easel/StudentEval">Link</a></td>
  </tr>
  <tr>
    <td>TorchDataComplexEval</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>DS-1000</td>
    <td>2023</td>
    <td>Pass@1</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://ds1000-code-gen.github.io/">Link</a></td>
  </tr>
  <tr>
    <td>ML-Bench</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/gersteinlab/ML-bench">Link</a></td>
  </tr>
  <tr>
    <td>LowCoder</td>
    <td>2023</td>
    <td>Accuracy</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/lowcoder-org/lowcoder">Link</a></td>
  </tr>
  <tr>
    <td>Ren et al.</td>
    <td>2023</td>
    <td>Time Consumption, Answer Correctness</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/goodchar123/KPC">Link</a></td>
  </tr>
  <tr>
    <td>CodeAlpaca (Py)</td>
    <td>2023</td>
    <td>-</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/sahil280114/codealpaca">Link</a></td>
  </tr>
  <tr>
    <td>CoLadder</td>
    <td>2023</td>
    <td>Usability, Cognitive Load</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>VeriGen</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/shailja-thakur/VGen">Link</a></td>
  </tr>
  <tr>
    <td>SOEval</td>
    <td>2023</td>
    <td>NDCG@K</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://paperswithcode.com/dataset/soeval">Link</a></td>
  </tr>
  <tr>
    <td>Decept-Prompt</td>
    <td>2023</td>
    <td>ASR, WFR</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>HumanEval-X</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/THUDM/CodeGeeX">Link</a></td>
  </tr>
  <tr>
    <td>ARCADE</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>MCoNaLa</td>
    <td>2023</td>
    <td>BLEU</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/zorazrw/multilingual-conala">Link</a></td>
  </tr>
  <tr>
    <td>CrossCode-Eval</td>
    <td>2023</td>
    <td>Code Match, Identifier Match</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://crosscodeeval.github.io/">Link</a></td>
  </tr>
  <tr>
    <td>Pisces</td>
    <td>2023</td>
    <td>BLEU, Syntax-Match, CodeBLEU</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>MBPP/HumanEval/APPS-ET</td>
    <td>2023</td>
    <td>CrystalBLEU, BERTScore, COMET, CodeBERTScore</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/Dingjz/CodeScore">Link</a></td>
  </tr>
  <tr>
    <td>LiveCode-Bench</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://livecodebench.github.io">Link</a></td>
  </tr>
  <tr>
    <td>Mercury</td>
    <td>2024</td>
    <td>Beyond Pass</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/Elfsong/Mercury">Link</a></td>
  </tr>
  <tr>
    <td>EffiBench</td>
    <td>2024</td>
    <td>ET, NET, MU, TMU, Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://huggingface.co/spaces/EffiBench/effibench-leaderboard">Link</a></td>
  </tr>
  <tr>
    <td>MBPP-san-DFY</td>
    <td>2024</td>
    <td>verify@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/Mondego/dafny-synthesis">Link</a></td>
  </tr>
  <tr>
    <td>CoderUJB</td>
    <td>2024</td>
    <td>Pass@k, Count@n, Coverage@n</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/WisdomShell/ujb">Link</a></td>
  </tr>
  <tr>
    <td>PythonSaga</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://anonymous.4open.science/r/PythonSaga">Link</a></td>
  </tr>
  <tr>
    <td>DevEval</td>
    <td>2024</td>
    <td>Pass@k, Recall@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/seketeam/DevEval">Link</a></td>
  </tr>
  <tr>
    <td>Exec-CSN</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/Veronicium/CodeBenchGen">Link</a></td>
  </tr>
  <tr>
    <td>Wang et al.</td>
    <td>2024</td>
    <td>BLEU-4, CodeBLEU, edit sim</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>EvoCodeBench</td>
    <td>2024</td>
    <td>Pass@k, Recall@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/seketeam/EvoCodeBench">Link</a></td>
  </tr>
  <tr>
    <td>RustEval</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/sfikas/rusteval">Link</a></td>
  </tr>
  <tr>
    <td>Devbench</td>
    <td>2024</td>
    <td>Faithfulness, Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/open-compass/DevBench">Link</a></td>
  </tr>
  <tr>
    <td>BigCode-Bench</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://bigcode-bench.github.io/">Link</a></td>
  </tr>
  <tr>
    <td>OOPEval</td>
    <td>2024</td>
    <td>Pass@k, Pass@o</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/alphadl/OOP-eval">Link</a></td>
  </tr>
  <tr>
    <td>ODEX</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/zorazrw/odex">Link</a></td>
  </tr>
  <tr>
    <td>NaturalCodeBench</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/THUDM/NaturalCodeBench">Link</a></td>
  </tr>
  <tr>
    <td>PAREval</td>
    <td>2024</td>
    <td>speedup@k, efficiency@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/parallelcodefoundry/ParEval">Link</a></td>
  </tr>
  <tr>
    <td>CAASD</td>
    <td>2024</td>
    <td>pass rate</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://drive.google.com/drive/folders/1i0UWqy1K4WwaCLnb7yhyQfV8UqjdXSkl">Link</a></td>
  </tr>
  <tr>
    <td>CodeScope</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/WeixiangYAN/CodeScope">Link</a></td>
  </tr>
  <tr>
    <td>CodeAgent-Bench</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/zkcpku/CodeAgent">Link</a></td>
  </tr>
  <tr>
    <td>JavaBench</td>
    <td>2024</td>
    <td>Completion@k, Compilation@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/java-bench/JavaBench">Link</a></td>
  </tr>
  <tr>
    <td>Chart2Code-160k</td>
    <td>2024</td>
    <td>Execution/pass rate, text match</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/Ryan-Holben/holbench">Link</a></td>
  </tr>
  <tr>
    <td>PoorCodeSumEval</td>
    <td>2024</td>
    <td>BLEU, BERTScore</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/ythere-y/PoorCodeSumEval">Link</a></td>
  </tr>
  <tr>
    <td>ComplexCodeEval</td>
    <td>2024</td>
    <td>BLEU, Syntax Match, Data Flow Match</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/ComplexCodeEval/ComplexCodeEval">Link</a></td>
  </tr>
  <tr>
    <td>StackEval</td>
    <td>2024</td>
    <td>Acceptance Score</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/ProsusAI/stack-eval">Link</a></td>
  </tr>
  <tr>
    <td>Code-Vision</td>
    <td>2025</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/wanghanbinpanda/CodeVision?tab=readme-ov-file">Link</a></td>
  </tr>
  <tr>
    <td>CodeIF-Bench</td>
    <td>2025</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/zhu-zhu-ding/CodeIF-Bench">Link</a></td>
  </tr>
  <tr>
    <td>CodeIF</td>
    <td>2025</td>
    <td>Satisfaction Rate</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/lin-rany/codeIF">Link</a></td>
  </tr>
  <tr>
    <td>LibEvolutionEval</td>
    <td>2025</td>
    <td>F1-score, MRR</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://lib-evolution-eval.github.io">Link</a></td>
  </tr>
  <tr>
    <td>COFFE</td>
    <td>2025</td>
    <td>Efficienct@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/JohnnyPeng18/Coffe?tab=readme-ov-file">Link</a></td>
  </tr>
  <tr>
    <td>Deep-Bench</td>
    <td>2025</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://anonymous.4open.science/r/DL-Bench-D65E/">Link</a></td>
  </tr>
  <tr>
    <td>DynaCode</td>
    <td>2025</td>
    <td>Pass@k</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/HWH-2000/DynaCode">Link</a></td>
  </tr>
  <tr>
    <td>FEA-Bench</td>
    <td>2025</td>
    <td>Precision, Recall</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/microsoft/FEA-Bench">Link</a></td>
  </tr>
  <tr>
    <td>MaintainCoder</td>
    <td>2025</td>
    <td>Pass@k, CodeDiff, ASTsim</td>
    <td><a href="#">Paper</a></td>
    <td><a href="">Link</a></td>
  </tr>
  <tr>
    <td>mHumanEval</td>
    <td>2025</td>
    <td>BERTScore</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/mraihan-gmu/mHumanEval-Benchmark">Link</a></td>
  </tr>
  <tr>
    <td>REPOEXEC</td>
    <td>2025</td>
    <td>Functional correctness, Dependency utilization</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/FSoft-AI4Code/RepoExec">Link</a></td>
  </tr>
  <tr>
    <td>Plot2Code</td>
    <td>2025</td>
    <td>code pass rate, text-match ratio</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://huggingface.co/datasets/TencentARC/Plot2Code">Link</a></td>
  </tr>
  <tr>
    <td>ProjectEval</td>
    <td>2025</td>
    <td>Pass@K</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://github.com/RyanLoil/ProjectEval/">Link</a></td>
  </tr>
  <tr>
    <td>SolEval</td>
    <td>2025</td>
    <td>Pass@K, Compile@k, Gas Consumption</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://anonymous.4open.science/r/SolEval-1C06/README.MD">Link</a></td>
  </tr>
  <tr>
    <td>ConvCodeWorld</td>
    <td>2025</td>
    <td>Pass@K, MRR, Recall</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://huggingface.co/spaces/ConvCodeWorld/ConvCodeWorld">Link</a></td>
  </tr>
  <tr>
    <td>Web-Bench</td>
    <td>2025</td>
    <td>Pass@K</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://huggingface.co/datasets/bytedance-research/Web-Bench">Link</a></td>
  </tr>
  <tr>
    <td>REPOCOD</td>
    <td>2025</td>
    <td>Pass@K</td>
    <td><a href="#">Paper</a></td>
    <td><a href="https://huggingface.co/datasets/lt-asset/REPOCOD">Link</a></td>
  </tr>
  <tr>
    <td rowspan="11"><b>Code Summarization</b></td>
    <td>PCSD</td>
    <td>2017</td>
    <td>Python</td>
    <td>BLEU, BLEU-4, ROUGE-L, METEOR, CIDEr</td>
    <td>92,545 pairs</td>
    <td><a href="https://github.com/Avmb/code-docstring-corpus">Link</a></td>
  </tr>
  <tr>
    <td>JCSD</td>
    <td>2018</td>
    <td>Java</td>
    <td>Precision, Recall, F-Score, BLEU-4, METEOR, ROUGE-L, CIDEr, BLEU-DC</td>
    <td>87,136 pairs</td>
    <td><a href="https://github.com/xinghu/TL-CodeSum">Link</a></td>
  </tr>
  <tr>
    <td>Deepcom</td>
    <td>2018</td>
    <td>Java</td>
    <td>BLEU-4, METEOR, ROUGE-L</td>
    <td>69,708 pairs</td>
    <td><a href="https://github.com/huxingfree/DeepCom">Link</a></td>
  </tr>
  <tr>
    <td>Funcom</td>
    <td>2019</td>
    <td>Java</td>
    <td>BLEU, ROUGE-L, METEOR</td>
    <td>2.1M pairs</td>
    <td><a href="#">Link</a></td>
  </tr>
  <tr>
    <td>CodeXGLUE</td>
    <td>2021</td>
    <td>Java, Python</td>
    <td>BLEU, BLEU-4, ROUGE-L, METEOR, USE, MRR</td>
    <td>see code_generation table</td>
    <td><a href="https://github.com/microsoft/CodeXGLUE">Link</a></td>
  </tr>
  <tr>
    <td>Funcom-java-long</td>
    <td>2023</td>
    <td>Java</td>
    <td>BLEU</td>
    <td>8192 methods</td>
    <td><a href="https://github.com/apcl-research/jam">Link</a></td>
  </tr>
  <tr>
    <td>CroCoSum</td>
    <td>2023</td>
    <td>English, Chinese</td>
    <td>ROUGE, BERTScore</td>
    <td>18,857 pairs</td>
    <td><a href="https://github.com/RosenZhang/CroCoSum">Link</a></td>
  </tr>
  <tr>
    <td>CAPYBARA</td>
    <td>2023</td>
    <td>C</td>
    <td>EM, BLEU-4, ROUGE-L, METEOR</td>
    <td>7,826 pairs</td>
    <td><a href="https://github.com/AISE-TUDelft/Capybara-BinT5">Link</a></td>
  </tr>
  <tr>
    <td>BinSum</td>
    <td>2023</td>
    <td>C</td>
    <td>BLEU, METEOR, ROUGE-L, Semantic Similarity</td>
    <td>557,664 functions</td>
    <td><a href="https://github.com/xinjin95/BinSum">Link</a></td>
  </tr>
  <tr>
    <td>P-CodeSum</td>
    <td>2024</td>
    <td>Multiple PLs</td>
    <td>BLEU-4, ROUGE-L</td>
    <td>1,500 pairs</td>
    <td><a href="https://github.com/Linshuhuai/P-CodeSum">Link</a></td>
  </tr>
  <tr>
    <td>FILE-CS</td>
    <td>2024</td>
    <td>Python</td>
    <td>BLEU, ROUGE-L, METEOR</td>
    <td>98,236 pairs</td>
    <td><a href="https://github.com/DeepSoftwareAnalytics/SparseCoder">Link</a></td>
  </tr>

  <!-- Code Translation -->
  <tr>
    <td rowspan="13"><b>Code Translation</b></td>
    <td>CodeSearchNet</td>
    <td>2020</td>
    <td>Multiple PLs</td>
    <td>BLEU, CodeBLEU, METEOR, Exact Match</td>
    <td>6.45M pairs</td>
    <td><a href="https://github.com/github/CodeSearchNet">Link</a></td>
  </tr>
  <tr>
    <td>CodeXGLUE</td>
    <td>2021</td>
    <td>Java, Python</td>
    <td>BLEU-4, BLEU, ACC, CodeBLEU</td>
    <td>11,800 pairs</td>
    <td><a href="https://github.com/microsoft/CodeXGLUE">Link</a></td>
  </tr>
  <tr>
    <td>CodeNet</td>
    <td>2021</td>
    <td>C++, Python</td>
    <td>Compilation, Runtime Errors, Functional Errors</td>
    <td>4,053 problems, 13.9M samples</td>
    <td><a href="https://github.com/github/CodeSearchNet">Link</a></td>
  </tr>
  <tr>
    <td>CoST</td>
    <td>2022</td>
    <td>Multiple PLs</td>
    <td>BLEU, CodeBLEU</td>
    <td>132,046 pairs</td>
    <td><a href="https://github.com/reddy-labcode-research/MuST-CoST">Link</a></td>
  </tr>
  <tr>
    <td>XLCoST</td>
    <td>2022</td>
    <td>Multiple PLs</td>
    <td>CodeBLEU, BLEU, MRR</td>
    <td>1,002,296 pairs</td>
    <td><a href="https://github.com/reddy-lab-code-research/XLCoST">Link</a></td>
  </tr>
  <tr>
    <td>Nova</td>
    <td>2023</td>
    <td>Binary</td>
    <td>BLEU, Exact Match, Instruction LCS</td>
    <td>60,600 pairs</td>
    <td><a href="#">Link</a></td>
  </tr>
  <tr>
    <td>SUT</td>
    <td>2023</td>
    <td>Multiple PLs</td>
    <td>Syntax Unit Test Accuracy, Syntax Element Score</td>
    <td>60k parallel, 200k mono</td>
    <td><a href="#">Link</a></td>
  </tr>
  <tr>
    <td>xCodeEval</td>
    <td>2023</td>
    <td>Multiple PLs</td>
    <td>Pass@K</td>
    <td>25M examples</td>
    <td><a href="https://github.com/ntunlp/xCodeEval">Link</a></td>
  </tr>
  <tr>
    <td>CodeTransOcean</td>
    <td>2023</td>
    <td>Multiple PLs</td>
    <td>BLEU, CodeBLEU, Exact String Match</td>
    <td>45 languages</td>
    <td><a href="https://github.com/WeixiangYAN/CodeTransOcean">Link</a></td>
  </tr>
  <tr>
    <td>G-TransEval</td>
    <td>2023</td>
    <td>Multiple PLs</td>
    <td>BLEU, CodeBLEU, Computational Accuracy</td>
    <td>400 pairs</td>
    <td><a href="https://github.com/PolyEval/G-TransEval">Link</a></td>
  </tr>
  <tr>
    <td>AVATAR</td>
    <td>2023</td>
    <td>Java, Python</td>
    <td>BLEU, Syntax Match, CodeBLEU, Execution Accuracy</td>
    <td>62,520 pairs</td>
    <td><a href="https://github.com/wasiahmad/AVATAR">Link</a></td>
  </tr>
  <tr>
    <td>AVATAR-TC</td>
    <td>2024</td>
    <td>Java, Python</td>
    <td>BLEU, CodeBLEU, Compilation Accuracy, Functional Equivalence</td>
    <td>57,368 pairs</td>
    <td><a href="https://anonymous.4open.science/r/CoTran">Link</a></td>
  </tr>
  <tr>
    <td>RustRepoTrans</td>
    <td>2024</td>
    <td>C, Java, Python → Rust</td>
    <td>Pass@k</td>
    <td>375 tasks</td>
    <td><a href="https://github.com/SYSUSELab/RustRepoTrans/">Link</a></td>
  </tr>

  <!-- Code Reasoning -->
  <tr>
    <td rowspan="3"><b>Code Reasoning</b></td>
    <td>CRUXEval</td>
    <td>2024</td>
    <td>Python</td>
    <td>Pass@k</td>
    <td>800</td>
    <td><a href="https://crux-eval.github.io">Link</a></td>
  </tr>
  <tr>
    <td>REval</td>
    <td>2025</td>
    <td>Python</td>
    <td>Accuracy, Incremental Consistency Score</td>
    <td>3,152</td>
    <td><a href="https://r-eval.github.io">Link</a></td>
  </tr>
  <tr>
    <td>DyCodeEval</td>
    <td>2025</td>
    <td>Python</td>
    <td>Pass@K, DivPass@K</td>
    <td>591</td>
    <td><a href="https://codekaleidoscope.github.io/dycodeeval.html">Link</a></td>
  </tr>
</table>




