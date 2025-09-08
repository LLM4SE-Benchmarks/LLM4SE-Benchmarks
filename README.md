# Hi there 👋 

## This is the collection of LLM4SE Benchmarks (Still under construction...)

📝 The organization of papers refers to our survey  
["Assessing and Advancing Benchmarks for Evaluating Large Language Models in Software Engineering Tasks"](https://arxiv.org/pdf/2505.08903). 

🚀 Welcome to submit issues to include your **LLM4SE benchmarks**!  
[![Submit Issue](https://img.shields.io/badge/Submit-Issue-blue?logo=github)](../../issues)

🔥 If you find our survey useful for your research, please cite the following paper:

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
    <td>[<a href="https://ieeexplore.ieee.org/document/8719458">Paper</a>]</td>
    <td>[<a href="https://tinyurl.com/y7tj9lkq">Link</a>]</td>
  </tr>
  <tr>
    <td>Rahman and Zhu</td>
    <td>2024</td>
    <td>Readability, Understandability, Specificability, Technical-aspects</td>
    <td>[<a href="https://arxiv.org/abs/2404.01558">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>Habib et al.</td>
    <td>2025</td>
    <td>Precision, Recall, and F</td>
    <td>[<a href="https://arxiv.org/abs/2505.17632">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>Voria et al.</td>
    <td>2025</td>
    <td>Precision, Recall, F, Accuracy, BLUE, ROUGE, METEOR, Brevity Penalty, Length Ratio</td>
    <td>[<a href="https://www.computer.org/csdl/journal/ts/2025/06/11008757/26TEcSo0gJq">Paper</a>]</td>
    <td>[<a href="https://figshare.com/s/46661b70336a46d66ac8">Link</a>]</td>
  </tr>

  <!-- Analysis -->
  <tr>
    <td rowspan="10"><b>Analysis</b></td>
    <td>PROMISE NFR</td>
    <td>2007</td>
    <td>-</td>
    <td>[Paper]</td>
    <td>[<a href="https://terapromise.csc.ncsu.edu/!/#repo/view/head/requirements/nfr">Link</a>]</td>
  </tr>
  <tr>
    <td>SecReq</td>
    <td>2010</td>
    <td>-</td>
    <td>[Paper]</td>
    <td>[<a href="https://zenodo.org/records/4530183">Link</a>]</td>
  </tr>
  <tr>
    <td>PURE</td>
    <td>2017</td>
    <td>-</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/8049173">Paper</a>]</td>
    <td>[<a href="http://fmt.isti.cnr.it/nlreqdataset/">Link</a>]</td>
  </tr>
  <tr>
    <td>Dalpiaz et al.</td>
    <td>2019</td>
    <td>Precision, Recall, F1-score, AUC</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/8920401">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>ReqEval</td>
    <td>2020</td>
    <td>Precision, Recall, F2, Success rate</td>
    <td>[Paper]</td>
    <td>[<a href="https://zenodo.org/records/4471411">Link</a>]</td>
  </tr>
  <tr>
    <td>NFR-SO</td>
    <td>2022</td>
    <td>F1</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3551349.3560417">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>DAMIR</td>
    <td>2022</td>
    <td>Precision, Recall, F2, Success rate</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3510003.3510157">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>Gärtner and Göhlich</td>
    <td>2024</td>
    <td>Accuracy, Precision, Recall, F</td>
    <td>[<a href="https://link.springer.com/article/10.1007/s10515-024-00452-x">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>Preda et al.</td>
    <td>2024</td>
    <td>Precision, Recall, F</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3643991.3644922">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/10817760">Link</a>]</td>
  </tr>
  <tr>
    <td>Koltoff et al.</td>
    <td>2024</td>
    <td>Precision, Recall, F, Accuracy</td>
    <td>[<a href="https://arxiv.org/abs/2406.08120">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/10652222">Link</a>]</td>
  </tr>

  <!-- Specification & Validation -->
  <tr>
    <td rowspan="9"><b>Specification & Validation</b></td>
    <td>Jdoctor</td>
    <td>2018</td>
    <td>Precision, Recall, F</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3213846.3213872">Paper</a>]</td>
    <td>[<a href="https://github.com/albertogoffi/toradocu">Link</a>]</td>
  </tr>
  <tr>
    <td>DocTer</td>
    <td>2022</td>
    <td>Precision, Recall, F1</td>
    <td>[<a href="https://arxiv.org/abs/2109.01002">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>Poudel et al.</td>
    <td>2023</td>
    <td>F2 and MAP</td>
    <td>[<a href="https://arxiv.org/abs/2312.04463">Paper</a>]</td>
    <td>[<a href="https://tinyurl.com/RSA-Results">Link</a>]</td>
  </tr>
  <tr>
    <td>Mandal et al.</td>
    <td>2023</td>
    <td>Precision, Recall, F1</td>
    <td>[<a href="https://arxiv.org/abs/2304.09181">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>SV-Benchmarks</td>
    <td>2024</td>
    <td>-</td>
    <td>[Paper]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>SpecGenBench</td>
    <td>2024</td>
    <td>#Passes, Success Probability, #Verifier Calls, User Rating</td>
    <td>[<a href="https://arxiv.org/abs/2401.08807">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>Reinpold et al.</td>
    <td>2024</td>
    <td>Precision, Recall, F</td>
    <td>[<a href="https://arxiv.org/abs/2411.11582">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>Krishna et al.</td>
    <td>2024</td>
    <td>Unambiguous, understandable, correctness, verifiable, consistency, non-redundancy, completeness, conciseness</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/10628461">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>OSVBench</td>
    <td>2025</td>
    <td>Pass@N, Syntax Error, Semantic Error</td>
    <td>[<a href="https://arxiv.org/abs/2504.20964">Paper</a>]</td>
    <td>[<a href="https://github.com/lishangyu-hkust/OSVBench">Link</a>]</td>
  </tr>

  <!-- Management -->
  <tr>
    <td rowspan="2"><b>Management</b></td>
    <td>Wang et al.</td>
    <td>2020</td>
    <td>Precision, Recall, F1</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/9218208">Paper</a>]</td>
    <td>[<a href="https://github.com/MeloFancy/DeepCoref">Link</a>]</td>
  </tr>
  <tr>
    <td>Helmeczi et al.</td>
    <td>2023</td>
    <td>Accuracy, F1</td>
    <td>[<a href="https://arxiv.org/abs/2306.08058">Paper</a>]</td>
    <td>[Link]</td>
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
    <td>[<a href="https://dl.acm.org/doi/pdf/10.1145/3697012">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>Leetcode</td>
    <td>2015</td>
    <td>Passing Test Cases, Runtime, Memory Usage</td>
    <td>[Paper]</td>
    <td>[<a href="https://leetcode.com">Link</a>]</td>
  </tr>
  <tr>
    <td>ExampleCheck</td>
    <td>2018</td>
    <td>misuse rate</td>
    <td>[<a href="https://tianyi-zhang.github.io/files/icse2018-examplecheck.pdf">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>CONCODE</td>
    <td>2018</td>
    <td>BLEU</td>
    <td>[<a href="https://arxiv.org/pdf/1808.09588">Paper</a>]</td>
    <td>[<a href="https://github.com/sriniiyer/concode">Link</a>]</td>
  </tr>
  <tr>
    <td>CoNaLa</td>
    <td>2018</td>
    <td>precision, recall, TPR</td>
    <td>[<a href="https://arxiv.org/pdf/1805.08949">Paper</a>]</td>
    <td>[<a href="http://conala-corpus.github.io/">Link</a>]</td>
  </tr>
  <tr>
    <td>NL2Bash</td>
    <td>2018</td>
    <td>manual, BLEU</td>
    <td>[<a href="https://arxiv.org/pdf/1802.08979">Paper</a>]</td>
    <td>[<a href="https://github.com/TellinaTool/nl2bash/tree/master/data">Link</a>]</td>
  </tr>
  <tr>
    <td>Spider</td>
    <td>2018</td>
    <td>Component Matching, Execution Accuracy</td>
    <td>[<a href="https://arxiv.org/pdf/1809.08887">Paper</a>]</td>
    <td>[<a href="https://yale-lily.github.io/spider">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeSearchNet</td>
    <td>2020</td>
    <td>NDCG, MRR</td>
    <td>[<a href="http://arxiv.org/pdf/1909.09436">Paper</a>]</td>
    <td>[<a href="https://github.com/github/CodeSearchNet">Link</a>]</td>
  </tr>
  <tr>
    <td>APPS</td>
    <td>2021</td>
    <td>Test Case Average, Strict Accuracy</td>
    <td>[<a href="https://arxiv.org/pdf/2105.09938">Paper</a>]</td>
    <td>[<a href="https://github.com/hendrycks/apps">Link</a>]</td>
  </tr>
  <tr>
    <td>MBPP</td>
    <td>2021</td>
    <td>% solved</td>
    <td>[<a href="https://arxiv.org/pdf/2108.07732">Paper</a>]</td>
    <td>[<a href="https://huggingface.co/datasets/google-research-datasets/mbpp">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeXGLUE</td>
    <td>2021</td>
    <td>EM, ES</td>
    <td>[<a href="https://arxiv.org/pdf/2102.04664">Paper</a>]</td>
    <td>[<a href="https://github.com/microsoft/CodeXGLUE">Link</a>]</td>
  </tr>
  <tr>
    <td>HumanEval</td>
    <td>2021</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/pdf/2107.03374">Paper</a>]</td>
    <td>[<a href="https://github.com/openai/human-eval">Link</a>]</td>
  </tr>
  <tr>
    <td>miniF2F</td>
    <td>2021</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/pdf/2109.00110">Paper</a>]</td>
    <td>[<a href="https://github.com/openai/miniF2F/tree/v1">Link</a>]</td>
  </tr>
  <tr>
    <td>Lyra</td>
    <td>2021</td>
    <td>BLEU, AST match</td>
    <td>[<a href="https://arxiv.org/pdf/2108.12144">Paper</a>]</td>
    <td>[<a href="https://github.com/LIANGQINGYUAN/Lyra">Link</a>]</td>
  </tr>
  <tr>
    <td>FC2Code</td>
    <td>2022</td>
    <td>BLEU</td>
    <td>[<a href="https://aclanthology.org/2022.findings-emnlp.449.pdf">Paper</a>]</td>
    <td>[<a href="https://github.com/LiuZeJie97/Code-Generation-FromFlowcharts-with-Texts-A-Benchmark-Dataset-and-AnApproach">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeContests</td>
    <td>2022</td>
    <td>n@k, Pass@k</td>
    <td>[<a href="https://arxiv.org/pdf/2203.07814">Paper</a>]</td>
    <td>[<a href="https://github.com/google-deepmind/code_contests">Link</a>]</td>
  </tr>
  <tr>
    <td>AixBench</td>
    <td>2022</td>
    <td>Correctness, Maintainability, Pass@1</td>
    <td>[<a href="https://arxiv.org/abs/2206.13179">Paper</a>]</td>
    <td>[<a href="https://github.com/aixcoder-plugin/nl2code-dataset">Link</a>]</td>
  </tr>
  <tr>
    <td>ReCode</td>
    <td>2022</td>
    <td>robust Pass@k, drop@k</td>
    <td>[<a href="https://aclanthology.org/2023.acl-long.773/">Paper</a>]</td>
    <td>[<a href="https://github.com/amazon-science/recode">Link</a>]</td>
  </tr>
  <tr>
    <td>SecurityEval</td>
    <td>2022</td>
    <td>percentage</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3549035.3561184">Paper</a>]</td>
    <td>[<a href="https://github.com/s2e-lab/SecurityEval">Link</a>]</td>
  </tr>
  <tr>
    <td>MathEquations</td>
    <td>2022</td>
    <td>Functional accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.5555/3600270.3601126">Paper</a>]</td>
    <td>[<a href="https://github.com/ejones313/codex-cog-biases">Link</a>]</td>
  </tr>
  <tr>
    <td>MBXP</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td>[<a href="https://openreview.net/forum?id=Bo7eeXm6An8">Paper</a>]</td>
    <td>[<a href="https://github.com/amazon-research/mxeval">Link</a>]</td>
  </tr>
  <tr>
    <td>NumpyEval</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td>[<a href="https://www.ijcai.org/proceedings/2022/329">Paper</a>]</td>
    <td>[<a href="https://github.com/microsoft/PyCodeGPT">Link</a>]</td>
  </tr>
  <tr>
    <td>PandasEval</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td>[<a href="https://www.ijcai.org/proceedings/2022/329">Paper</a>]</td>
    <td>[<a href="https://github.com/microsoft/PyCodeGPT">Link</a>]</td>
  </tr>
  <tr>
    <td>TorchData-Eval</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2210.17236">Paper</a>]</td>
    <td>[<a href="https://github.com/microsoft/PyCodeGPT/tree/main/apicoder">Link</a>]</td>
  </tr>
  <tr>
    <td>MonkeyEval</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2210.17236">Paper</a>]</td>
    <td>[<a href="https://github.com/microsoft/PyCodeGPT/tree/main/apicoder">Link</a>]</td>
  </tr>
  <tr>
    <td>BeatNumEval</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2210.17236">Paper</a>]</td>
    <td>[<a href="https://github.com/microsoft/PyCodeGPT/tree/main/apicoder">Link</a>]</td>
  </tr>
  <tr>
    <td>MTPB</td>
    <td>2022</td>
    <td>Pass Rate, PPL</td>
    <td>[<a href="https://openreview.net/forum?id=iaYcJKpY2B_">Paper</a>]</td>
    <td>[<a href="https://github.com/salesforce/CodeGen/tree/main">Link</a>]</td>
  </tr>
  <tr>
    <td>Multi-HumanEval</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td>[<a href="https://openreview.net/forum?id=Bo7eeXm6An8">Paper</a>]</td>
    <td>[<a href="https://github.com/amazon-research/mxeval">Link</a>]</td>
  </tr>
  <tr>
    <td>DSP</td>
    <td>2022</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2201.12901">Paper</a>]</td>
    <td>[<a href="https://github.com/microsoft/DataScienceProblems">Link</a>]</td>
  </tr>
  <tr>
    <td>ExeDS</td>
    <td>2022</td>
    <td>BLEU, CodeBLEU, EM</td>
    <td>[<a href="https://aclanthology.org/2022.dash-1.5/">Paper</a>]</td>
    <td>[<a href="https://github.com/Jun-jie-Huang/ExeDS">Link</a>]</td>
  </tr>
  <tr>
    <td>XLCoST</td>
    <td>2022</td>
    <td>BLEU, CodeBLEU, MRR</td>
    <td>[<a href="https://arxiv.org/abs/2206.08474">Paper</a>]</td>
    <td>[<a href="https://github.com/reddy-lab-code-research/XLCoST">Link</a>]</td>
  </tr>
  <tr>
    <td>Qing et al.</td>
    <td>2023</td>
    <td>Success Rate</td>
    <td>[<a href="https://arxiv.org/abs/2308.04788">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>ClassEval</td>
    <td>2023</td>
    <td>Pass@k, DEP(F), DEP(M)</td>
    <td>[<a href="https://arxiv.org/abs/2308.01861">Paper</a>]</td>
    <td>[<a href="https://github.com/FudanSELab/ClassEval">Link</a>]</td>
  </tr>
  <tr>
    <td>TACO</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2312.14852">Paper</a>]</td>
    <td>[<a href="https://github.com/FlagOpen/TACO">Link</a>]</td>
  </tr>
  <tr>
    <td>xCodeEval</td>
    <td>2023</td>
    <td>F1, Pass@k, Accuracy</td>
    <td>[<a href="https://aclanthology.org/2024.acl-long.367/">Paper</a>]</td>
    <td>[<a href="https://github.com/ntunlp/xCodeEval">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeApex</td>
    <td>2023</td>
    <td>AC@1, AC@all, AC Rate</td>
    <td>[<a href="https://arxiv.org/abs/2309.01940">Paper</a>]</td>
    <td>[<a href="https://apex.sjtu.edu.cn/codeapex/">Link</a>]</td>
  </tr>
  <tr>
    <td>CloverBench</td>
    <td>2023</td>
    <td>Accept@k</td>
    <td>[<a href="https://dl.acm.org/doi/10.1007/978-3-031-65112-0_7">Paper</a>]</td>
    <td>[<a href="https://github.com/ChuyueSun/Clover">Link</a>]</td>
  </tr>
  <tr>
    <td>Mastropaolo et al.</td>
    <td>2023</td>
    <td>CodeBLEU, Levenshtein Distance</td>
    <td>[<a href="https://arxiv.org/abs/2302.00438">Paper</a>]</td>
    <td>[<a href="https://github.com/antonio-mastropaolo/robustness-copilot">Link</a>]</td>
  </tr>
  <tr>
    <td>CoderEval</td>
    <td>2023</td>
    <td>Pass@k, Acc@k</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3597503.3623316">Paper</a>]</td>
    <td>[<a href="https://github.com/CoderEval/CoderEval">Link</a>]</td>
  </tr>
  <tr>
    <td>EvalPlus</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td>[<a href="https://dl.acm.org/doi/10.5555/3666122.3667065">Paper</a>]</td>
    <td>[<a href="https://github.com/evalplus/evalplus">Link</a>]</td>
  </tr>
  <tr>
    <td>Shapkin et al.</td>
    <td>2023</td>
    <td>CodeBLEU, Accuracy</td>
    <td>[<a href="https://arxiv.org/html/2312.08976v1">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>CrossCode-Bench</td>
    <td>2023</td>
    <td>EM, BLEU, ROUGE-L</td>
    <td>[<a href="https://dl.acm.org/doi/abs/10.1109/ICSE48619.2023.00055">Paper</a>]</td>
    <td>[<a href="https://github.com/NougatCA/CrossCodeBench">Link</a>]</td>
  </tr>
  <tr>
    <td>MultiPL-E</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td>[<a href="https://www.computer.org/csdl/journal/ts/2023/07/10103177/1MpWUtj7Rwk">Paper</a>]</td>
    <td>[<a href="http://github.com/nuprl/MultiPL-E">Link</a>]</td>
  </tr>
  <tr>
    <td>StudentEval</td>
    <td>2023</td>
    <td>Pass@1</td>
    <td>[<a href="https://aclanthology.org/2024.findings-acl.501/">Paper</a>]</td>
    <td>[<a href="https://huggingface.co/datasets/wellesley-easel/StudentEval">Link</a>]</td>
  </tr>
  <tr>
    <td>TorchDataComplexEval</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2307.15370">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>DS-1000</td>
    <td>2023</td>
    <td>Pass@1</td>
    <td>[<a href="https://dl.acm.org/doi/10.5555/3618408.3619164">Paper</a>]</td>
    <td>[<a href="https://ds1000-code-gen.github.io/">Link</a>]</td>
  </tr>
  <tr>
    <td>ML-Bench</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2311.09835">Paper</a>]</td>
    <td>[<a href="https://github.com/gersteinlab/ML-bench">Link</a>]</td>
  </tr>
  <tr>
    <td>LowCoder</td>
    <td>2023</td>
    <td>Accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3640543.3645203">Paper</a>]</td>
    <td>[<a href="https://github.com/lowcoder-org/lowcoder">Link</a>]</td>
  </tr>
  <tr>
    <td>Ren et al.</td>
    <td>2023</td>
    <td>Time Consumption, Answer Correctness</td>
    <td>[<a href="https://dl.acm.org/doi/10.1109/ASE56229.2023.00143">Paper</a>]</td>
    <td>[<a href="https://github.com/goodchar123/KPC">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeAlpaca (Py)</td>
    <td>2023</td>
    <td>-</td>
    <td>[<a href="https://github.com/sahil280114/codealpaca">Paper</a>]</td>
    <td>[<a href="https://github.com/sahil280114/codealpaca">Link</a>]</td>
  </tr>
  <tr>
    <td>CoLadder</td>
    <td>2023</td>
    <td>Usability, Cognitive Load</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3654777.3676357">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>VeriGen</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3643681">Paper</a>]</td>
    <td>[<a href="https://github.com/shailja-thakur/VGen">Link</a>]</td>
  </tr>
  <tr>
    <td>SOEval</td>
    <td>2023</td>
    <td>NDCG@K</td>
    <td>[<a href="https://arxiv.org/abs/2307.08220">Paper</a>]</td>
    <td>[<a href="https://paperswithcode.com/dataset/soeval">Link</a>]</td>
  </tr>
  <tr>
    <td>Decept-Prompt</td>
    <td>2023</td>
    <td>ASR, WFR</td>
    <td>[<a href="https://arxiv.org/abs/2312.04730">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>HumanEval-X</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3580305.3599790">Paper</a>]</td>
    <td>[<a href="https://github.com/THUDM/CodeGeeX">Link</a>]</td>
  </tr>
  <tr>
    <td>ARCADE</td>
    <td>2023</td>
    <td>Pass@k</td>
    <td>[<a href="https://aclanthology.org/2023.acl-long.9/">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>MCoNaLa</td>
    <td>2023</td>
    <td>BLEU</td>
    <td>[<a href="https://aclanthology.org/2023.findings-eacl.20.pdf">Paper</a>]</td>
    <td>[<a href="https://github.com/zorazrw/multilingual-conala">Link</a>]</td>
  </tr>
  <tr>
    <td>CrossCode-Eval</td>
    <td>2023</td>
    <td>Code Match, Identifier Match</td>
    <td>[<a href="https://arxiv.org/abs/2310.11248">Paper</a>]</td>
    <td>[<a href="https://crosscodeeval.github.io/">Link</a>]</td>
  </tr>
  <tr>
    <td>Pisces</td>
    <td>2023</td>
    <td>BLEU, Syntax-Match, CodeBLEU</td>
    <td>[<a href="https://dl.acm.org/doi/abs/10.1007/s10664-023-10372-1">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>MBPP/HumanEval/APPS-ET</td>
    <td>2023</td>
    <td>CrystalBLEU, BERTScore, COMET, CodeBERTScore</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3695991">Paper</a>]</td>
    <td>[<a href="https://github.com/Dingjz/CodeScore">Link</a>]</td>
  </tr>
  <tr>
    <td>LiveCode-Bench</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td>[<a href="https://openreview.net/forum?id=chfJJYC3iL">Paper</a>]</td>
    <td>[<a href="https://livecodebench.github.io">Link</a>]</td>
  </tr>
  <tr>
    <td>Mercury</td>
    <td>2024</td>
    <td>Beyond Pass</td>
    <td>[<a href="https://arxiv.org/abs/2402.07844">Paper</a>]</td>
    <td>[<a href="https://github.com/Elfsong/Mercury">Link</a>]</td>
  </tr>
  <tr>
    <td>EffiBench</td>
    <td>2024</td>
    <td>ET, NET, MU, TMU, Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2402.02037">Paper</a>]</td>
    <td>[<a href="https://huggingface.co/spaces/EffiBench/effibench-leaderboard">Link</a>]</td>
  </tr>
  <tr>
    <td>MBPP-san-DFY</td>
    <td>2024</td>
    <td>verify@k</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3643763">Paper</a>]</td>
    <td>[<a href="https://github.com/Mondego/dafny-synthesis">Link</a>]</td>
  </tr>
  <tr>
    <td>CoderUJB</td>
    <td>2024</td>
    <td>Pass@k, Count@n, Coverage@n</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3650212.3652115">Paper</a>]</td>
    <td>[<a href="https://github.com/WisdomShell/ujb">Link</a>]</td>
  </tr>
  <tr>
    <td>PythonSaga</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td>[<a href="https://aclanthology.org/2024.findings-emnlp.996.pdf">Paper</a>]</td>
    <td>[<a href="https://anonymous.4open.science/r/PythonSaga">Link</a>]</td>
  </tr>
  <tr>
    <td>DevEval</td>
    <td>2024</td>
    <td>Pass@k, Recall@k</td>
    <td>[<a href="https://aclanthology.org/2024.findings-acl.214/">Paper</a>]</td>
    <td>[<a href="https://github.com/seketeam/DevEval">Link</a>]</td>
  </tr>
  <tr>
    <td>Exec-CSN</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td>[<a href="https://openreview.net/forum?id=XXVRkPB1tg">Paper</a>]</td>
    <td>[<a href="https://github.com/Veronicium/CodeBenchGen">Link</a>]</td>
  </tr>
  <tr>
    <td>Wang et al.</td>
    <td>2024</td>
    <td>BLEU-4, CodeBLEU, edit sim</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3714462">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>EvoCodeBench</td>
    <td>2024</td>
    <td>Pass@k, Recall@k</td>
    <td>[<a href="https://arxiv.org/abs/2404.00599">Paper</a>]</td>
    <td>[<a href="https://github.com/seketeam/EvoCodeBench">Link</a>]</td>
  </tr>
  <tr>
    <td>RustEval</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2406.03283">Paper</a>]</td>
    <td>[<a href="https://github.com/sfikas/rusteval">Link</a>]</td>
  </tr>
  <tr>
    <td>Devbench</td>
    <td>2024</td>
    <td>Faithfulness, Pass@k</td>
    <td>[<a href="https://arxiv.org/html/2403.08604v1">Paper</a>]</td>
    <td>[<a href="https://github.com/open-compass/DevBench">Link</a>]</td>
  </tr>
  <tr>
    <td>BigCode-Bench</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td>[<a href="https://openreview.net/forum?id=YrycTjllL0">Paper</a>]</td>
    <td>[<a href="https://bigcode-bench.github.io/">Link</a>]</td>
  </tr>
  <tr>
    <td>OOPEval</td>
    <td>2024</td>
    <td>Pass@k, Pass@o</td>
    <td>[<a href="https://aclanthology.org/2024.findings-acl.808/">Paper</a>]</td>
    <td>[<a href="https://github.com/alphadl/OOP-eval">Link</a>]</td>
  </tr>
  <tr>
    <td>ODEX</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td>[<a href="https://aclanthology.org/2023.findings-emnlp.89.pdf">Paper</a>]</td>
    <td>[<a href="https://github.com/zorazrw/odex">Link</a>]</td>
  </tr>
  <tr>
    <td>NaturalCodeBench</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td>[<a href="https://aclanthology.org/2024.findings-acl.471/">Paper</a>]</td>
    <td>[<a href="https://github.com/THUDM/NaturalCodeBench">Link</a>]</td>
  </tr>
  <tr>
    <td>PAREval</td>
    <td>2024</td>
    <td>speedup@k, efficiency@k</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3625549.3658689">Paper</a>]</td>
    <td>[<a href="https://github.com/parallelcodefoundry/ParEval">Link</a>]</td>
  </tr>
  <tr>
    <td>CAASD</td>
    <td>2024</td>
    <td>pass rate</td>
    <td>[<a href="https://arxiv.org/abs/2401.01062">Paper</a>]</td>
    <td>[<a href="https://drive.google.com/drive/folders/1i0UWqy1K4WwaCLnb7yhyQfV8UqjdXSkl">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeScope</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td>[<a href="https://aclanthology.org/2024.acl-long.301.pdf">Paper</a>]</td>
    <td>[<a href="https://github.com/WeixiangYAN/CodeScope">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeAgent-Bench</td>
    <td>2024</td>
    <td>Pass@k</td>
    <td>[<a href="https://aclanthology.org/2024.acl-long.737.pdf">Paper</a>]</td>
    <td>[<a href="https://github.com/zkcpku/CodeAgent">Link</a>]</td>
  </tr>
  <tr>
    <td>JavaBench</td>
    <td>2024</td>
    <td>Completion@k, Compilation@k</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3691620.3695470">Paper</a>]</td>
    <td>[<a href="https://github.com/java-bench/JavaBench">Link</a>]</td>
  </tr>
  <tr>
    <td>Chart2Code-160k</td>
    <td>2024</td>
    <td>Execution/pass rate, text match</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3639478.3639792">Paper</a>]</td>
    <td>[<a href="https://github.com/Ryan-Holben/holbench">Link</a>]</td>
  </tr>
  <tr>
    <td>PoorCodeSumEval</td>
    <td>2024</td>
    <td>BLEU, BERTScore</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3691620.3695072">Paper</a>]</td>
    <td>[<a href="https://github.com/ythere-y/PoorCodeSumEval">Link</a>]</td>
  </tr>
  <tr>
    <td>ComplexCodeEval</td>
    <td>2024</td>
    <td>BLEU, Syntax Match, Data Flow Match</td>
    <td>[<a href="https://arxiv.org/html/2409.10280v1">Paper</a>]</td>
    <td>[<a href="https://github.com/ComplexCodeEval/ComplexCodeEval">Link</a>]</td>
  </tr>
  <tr>
    <td>StackEval</td>
    <td>2024</td>
    <td>Acceptance Score</td>
    <td>[<a href="https://openreview.net/forum?id=42mqpIrA39">Paper</a>]</td>
    <td>[<a href="https://github.com/ProsusAI/stack-eval">Link</a>]</td>
  </tr>
  <tr>
    <td>Code-Vision</td>
    <td>2025</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2502.11829">Paper</a>]</td>
    <td>[<a href="https://github.com/wanghanbinpanda/CodeVision?tab=readme-ov-file">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeIF-Bench</td>
    <td>2025</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2503.22688">Paper</a>]</td>
    <td>[<a href="https://github.com/zhu-zhu-ding/CodeIF-Bench">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeIF</td>
    <td>2025</td>
    <td>Satisfaction Rate</td>
    <td>[<a href="https://aclanthology.org/2025.acl-industry.89.pdf">Paper</a>]</td>
    <td>[<a href="https://github.com/lin-rany/codeIF">Link</a>]</td>
  </tr>
  <tr>
    <td>LibEvolutionEval</td>
    <td>2025</td>
    <td>F1-score, MRR</td>
    <td>[<a href="https://aclanthology.org/2025.naacl-long.348/">Paper</a>]</td>
    <td>[<a href="https://lib-evolution-eval.github.io">Link</a>]</td>
  </tr>
  <tr>
    <td>COFFE</td>
    <td>2025</td>
    <td>Efficienct@k</td>
    <td>[<a href="https://arxiv.org/abs/2502.02827">Paper</a>]</td>
    <td>[<a href="https://github.com/JohnnyPeng18/Coffe?tab=readme-ov-file">Link</a>]</td>
  </tr>
  <tr>
    <td>Deep-Bench</td>
    <td>2025</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2502.18726">Paper</a>]</td>
    <td>[<a href="https://anonymous.4open.science/r/DL-Bench-D65E/">Link</a>]</td>
  </tr>
  <tr>
    <td>DynaCode</td>
    <td>2025</td>
    <td>Pass@k</td>
    <td>[<a href="https://arxiv.org/abs/2503.10452">Paper</a>]</td>
    <td>[<a href="https://github.com/HWH-2000/DynaCode">Link</a>]</td>
  </tr>
  <tr>
    <td>FEA-Bench</td>
    <td>2025</td>
    <td>Precision, Recall</td>
    <td>[<a href="https://aclanthology.org/2025.acl-long.839/">Paper</a>]</td>
    <td>[<a href="https://github.com/microsoft/FEA-Bench">Link</a>]</td>
  </tr>
  <tr>
    <td>MaintainCoder</td>
    <td>2025</td>
    <td>Pass@k, CodeDiff, ASTsim</td>
    <td>[<a href="https://arxiv.org/abs/2503.24260">Paper</a>]</td>
    <td>[Link]</td>
  </tr>
  <tr>
    <td>mHumanEval</td>
    <td>2025</td>
    <td>BERTScore</td>
    <td>[<a href="https://arxiv.org/abs/2410.15037">Paper</a>]</td>
    <td>[<a href="https://github.com/mraihan-gmu/mHumanEval-Benchmark">Link</a>]</td>
  </tr>
  <tr>
    <td>REPOEXEC</td>
    <td>2025</td>
    <td>Functional correctness, Dependency utilization</td>
    <td>[<a href="https://aclanthology.org/2025.findings-naacl.82/">Paper</a>]</td>
    <td>[<a href="https://github.com/FSoft-AI4Code/RepoExec">Link</a>]</td>
  </tr>
  <tr>
    <td>Plot2Code</td>
    <td>2025</td>
    <td>code pass rate, text-match ratio</td>
    <td>[<a href="https://aclanthology.org/2025.findings-naacl.164/">Paper</a>]</td>
    <td>[<a href="https://huggingface.co/datasets/TencentARC/Plot2Code">Link</a>]</td>
  </tr>
  <tr>
    <td>ProjectEval</td>
    <td>2025</td>
    <td>Pass@K</td>
    <td>[<a href="https://aclanthology.org/2025.findings-acl.1036.pdf">Paper</a>]</td>
    <td>[<a href="https://github.com/RyanLoil/ProjectEval/">Link</a>]</td>
  </tr>
  <tr>
    <td>SolEval</td>
    <td>2025</td>
    <td>Pass@K, Compile@k, Gas Consumption</td>
    <td>[<a href="https://arxiv.org/abs/2502.18793">Paper</a>]</td>
    <td>[<a href="https://anonymous.4open.science/r/SolEval-1C06/README.MD">Link</a>]</td>
  </tr>
  <tr>
    <td>ConvCodeWorld</td>
    <td>2025</td>
    <td>Pass@K, MRR, Recall</td>
    <td>[<a href="https://arxiv.org/abs/2502.19852">Paper</a>]</td>
    <td>[<a href="https://huggingface.co/spaces/ConvCodeWorld/ConvCodeWorld">Link</a>]</td>
  </tr>
  <tr>
    <td>Web-Bench</td>
    <td>2025</td>
    <td>Pass@K</td>
    <td>[<a href="https://arxiv.org/abs/2505.07473">Paper</a>]</td>
    <td>[<a href="https://huggingface.co/datasets/bytedance-research/Web-Bench">Link</a>]</td>
  </tr>
  <tr>
    <td>REPOCOD</td>
    <td>2025</td>
    <td>Pass@K</td>
    <td>[<a href="https://arxiv.org/abs/2410.21647">Paper</a>]</td>
    <td>[<a href="https://huggingface.co/datasets/lt-asset/REPOCOD">Link</a>]</td>
  </tr>
  <tr>
    <td rowspan="11"><b>Code Summarization</b></td>
    <td>PCSD</td>
    <td>2017</td>
    <td>Python</td>
    <td>BLEU, BLEU-4, ROUGE-L, METEOR, CIDEr</td>
    <td>92,545 pairs</td>
    <td>[<a href="https://aclanthology.org/I17-2053/">Paper</a>]</td>
    <td>[<a href="https://github.com/Avmb/code-docstring-corpus">Link</a>]</td>
  </tr>
  <tr>
    <td>JCSD</td>
    <td>2018</td>
    <td>Java</td>
    <td>Precision, Recall, F-Score, BLEU-4, METEOR, ROUGE-L, CIDEr, BLEU-DC</td>
    <td>87,136 pairs</td>
    <td>[<a href="https://dl.acm.org/doi/10.5555/3304889.3304975">Paper</a>]</td>
    <td>[<a href="https://github.com/xinghu/TL-CodeSum">Link</a>]</td>
  </tr>
  <tr>
    <td>Deepcom</td>
    <td>2018</td>
    <td>Java</td>
    <td>BLEU-4, METEOR, ROUGE-L</td>
    <td>69,708 pairs</td>
    <td>[<a href="https://github.com/huxingfree/DeepCom">Link</a>]</td>
  </tr>
  <tr>
    <td>Funcom</td>
    <td>2019</td>
    <td>Java</td>
    <td>BLEU, ROUGE-L, METEOR</td>
    <td>2.1M pairs</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeXGLUE</td>
    <td>2021</td>
    <td>Java, Python</td>
    <td>BLEU, BLEU-4, ROUGE-L, METEOR, USE, MRR</td>
    <td>see code_generation table</td>
    <td>[<a href="https://github.com/microsoft/CodeXGLUE">Link</a>]</td>
  </tr>
  <tr>
    <td>Funcom-java-long</td>
    <td>2023</td>
    <td>Java</td>
    <td>BLEU</td>
    <td>8192 methods</td>
    <td>[<a href="https://github.com/apcl-research/jam">Link</a>]</td>
  </tr>
  <tr>
    <td>CroCoSum</td>
    <td>2023</td>
    <td>English, Chinese</td>
    <td>ROUGE, BERTScore</td>
    <td>18,857 pairs</td>
    <td>[<a href="https://github.com/RosenZhang/CroCoSum">Link</a>]</td>
  </tr>
  <tr>
    <td>CAPYBARA</td>
    <td>2023</td>
    <td>C</td>
    <td>EM, BLEU-4, ROUGE-L, METEOR</td>
    <td>7,826 pairs</td>
    <td>[<a href="https://github.com/AISE-TUDelft/Capybara-BinT5">Link</a>]</td>
  </tr>
  <tr>
    <td>BinSum</td>
    <td>2023</td>
    <td>C</td>
    <td>BLEU, METEOR, ROUGE-L, Semantic Similarity</td>
    <td>557,664 functions</td>
    <td>[<a href="https://github.com/xinjin95/BinSum">Link</a>]</td>
  </tr>
  <tr>
    <td>P-CodeSum</td>
    <td>2024</td>
    <td>Multiple PLs</td>
    <td>BLEU-4, ROUGE-L</td>
    <td>1,500 pairs</td>
    <td>[<a href="https://github.com/Linshuhuai/P-CodeSum">Link</a>]</td>
  </tr>
  <tr>
    <td>FILE-CS</td>
    <td>2024</td>
    <td>Python</td>
    <td>BLEU, ROUGE-L, METEOR</td>
    <td>98,236 pairs</td>
    <td>[<a href="https://github.com/DeepSoftwareAnalytics/SparseCoder">Link</a>]</td>
  </tr>

  <!-- Code Translation -->
  <tr>
    <td rowspan="13"><b>Code Translation</b></td>
    <td>CodeSearchNet</td>
    <td>2020</td>
    <td>Multiple PLs</td>
    <td>BLEU, CodeBLEU, METEOR, Exact Match</td>
    <td>6.45M pairs</td>
    <td>[<a href="https://github.com/github/CodeSearchNet">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeXGLUE</td>
    <td>2021</td>
    <td>Java, Python</td>
    <td>BLEU-4, BLEU, ACC, CodeBLEU</td>
    <td>11,800 pairs</td>
    <td>[<a href="https://github.com/microsoft/CodeXGLUE">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeNet</td>
    <td>2021</td>
    <td>C++, Python</td>
    <td>Compilation, Runtime Errors, Functional Errors</td>
    <td>4,053 problems, 13.9M samples</td>
    <td>[<a href="https://github.com/github/CodeSearchNet">Link</a>]</td>
  </tr>
  <tr>
    <td>CoST</td>
    <td>2022</td>
    <td>Multiple PLs</td>
    <td>BLEU, CodeBLEU</td>
    <td>132,046 pairs</td>
    <td>[<a href="https://github.com/reddy-labcode-research/MuST-CoST">Link</a>]</td>
  </tr>
  <tr>
    <td>XLCoST</td>
    <td>2022</td>
    <td>Multiple PLs</td>
    <td>CodeBLEU, BLEU, MRR</td>
    <td>1,002,296 pairs</td>
    <td>[<a href="https://github.com/reddy-lab-code-research/XLCoST">Link</a>]</td>
  </tr>
  <tr>
    <td>Nova</td>
    <td>2023</td>
    <td>Binary</td>
    <td>BLEU, Exact Match, Instruction LCS</td>
    <td>60,600 pairs</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>SUT</td>
    <td>2023</td>
    <td>Multiple PLs</td>
    <td>Syntax Unit Test Accuracy, Syntax Element Score</td>
    <td>60k parallel, 200k mono</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>xCodeEval</td>
    <td>2023</td>
    <td>Multiple PLs</td>
    <td>Pass@K</td>
    <td>25M examples</td>
    <td>[<a href="https://github.com/ntunlp/xCodeEval">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeTransOcean</td>
    <td>2023</td>
    <td>Multiple PLs</td>
    <td>BLEU, CodeBLEU, Exact String Match</td>
    <td>45 languages</td>
    <td>[<a href="https://github.com/WeixiangYAN/CodeTransOcean">Link</a>]</td>
  </tr>
  <tr>
    <td>G-TransEval</td>
    <td>2023</td>
    <td>Multiple PLs</td>
    <td>BLEU, CodeBLEU, Computational Accuracy</td>
    <td>400 pairs</td>
    <td>[<a href="https://github.com/PolyEval/G-TransEval">Link</a>]</td>
  </tr>
  <tr>
    <td>AVATAR</td>
    <td>2023</td>
    <td>Java, Python</td>
    <td>BLEU, Syntax Match, CodeBLEU, Execution Accuracy</td>
    <td>62,520 pairs</td>
    <td>[<a href="https://github.com/wasiahmad/AVATAR">Link</a>]</td>
  </tr>
  <tr>
    <td>AVATAR-TC</td>
    <td>2024</td>
    <td>Java, Python</td>
    <td>BLEU, CodeBLEU, Compilation Accuracy, Functional Equivalence</td>
    <td>57,368 pairs</td>
    <td>[<a href="https://anonymous.4open.science/r/CoTran">Link</a>]</td>
  </tr>
  <tr>
    <td>RustRepoTrans</td>
    <td>2024</td>
    <td>C, Java, Python → Rust</td>
    <td>Pass@k</td>
    <td>375 tasks</td>
    <td>[<a href="https://github.com/SYSUSELab/RustRepoTrans/">Link</a>]</td>
  </tr>

  <!-- Code Reasoning -->
  <tr>
    <td rowspan="3"><b>Code Reasoning</b></td>
    <td>CRUXEval</td>
    <td>2024</td>
    <td>Python</td>
    <td>Pass@k</td>
    <td>800</td>
    <td>[<a href="https://crux-eval.github.io">Link</a>]</td>
  </tr>
  <tr>
    <td>REval</td>
    <td>2025</td>
    <td>Python</td>
    <td>Accuracy, Incremental Consistency Score</td>
    <td>3,152</td>
    <td>[<a href="https://r-eval.github.io">Link</a>]</td>
  </tr>
  <tr>
    <td>DyCodeEval</td>
    <td>2025</td>
    <td>Python</td>
    <td>Pass@K, DivPass@K</td>
    <td>591</td>
    <td>[<a href="https://codekaleidoscope.github.io/dycodeeval.html">Link</a>]</td>
  </tr>
</table>

**Software Testing**
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
    <td rowspan="14"><b>Test Generation</b></td>
    <td>Evosuite SF110</td>
    <td>2011</td>
    <td>Line coverage, branch coverage, and test correctness</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/2685612">Paper</a>]</td>
    <td>[<a href="https://www.evosuite.org/experimental-data/sf100/">Link</a>]</td>
  </tr>
  <tr>
    <td>Defects4J</td>
    <td>2014</td>
    <td>The number of test case is executable, CodeBLEU, line coverage, branch coverage, and the number of detected bugs</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/2610384.2628055">Paper</a>]</td>
    <td>[<a href="https://github.com/rjust/defects4j">Link</a>]</td>
  </tr>
  <tr>
    <td>DynaMOSA</td>
    <td>2018</td>
    <td>Line coverage, branch coverage, number of detected bugs</td>
    <td>[<a href="http://ieeexplore.ieee.org/document/7840029/">Paper</a>]</td>
    <td>[<a href="https://www.evosuite.org/experimental-data/evolutionary-algorithm-study/">Link</a>]</td>
  </tr>
  <tr>
    <td>BugsInPy</td>
    <td>2020</td>
    <td>Line coverage, branch coverage, and number of detected bugs </td>
    <td>[<a href="https://dl.acm.org/doi/abs/10.1145/3368089.3417943">Paper</a>]</td>
    <td>[<a href="https://github.com/soarsmu/BugsInPy">Link</a>]</td>
  </tr>
  <tr>
    <td>HumanEval</td>
    <td>2021</td>
    <td>Mutation score, Pass@K, the number of killed mutants, line coverage, and branch coverage</td>
    <td>[<a href="https://arxiv.org/abs/2107.03374">Paper</a>]</td>
    <td>[<a href="https://github.com/openai/human-eval">Link</a>]</td>
  </tr>
  <tr>
    <td>MBPP</td>
    <td>2021</td>
    <td>Pass@K</td>
    <td>[<a href="https://arxiv.org/abs/2108.07732">Paper</a>]</td>
    <td>[<a href="https://huggingface.co/datasets/google-research-datasets/mbpp">Link</a>]</td>
  </tr>
  <tr>
    <td>APPS</td>
    <td>2021</td>
    <td>Pass@K</td>
    <td>[<a href="https://arxiv.org/abs/2105.09938">Paper</a>]</td>
    <td>[<a href="https://github.com/hendrycks/apps">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeContests</td>
    <td>2022</td>
    <td>Pass@K</td>
    <td>[<a href="https://arxiv.org/abs/2203.07814">Paper</a>]</td>
    <td>[<a href="https://github.com/google-deepmind/code_contests">Link</a>]</td>
  </tr>
  <tr>
    <td>HumanEval-X</td>
    <td>2023</td>
    <td>Pass@K</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3580305.3599790">Paper</a>]</td>
    <td>[<a href="https://github.com/THUDM/CodeGeeX">Link</a>]</td>
  </tr>
  <tr>
    <td>CoderUJB</td>
    <td>2024</td>
    <td>Syntax correctness rate, compile passing rate, line coverage</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3650212.3652115">Paper</a>]</td>
    <td>[<a href="https://github.com/WisdomShell/ujb">Link</a>]</td>
  </tr>
  <tr>
    <td>SWT-Bench</td>
    <td>2024</td>
    <td>Success rate and change coverage </td>
    <td>[<a href="https://arxiv.org/abs/2406.12952">Paper</a>]</td>
    <td>[<a href="https://github.com/logic-star-ai/SWT-Bench">Link</a>]</td>
  </tr>
  <tr>
    <td>TestBench</td>
    <td>2024</td>
    <td>Syntax/compilation/execution correctness rate, coverage/defect detection rate</td>
    <td>[<a href="https://arxiv.org/abs/2409.17561">Paper</a>]</td>
    <td>[<a href="https://github.com/iSEngLab/TestBench">Link</a>]</td>
  </tr>
  <tr>
    <td>TestEval</td>
    <td>2025</td>
    <td>overall/line/branch/path coverage</td>
    <td>[<a href="https://aclanthology.org/2025.findings-naacl.197/">Paper</a>]</td>
    <td>[<a href="https://github.com/iSEngLab/TestBench">Link</a>]</td>
  </tr>
  <tr>
    <td>ProjectTest</td>
    <td>2025</td>
    <td>Compilation/correctness/coverage rate</td>
    <td>[<a href="https://arxiv.org/abs/2502.06556">Paper</a>]</td>
    <td>[<a href="https://github.com/YiboWANG214/ProjectTest">Link</a>]</td>
  </tr>

  <!-- Assertion Generation -->
  <tr>
    <td rowspan="1"><b>Assertion Generation</b></td>
    <td>ATLAS</td>
    <td>2020</td>
    <td>Exact match, edit distance, and longest common subsequence</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3377811.3380429">Paper</a>]</td>
    <td>[<a href="https://sites.google.com/view/atlas-nmt/home">Link</a>]</td>
  </tr>

  <!-- GUI Test -->
  <tr>
    <td rowspan="2"><b>GUI Test</b></td>
    <td>Themis</td>
    <td>2021</td>
    <td>The number of detected bugs, and activity coverage</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3468264.3468620">Paper</a>]</td>
    <td>[<a href="https://github.com/the-themis-benchmarks/home">Link</a>]</td>
  </tr>
  <tr>
    <td>QTypist</td>
    <td>2021</td>
    <td>Passing rate, coverage metrics, activity number, and page number</td>
    <td>[<a href="https://dl.acm.org/doi/10.1109/ICSE48619.2023.00119">Paper</a>]</td>
    <td>[<a href="https://github.com/franklinbill/QTypist">Link</a>]</td>
  </tr>

  <!-- Testing Automation -->
  <tr>
    <td rowspan="4"><b>Testing Automation</b></td>
    <td>LAVA-M</td>
    <td>2016</td>
    <td>Coverage, Unique bug</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/7546498">Paper</a>]</td>
    <td>[<a href="https://github.com/panda-re/lava">Link</a>]</td>
  </tr>
  <tr>
    <td>Unibench</td>
    <td>2021</td>
    <td>Quality of bugs, stability of finding bugs, speed of finding bugs, and overhead</td>
    <td>[<a href="https://www.usenix.org/conference/usenixsecurity21/presentation/li-yuwei">Paper</a>]</td>
    <td>[<a href="https://github.com/unifuzz/unibench">Link</a>]</td>
  </tr>
  <tr>
    <td>FuzzBench</td>
    <td>2021</td>
    <td>Coverage, Unique bug</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3468264.3473932">Paper</a>]</td>
    <td>[<a href="https://google.github.io/fuzzbench">Link</a>]</td>
  </tr>
  <tr>
    <td>FuzzGPT</td>
    <td>2024</td>
    <td>Code coverage, API coverage, number of unique crashes</td>
    <td>[<a href="https://arxiv.org/abs/2304.02014">Paper</a>]</td>
    <td>[<a href="https://github.com/ise-uiuc/FuzzGPT">Link</a>]</td>
  </tr>

  <!-- Testing Prediction -->
  <tr>
    <td rowspan="2"><b>Testing Prediction</b></td>
    <td>IDoFT</td>
    <td>2019</td>
    <td>Precision, Recall, F1-Score</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/8730188/">Paper</a>]</td>
    <td>[<a href="https://github.com/TestingResearchIllinois/idoft">Link</a>]</td>
  </tr>
  <tr>
    <td>FlakeFlagger</td>
    <td>2021</td>
    <td>Precision, Recall, F1-Score</td>
    <td>[<a href="https://jonbell.net/publications/flakeflagger">Paper</a>]</td>
    <td>[<a href="https://github.com/AlshammariA/FlakeFlagger">Link</a>]</td>
  </tr>

  <!-- Testing Repair -->
  <tr>
    <td rowspan="2"><b>Testing Repair</b></td>
    <td>TARBENCH</td>
    <td>2025</td>
    <td>CodeBLEU, BLEU, exact match, repair accuracy</td>
    <td>[<a href="https://arxiv.org/abs/2401.06765">Paper</a>]</td>
    <td>[<a href="https://figshare.com/articles/dataset/_b_TaRBench_A_Comprehensive_Benchmark_for_Automated_Test_Case_Repair_b_/25008893">Link</a>]</td>
  </tr>
  <tr>
    <td>Syn-Bench</td>
    <td>2025</td>
    <td>Syntactic/semantic correctness, code coverage</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3720419">Paper</a>]</td>
    <td>[<a href="https://sites.google.com/view/utfix">Link</a>]</td>
  </tr>
</table>

**AIOps**
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
    <td rowspan="4"><b>Log Statement Generation</b></td>
    <td>LANCE</td>
    <td>2022</td>
    <td>Correct prediction ratio</td>
    <td>[<a href="https://arxiv.org/pdf/2201.04837">Paper</a>]</td>
    <td>[<a href="https://github.com/antonio-mastropaolo/LANCE">Link</a>]</td>
  </tr>
  <tr>
    <td>LogBench</td>
    <td>2024</td>
    <td>Accuracy, Precision, Recall</td>
    <td>[<a href="https://arxiv.org/pdf/2307.05950">Paper</a>]</td>
    <td>[<a href="https://github.com/LoggingResearch/LoggingEmpirical">Link</a>]</td>
  </tr>
  <tr>
    <td>SCLoger</td>
    <td>2024</td>
    <td>Accuracy, Precision, Recall, F1, BLEU, and ROUGE</td>
    <td>[<a href="https://arxiv.org/pdf/2402.12958">Paper</a>]</td>
    <td>[<a href="https://github.com/YichenLi00/SCLogger">Link</a>]</td>
  </tr>
  <tr>
    <td>AL-Bench</td>
    <td>2025</td>
    <td>Position Accuracy, Level Accuracy, Average Level Distance, Message Accuracy, Dynamic Expression Accuracy, Static Text Similarity</td>
    <td>[<a href="https://arxiv.org/pdf/2502.03160">Paper</a>]</td>
    <td>[<a href="https://github.com/shuaijiumei/logging-benchmark">Link</a>]</td>
  </tr>

  <!-- Log Parsing -->
  <tr>
    <td rowspan="2"><b>Log Parsing</b></td>
    <td>Loghub</td>
    <td>2023</td>
    <td>Accuracy</td>
    <td>[<a href="https://arxiv.org/pdf/2008.06448">Paper</a>]</td>
    <td>[<a href="https://github.com/logpai/loghub">Link</a>]</td>
  </tr>
  <tr>
    <td>Loghub-2.0</td>
    <td>2024</td>
    <td>Accuracy, F1-score</td>
    <td>[<a href="https://arxiv.org/pdf/2308.10828">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/8275861">Link</a>]</td>
  </tr>
</table>

**Maintenance**
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
    <td rowspan="7"><b>Code Review</b></td>
    <td>CodeReview</td>
    <td>2022</td>
    <td>Exact Match</td>
    <td>[<a href="https://arxiv.org/pdf/2201.06850">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/5387856#.YTDrPZ4zZyo">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeReviewer</td>
    <td>2022</td>
    <td>Exact Match and BLEU</td>
    <td>[<a href="https://arxiv.org/pdf/2203.09095">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/6900648">Link</a>]</td>
  </tr>
  <tr>
    <td>AUGER</td>
    <td>2023</td>
    <td>ROUGE, Perfect Prediction Rate</td>
    <td>[<a href="https://arxiv.org/pdf/2208.08014">Paper</a>]</td>
    <td>[<a href="https://gitlab.com/ai-for-se-public-data/auger-fse-2022">Link</a>]</td>
  </tr>
  <tr>
    <td>Review-Explaining</td>
    <td>2023</td>
    <td>Explanation type correctness,the semantic meaning correctness</td>
    <td>[<a href="https://arxiv.org/pdf/2311.09020">Paper</a>]</td>
    <td>[<a href="https://figshare.com/s/135201b8f87ab705448b">Link</a>]</td>
  </tr>
  <tr>
    <td>Code-Review-Assist</td>
    <td>2023</td>
    <td>Precision, Recall, and F1 score</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/10123491">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/7533156">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeReview-New</td>
    <td>2024</td>
    <td>Exact Match Trim, Exact Match, BLEU</td>
    <td>[<a href="https://arxiv.org/pdf/2309.08221">Paper</a>]</td>
    <td>[<a href="https://sites.google.com/view/chatgptcodereview">Link</a>]</td>
  </tr>
  <tr>
    <td>ManualReviewComment</td>
    <td>2025</td>
    <td>Precision, Recall, F1</td>
    <td>[<a href="https://arxiv.org/pdf/2502.02757">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/13150598">Link</a>]</td>
  </tr>

  <!-- Clone Detection -->
  <tr>
    <td rowspan="5"><b>Clone Detection</b></td>
    <td>BigCloneBench</td>
    <td>2014</td>
    <td>Precision, Recall, F1</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/7332459">Paper</a>]</td>
    <td>[<a href="https://github.com/clonebench/BigCloneBench">Link</a>]</td>
  </tr>
  <tr>
    <td>POJ-104</td>
    <td>2016</td>
    <td>Precision, Recall, MAP</td>
    <td>[<a href="https://arxiv.org/pdf/1409.5718">Paper</a>]</td>
    <td>[<a href="https://drive.google.com/file/d/0B2i-vWnOu7MxVlJwQXN6eVNONUU/view?resourcekey=0-Po3kiAifLfCCYnanCBDMHw">Link</a>]</td>
  </tr>
  <tr>
    <td>Company-C/C++</td>
    <td>2023</td>
    <td>MRR, Precision, Recall </td>
    <td>[<a href="https://arxiv.org/pdf/2309.02182">Paper</a>]</td>
    <td>[<a href="https://github.com/SFI-Lero/SSCD/tree/main">Link</a>]</td>
  </tr>
  <tr>
    <td>GPTCloneBench</td>
    <td>2023</td>
    <td>Precision, Recall</td>
    <td>[<a href="https://arxiv.org/pdf/2308.13963">Paper</a>]</td>
    <td>[<a href="https://github.com/srlabUsask/GPTCloneBench">Link</a>]</td>
  </tr>
  <tr>
    <td>Curated CodeNet</td>
    <td>2023</td>
    <td>Precision, Recall</td>
    <td>[<a href="https://arxiv.org/pdf/2308.01191">Paper</a>]</td>
    <td>[<a href="https://github.com/LLM4CodeClone/LLM4CodeClone">Link</a>]</td>
  </tr>

  <!-- Refactoring -->
  <tr>
    <td rowspan="1"><b>Refactoring</b></td>
    <td>JavaRef</td>
    <td>2023</td>
    <td>Accuracy, Exact Match, Edit Distance, Character Error Rate</td>
    <td>[<a href="https://arxiv.org/pdf/2305.17708">Paper</a>]</td>
    <td>[<a href="https://drive.google.com/drive/folders/1aw2yiUTXwB3gJrDcFWeDpYvGgJNYjt51">Link</a>]</td>
  </tr>
</table>

**Quality Management**
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
    <td rowspan="6"><b>Defect Prediction</b></td>
    <td>Bugs.jar</td>
    <td>2018</td>
    <td>Precision, Recall, F1, Accuracy, MCC</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3196398.3196473">Paper</a>]</td>
    <td>[<a href="https://github.com/bugs-dot-jar/bugs-dot-jar">Link</a>]</td>
  </tr>
  <tr>
    <td>Bears</td>
    <td>2019</td>
    <td>Precision, Recall, F1, Accuracy, MCC</td>
    <td>[<a href="https://arxiv.org/abs/1901.06024">Paper</a>]</td>
    <td>[<a href="https://github.com/bears-bugs">Link</a>]</td>
  </tr>
  <tr>
    <td>Zeng et al.</td>
    <td>2021</td>
    <td>Accuracy, Recall, False Discovery Rate, AUC-ROC, AUC-PR</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3460319.3464819">Paper</a>]</td>
    <td>[<a href="https://github.com/ZZR0/ISSTA21-JIT-DP">Link</a>]</td>
  </tr>
  <tr>
    <td>Review-Explaining</td>
    <td>2023</td>
    <td>Explanation type correctness,the semantic meaning correctness</td>
    <td>[<a href="#">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>JIT-defects4j</td>
    <td>2022</td>
    <td>F1-score, AUC, Recall@20 Effort, Effort@20 Recall, P𝑜𝑝𝑡 , Top-N Accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3540250.3549165">Paper</a>]</td>
    <td>[<a href="https://github.com/jacknichao/JIT-Fine">Link</a>]</td>
  </tr>
  <tr>
    <td>Opu et al.</td>
    <td>2025</td>
    <td>Precision, Recall, F1, Accuracy, MCC</td>
    <td>[<a href="https://arxiv.org/abs/2505.08263">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>

  <!-- Bug Localization -->
  <tr>
    <td rowspan="20"><b>Bug Localization</b></td>
    <td>Ye et al.</td>
    <td>2014</td>
    <td>Accuracy, MRR, MAP</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/2635868.2635874">Paper</a>]</td>
    <td>[<a href="http://dx.doi.org/10.6084/m9.figshare.951967">Link</a>]</td>
  </tr>
  <tr>
    <td>Defects4J</td>
    <td>2014</td>
    <td>ACC@K, FPR, Top@N</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/2610384.2628055">Paper</a>]</td>
    <td>[<a href="https://github.com/rjust/defects4j">Link</a>]</td>
  </tr>
  <tr>
    <td>Bench4BL</td>
    <td>2018</td>
    <td>MRR, MAP, HIT@K</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3213846.3213856">Paper</a>]</td>
    <td>[<a href="https://github.com/exatoa/Bench4BL">Link</a>]</td>
  </tr>
  <tr>
    <td>Devign</td>
    <td>2019</td>
    <td>Top@N</td>
    <td>[<a href="https://arxiv.org/abs/1909.03496">Paper</a>]</td>
    <td>[<a href="https://github.com/epicosy/devign">Link</a>]</td>
  </tr>
  <tr>
    <td>BugsInPy</td>
    <td>2020</td>
    <td>ACC@K,Top@N</td>
    <td>[<a href="https://dl.acm.org/doi/abs/10.1145/3368089.3417943">Paper</a>]</td>
    <td>[<a href="https://github.com/soarsmu/BugsInPy">Link</a>]</td>
  </tr>
   <tr>
    <td>Zhu et al.</td>
    <td>2021</td>
    <td>Accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3468264.3468544">Paper</a>]</td>
    <td>[<a href="https://github.com/pkuzqh/Recoder">Link</a>]</td>
  </tr>
  <tr>
    <td>CodeReviewer</td>
    <td>2022</td>
    <td>Accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3540250.3549081">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/6900648">Link</a>]</td>
  </tr>
   <tr>
    <td>Ciborowska et al.</td>
    <td>2022</td>
    <td>Precision@K, Recall@K, F1-score@K, MRR, MAP </td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3510003.3510042">Paper</a>]</td>
    <td>[<a href="https://anonymous.4open.science/r/fbl-bert-700C/README.md">Link</a>]</td>
  </tr>
  <tr>
    <td>Ma et al.</td>
    <td>2023</td>
    <td>MAP, MRR, Top@N</td>
    <td>[<a href="https://www.ijcai.org/proceedings/2023/0249.pdf">Paper</a>]</td>
    <td>[<a href="https://lamda.nju.edu.cn/mayf/sgAttention-Code.zip">Link</a>]</td>
  </tr>
  <tr>
    <td>RTLLM</td>
    <td>2024</td>
    <td>Hit Rate, pass@k</td>
    <td>[<a href="https://dl.acm.org/doi/10.1109/ASP-DAC58780.2024.10473904">Paper</a>]</td>
    <td>[<a href="https://github.com/hkust-zhiyao/RTLLM">Link</a>]</td>
  </tr>
  <tr>
    <td>BeetleBox</td>
    <td>2024</td>
    <td>Accuracy, MRR, MAP </td>
    <td>[<a href="https://arxiv.org/abs/2407.17631">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/15122980">Link</a>]</td>
  </tr>
  <tr>
    <td>SWE-Bench</td>
    <td>2024</td>
    <td>Accuracy, MRR, MAP, TopN, Precision</td>
    <td>[<a href="https://openreview.net/forum?id=VTF8yNQM66">Paper</a>]</td>
    <td>[<a href="https://www.swebench.com">Link</a>]</td>
  </tr>
  <tr>
    <td>Chandramohan et al.</td>
    <td>2024</td>
    <td>Accuracy, MRR, MAP</td>
    <td>[<a href="https://arxiv.org/abs/2407.02732">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>Stracquadanio et al.</td>
    <td>2024</td>
    <td>Top-1 bug coverage</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/10546890/">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>Manke et al.</td>
    <td>2024</td>
    <td>TP, FP</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3708473">Paper</a>]</td>
    <td>[<a href="https://github.com/Ruchira-1/Theia?tab=readme-ov-file">Link</a>]</td>
  </tr>
  <tr>
    <td>D58</td>
    <td>2024</td>
    <td>Recall, MRR, CandiAvg</td>
    <td>[<a href="https://arxiv.org/abs/2408.12070">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>Saha et al.</td>
    <td>2024</td>
    <td>MRR, MAP, HIT@K</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3650212.3680357">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/12692994">Link</a>]</td>
  </tr>
  <tr>
    <td>Widyasari et al.</td>
    <td>2024</td>
    <td>Top-K</td>
    <td>[<a href="https://arxiv.org/abs/2403.10507">Paper</a>]</td>
    <td>[<a href="https://figshare.com/s/bce02cb607a6c30043ad?file=47354473">Link</a>]</td>
  </tr>
  <tr>
    <td>LINUXFLBENCH</td>
    <td>2025</td>
    <td>Recall@k, MRR</td>
    <td>[<a href="https://arxiv.org/abs/2505.19489">Paper</a>]</td>
    <td>[<a href="https://github.com/FudanSELab/LinuxFLBench">Link</a>]</td>
  </tr>
  <tr>
    <td>ACPR</td>
    <td>2025</td>
    <td>Accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.1609/aaai.v39i1.31988">Paper</a>]</td>
    <td>[<a href="https://github.com/zhenlongDai/AdaPatcher">Link</a>]</td>
  </tr>

  <!-- Repair -->
  <tr>
    <td rowspan="12"><b>Repair</b></td>
    <td>Defects4J</td>
    <td>2014</td>
    <td># fixed bugs</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/2610384.2628055">Paper</a>]</td>
    <td>[<a href="https://github.com/rjust/defects4j">Link</a>]</td>
  </tr>
  <tr>
    <td>QuixBugs</td>
    <td>2017</td>
    <td># fixed bugs</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3135932.3135941">Paper</a>]</td>
    <td>[<a href="https://github.com/jkoppel/QuixBugs">Link</a>]</td>
  </tr>
  <tr>
    <td>LMDefects</td>
    <td>2023</td>
    <td># fixed bugs</td>
    <td>[<a href="https://arxiv.org/abs/2205.10583">Paper</a>]</td>
    <td>[<a href="https://github.com/zhiyufan/apr4codex">Link</a>]</td>
  </tr>
  <tr>
    <td>InferredBugs</td>
    <td>2023</td>
    <td>Ratio of fixed bugs</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3611643.3613892">Paper</a>]</td>
    <td>[<a href="https://github.com/microsoft/InferredBugs">Link</a>]</td>
  </tr>
  <tr>
    <td>ARHE</td>
    <td>2023</td>
    <td>Accuracy</td>
    <td>[<a href="https://arxiv.org/abs/2304.02195">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>Leetcode-debug</td>
    <td>2023</td>
    <td>Acceptance rate</td>
    <td>[<a href="https://arxiv.org/abs/2307.08260">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>API-Misuse-Repair</td>
    <td>2017</td>
    <td>Eaxct Match, BLEU, CodeBLEU</td>
    <td>[<a href="https://arxiv.org/abs/2310.16390">Paper</a>]</td>
    <td>[<a href="https://anonymous.4open.science/r/TOSEM-API-Misuse">Link</a>]</td>
  </tr>
  <tr>
    <td>DebugBench</td>
    <td>2024</td>
    <td>Pass Rate</td>
    <td>[<a href="https://arxiv.org/abs/2401.04621">Paper</a>]</td>
    <td>[<a href="https://github.com/thunlp/DebugBench">Link</a>]</td>
  </tr>
  <tr>
    <td>SWE-Bench</td>
    <td>2024</td>
    <td>Resolution rate</td>
    <td>[<a href="https://openreview.net/forum?id=VTF8yNQM66">Paper</a>]</td>
    <td>[<a href="https://www.swebench.com">Link</a>]</td>
  </tr>
  <tr>
    <td>SWE-bench Multimodal</td>
    <td>2024</td>
    <td>Resolution rate</td>
    <td>[<a href="https://arxiv.org/abs/2410.03859">Paper</a>]</td>
    <td>[<a href="https://www.swebench.com/multimodal">Link</a>]</td>
  </tr>
  <tr>
    <td>SWE-Lancer</td>
    <td>2025</td>
    <td>Resolution rate</td>
    <td>[<a href="https://arxiv.org/abs/2502.12115">Paper</a>]</td>
    <td>[<a href="https://github.com/openai/SWELancer-Benchmark">Link</a>]</td>
  </tr>
  <tr>
    <td>Multi-SWE-bench</td>
    <td>2025</td>
    <td>Resolution rate</td>
    <td>[<a href="https://arxiv.org/abs/2504.02605">Paper</a>]</td>
    <td>[<a href="https://github.com/multi-swe-bench/multi-swe-bench/tree/main">Link</a>]</td>
  </tr>

  <!-- Vulnerability Detection -->
  <tr>
    <td rowspan="61"><b>Vulnerability Detection</b></td>
    <td>Choi et al.</td>
    <td>2017</td>
    <td>Accuracy, F1, AUC</td>
    <td>[<a href="https://dl.acm.org/doi/10.5555/3172077.3172102">Paper</a>]</td>
    <td>[<a href="https://github.com/mjc92/buffer_overrun_memory_networks">Link</a>]</td>
  </tr>
  <tr>
    <td>Lin et al.</td>
    <td>2017</td>
    <td>Top-k Recall</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3133956.3138840">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>DGBBench</td>
    <td>2017</td>
    <td>Precision, Recall, F1, Accuracy </td>
    <td>[<a href="https://ieeexplore.ieee.org/document/7965318/">Paper</a>]</td>
    <td>[<a href="https://dbgbench.github.io">Link</a>]</td>
  </tr>
  <tr>
    <td>Juliet</td>
    <td>2018</td>
    <td>Precision, Recall, MCC </td>
    <td>[<a href="#">Paper</a>]</td>
    <td>[<a href="https://samate.nist.gov/SARD/test-suites/112">Link</a>]</td>
  </tr>
  <tr>
    <td>VulDeePecker</td>
    <td>2018</td>
    <td>FN, FP, TN, TP, Precision, Recall, F1, AUC, MCC</td>
    <td>[<a href="https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_03A-2_Li_paper.pdf">Paper</a>]</td>
    <td>[<a href="https://github.com/CGCL-codes/VulDeePecker">Link</a>]</td>
  </tr>
  <tr>
    <td>Draper</td>
    <td>2018</td>
    <td>FN, FP, TN, TP, Precision, Recall, F1, AUC, MCC </td>
    <td>[<a href="https://arxiv.org/abs/1807.04320">Paper</a>]</td>
    <td>[<a href="https://osf.io/d45bw/">Link</a>]</td>
  </tr>
  <tr>
    <td>Devign</td>
    <td>2019</td>
    <td>Accuracy, Precision, Recall, F1, FPR, AUC, Precision@K,MCC </td>
    <td>[<a href="https://arxiv.org/abs/1909.03496">Paper</a>]</td>
    <td>[<a href="https://github.com/epicosy/devign">Link</a>]</td>
  </tr>
  <tr>
    <td>Ponta et al.</td>
    <td>2019</td>
    <td>AUC, F1</td>
    <td>[<a href="https://dl.acm.org/doi/10.1109/MSR.2019.00064">Paper</a>]</td>
    <td>[<a href="https://github.com/SAP/project-kb">Link</a>]</td>
  </tr>
  <tr>
    <td>BigVul</td>
    <td>2020</td>
    <td>Accuracy, Precision, Recall, F1, FPR, AUC, Precision@K, MCC</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3379597.3387501">Paper</a>]</td>
    <td>[<a href="https://github.com/ZeoVan/MSR_20_Code_vulnerability_CSV_Dataset">Link</a>]</td>
  </tr>
  <tr>
    <td>ReVeal</td>
    <td>2020</td>
    <td>Accuracy, Precision, Recall, F1, FPR, AUC, Precision@K </td>
    <td>[<a href="https://www.computer.org/csdl/journal/ts/2022/09/09448435/1ugE8leB4Va">Paper</a>]</td>
    <td>[<a href="https://github.com/VulDetProject/ReVeal">Link</a>]</td>
  </tr>
  <tr>
    <td>SmartBugs</td>
    <td>2020</td>
    <td>Precision, Recall, F1, Top-N Accuracy, MAR, MFR</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3324884.3415298">Paper</a>]</td>
    <td>[<a href="https://smartbugs.github.io">Link</a>]</td>
  </tr>
  <tr>
    <td>Great</td>
    <td>2020</td>
    <td>Precision, Recall, Accuracy </td>
    <td>[<a href="https://openreview.net/forum?id=B1lnbRNtwr">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/3954944">Link</a>]</td>
  </tr>
  <tr>
    <td>Magma</td>
    <td>2020</td>
    <td>ROC-AUC</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3428334">Paper</a>]</td>
    <td>[<a href="https://hexhive.epfl.ch/magma/">Link</a>]</td>
  </tr>
  <tr>
    <td>SolidiFI</td>
    <td>2020</td>
    <td>FN, FP</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3395363.3397385">Paper</a>]</td>
    <td>[<a href="https://github.com/DependableSystemsLab/SolidiFI-benchmark">Link</a>]</td>
  </tr>
  <tr>
    <td>SySeVR</td>
    <td>2021</td>
    <td>FPR, FNR, Precision, Recall, F1</td>
    <td>[<a href="https://ieeexplore.ieee.org/iel7/8858/4358699/09321538.pdf">Paper</a>]</td>
    <td>[<a href="https://github.com/SySeVR/SySeVR">Link</a>]</td>
  </tr>
  <tr>
    <td>D2A</td>
    <td>2021</td>
    <td>Precision, Recall, MCC</td>
    <td>[<a href="https://dl.acm.org/doi/10.1109/ICSE-SEIP52600.2021.00020">Paper</a>]</td>
    <td>[<a href="https://github.com/ibm/D2A">Link</a>]</td>
  </tr>
  <tr>
    <td>PatchDB</td>
    <td>2021</td>
    <td>Precision, Recall, F1</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/9505097/">Paper</a>]</td>
    <td>[<a href="https://github.com/SunLab-GMU/PatchDB">Link</a>]</td>
  </tr>
  <tr>
    <td>CVEFixes</td>
    <td>2021</td>
    <td>Accuracy, Precision, Recall, F1, FPR</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3475960.3475985">Paper</a>]</td>
    <td>[<a href="https://github.com/secureIT-project/CVEfixes">Link</a>]</td>
  </tr>
  <tr>
    <td>CrossVul</td>
    <td>2021</td>
    <td>Accuracy, Precision, Recall, F1, FPR</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3468264.3473122">Paper</a>]</td>
    <td>[<a href="https://doi.org/10.5281/zenodo.4734050">Link</a>]</td>
  </tr>
  <tr>
    <td>VCmatch</td>
    <td>2022</td>
    <td>AUC, F1</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/9825908/">Paper</a>]</td>
    <td>[<a href="https://figshare.com/s/0f3ed11f9348e2f3a9f8">Link</a>]</td>
  </tr>
  <tr>
    <td>VUDENC</td>
    <td>2022</td>
    <td>Precision, Recall, F1, Accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.1016/j.infsof.2021.106809">Paper</a>]</td>
    <td>[<a href="https://github.com/LauraWartschinski/VulnerabilityDetection?tab=readme-ov-file">Link</a>]</td>
  </tr>
  <tr>
    <td>SARD</td>
    <td>2023</td>
    <td>Accuracy, Precision,Recall, F1</td>
    <td>[<a href="https://www.nist.gov/itl/ssd/software-quality-group/samate/software-assurance-reference-dataset-sard">Paper</a>]</td>
    <td>[<a href="https://samate.nist.gov/SARD">Link</a>]</td>
  </tr>
  <tr>
    <td>DiverseVul</td>
    <td>2023</td>
    <td>Accuracy, Precision, Recall, F1, FPR</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3607199.3607242">Paper</a>]</td>
    <td>[<a href="https://github.com/wagner-group/diversevul">Link</a>]</td>
  </tr>
  <tr>
    <td>Web3Bugs</td>
    <td>2023</td>
    <td>TP,TN, FP, FN</td>
    <td>[<a href="https://dl.acm.org/doi/10.1109/ICSE48619.2023.00061">Paper</a>]</td>
    <td>[<a href="https://github.com/ZhangZhuoSJTU/Web3Bugs">Link</a>]</td>
  </tr>
  <tr>
    <td>DeFi Hacks</td>
    <td>2023</td>
    <td>TP,TN, FP, FN</td>
    <td>[<a href=". https://wooded-meter-1d8.notion.site/0e85e02c5ed34df3855ea9f3ca40f53b?v=22e5e2c506ef4caeb40b4f78e23517ee">Paper</a>]</td>
    <td>[<a href="https://wooded-meter-1d8.notion.site/0e85e02c5ed34df3855ea9f3ca40f53b?v=22e5e2c506ef4caeb40b4f78e23517ee">Link</a>]</td>
  </tr>
  <tr>
    <td>VulBench</td>
    <td>2023</td>
    <td>Precision, Recall, F1</td>
    <td>[<a href="https://openreview.net/forum?id=Q3GVrWRKuB">Paper</a>]</td>
    <td>[<a href="https://github.com/Hustcw/VulBench">Link</a>]</td>
  </tr>
  <tr>
    <td>OWASP</td>
    <td>2023</td>
    <td>Accuracy</td>
    <td>[<a href="https://github.com/OWASP-Benchmark/BenchmarkJava">Paper</a>]</td>
    <td>[<a href="https://owasp.org/www-project-benchmark">Link</a>]</td>
  </tr>
  <tr>
    <td>TreeVul</td>
    <td>2023</td>
    <td>F1, Macro-F1, MCC</td>
    <td>[<a href="https://dl.acm.org/doi/10.1109/ICSE48619.2023.00088">Paper</a>]</td>
    <td>[<a href="https://figshare.com/articles/online_resource/TreeVul_-_Replication_Package/19727050">Link</a>]</td>
  </tr>
  <tr>
    <td>FormAI</td>
    <td>2023</td>
    <td>Precision, Recall, F1, Accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3617555.3617874">Paper</a>]</td>
    <td>[<a href="https://github.com/FormAI-Dataset">Link</a>]</td>
  </tr>
  <tr>
    <td>Hu et al.</td>
    <td>2023</td>
    <td>Hit #</td>
    <td>[<a href="https://www.computer.org/csdl/proceedings-article/tps-isa/2023/238500a297/1UAj658V0c0">Paper</a>]</td>
    <td>[<a href="https://github.com/git-disl/GPTLens">Link</a>]</td>
  </tr>
  <tr>
    <td>FalconVulnDB</td>
    <td>2024</td>
    <td>Precision, Recall, F1, Accuracy</td>
    <td>[<a href="https://arxiv.org/abs/2307.06616">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>FormAI-v2</td>
    <td>2024</td>
    <td>Average Property Violations Per File/Line</td>
    <td>[<a href="https://arxiv.org/abs/2404.18353v1/">Paper</a>]</td>
    <td>[<a href="https://github.com/FormAI-Dataset">Link</a>]</td>
  </tr>
  <tr>
    <td>MoreFixes</td>
    <td>2024</td>
    <td>Accuracy, Precision, Recall, F1</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3663533.3664036">Paper</a>]</td>
    <td>[<a href="https://github.com/JafarAkhondali/Morefixes">Link</a>]</td>
  </tr>
  <tr>
    <td>VulEval</td>
    <td>2024</td>
    <td>Precision, Recall, F1, MCC, Precision@k, Recall@k </td>
    <td>[<a href="https://arxiv.org/abs/2404.15596">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>InterPVD</td>
    <td>2024</td>
    <td>FPR, FNR, Accuracy, Precision, F1</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3597503.3639218">Paper</a>]</td>
    <td>[<a href="https://github.com/CGCLcodes/VulTrigger">Link</a>]</td>
  </tr>
  <tr>
    <td>ReposVul</td>
    <td>2024</td>
    <td>Accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3639478.3647634">Paper</a>]</td>
    <td>[<a href="https://github.com/Eshe0922/ReposVul">Link</a>]</td>
  </tr>
  <tr>
    <td>MegaVul</td>
    <td>2024</td>
    <td>Accuracy, Precision, Recall, F1</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3643991.3644886">Paper</a>]</td>
    <td>[<a href="https://github.com/Icyrockton/MegaVul">Link</a>]</td>
  </tr>
  <tr>
    <td>SecLLMHolmes</td>
    <td>2024</td>
    <td>Response Rate, Accuracy, Correct Reasoning Rate</td>
    <td>[<a href="https://arxiv.org/abs/2312.12575">Paper</a>]</td>
    <td>[<a href="https://github.com/ai4cloudops/SecLLMHolmes">Link</a>]</td>
  </tr>
  <tr>
    <td>VulDetectBench</td>
    <td>2024</td>
    <td>F1, Accuracy</td>
    <td>[<a href="https://arxiv.org/abs/2406.07595">Paper</a>]</td>
    <td>[<a href="https://github.com/Sweetaroo/VulDetectBench">Link</a>]</td>
  </tr>
  <tr>
    <td>SC-LOC</td>
    <td>2024</td>
    <td>Precision, Recall, Accuracy, F1-Score</td>
    <td>[<a href="https://arxiv.org/abs/2404.00287">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>Ma et al.</td>
    <td>2024</td>
    <td>Precision, Recall, Accuracy, F1-Score</td>
    <td>[<a href="https://arxiv.org/abs/2403.16073">Paper</a>]</td>
    <td>[<a href="https://sites.google.com/view/iaudittool/home">Link</a>]</td>
  </tr>
  <tr>
    <td>FELLMVP</td>
    <td>2024</td>
    <td>Precision, Recall, Accuracy, F1-Score</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/10664408/">Paper</a>]</td>
    <td>[<a href="https://drive.google.com/drive/folders/1uSXaY7vOvcwQIwXs5JwD9C2hxK9bFMsZ">Link</a>]</td>
  </tr>
  <tr>
    <td>Yıldırım et al.</td>
    <td>2024</td>
    <td>Accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3655693.3655701">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>Vulcorpus</td>
    <td>2024</td>
    <td>Accuracy, Improvement Suggestion</td>
    <td>[<a href="https://arxiv.org/abs/2406.18894">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>Fang et al.</td>
    <td>2024</td>
    <td>Not vulnerability detection </td>
    <td>[<a href="https://arxiv.org/abs/2404.08144">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>SLFHunter</td>
    <td>2024</td>
    <td>TP,TN, FP, FN, F1-score</td>
    <td>[<a href="https://www.sciencedirect.com/science/article/pii/S0167404824002761">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>Guo et al.</td>
    <td>2024</td>
    <td>Precision, Recall, F1-Score</td>
    <td>[<a href="https://dl.acm.org/doi/10.1007/978-3-031-70879-4_14">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/10975439">Link</a>]</td>
  </tr>
  <tr>
    <td>VulnPatchPairs</td>
    <td>2024</td>
    <td>Precision, Recall, F1, Accuracy, FPR, FNR</td>
    <td>[<a href="https://dl.acm.org/doi/10.5555/3698900.3699138">Paper</a>]</td>
    <td>[<a href="https://github.com/niklasrisse/VPP">Link</a>]</td>
  </tr>
  <tr>
    <td>Real-Vul</td>
    <td>2024</td>
    <td>Precision, Recall, F1, Accuracy, AUC</td>
    <td>[<a href="https://ieeexplore.ieee.org/document/10587162/">Paper</a>]</td>
    <td>[<a href="https://zenodo.org/records/12707476">Link</a>]</td>
  </tr>
  <tr>
    <td>PairVul</td>
    <td>2024</td>
    <td>Accuracy, Pairwise Accuracy, F1-score, MCC </td>
    <td>[<a href="https://arxiv.org/abs/2406.11147">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>VulSmart</td>
    <td>2024</td>
    <td>Precision, Recall, F1, Accuracy</td>
    <td>[<a href="https://arxiv.org/abs/2409.10574">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>KernJC</td>
    <td>2024</td>
    <td>TP, TN, FP, FN, Precision, Recall, F1, Accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3678890.3678891">Paper</a>]</td>
    <td>[<a href="#">Link</a>]</td>
  </tr>
  <tr>
    <td>LLM4Vuln</td>
    <td>2025</td>
    <td>TP,TN, FP, FN, F1-score</td>
    <td>[<a href="https://openreview.net/forum?id=f6W3NJAfRM">Paper</a>]</td>
    <td>[<a href="https://anonymous.4open.science/r/LLM4Vuln/README.md">Link</a>]</td>
  </tr>
  <tr>
    <td>VULZOO</td>
    <td>2025</td>
    <td>Precision, Recall, F1, Accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3691620.3695345">Paper</a>]</td>
    <td>[<a href="https://github.com/NUS-Curiosity/VulZoo">Link</a>]</td>
  </tr>
  <tr>
    <td>CWE-Bench-Java</td>
    <td>2025</td>
    <td>#Detected, Avg. False Discovery Rate, Avg. F1, Precision, Recall</td>
    <td>[<a href="https://openreview.net/forum?id=9LdJDU7E91">Paper</a>]</td>
    <td>[<a href="https://github.com/iris-sast/iris">Link</a>]</td>
  </tr>
  <tr>
    <td>CASTLE</td>
    <td>2025</td>
    <td>CASTLE Score, Combination Score, Precision, Recall, Accuracy</td>
    <td>[<a href="https://arxiv.org/abs/2503.09433">Paper</a>]</td>
    <td>[<a href="https://github.com/CASTLE-Benchmark">Link</a>]</td>
  </tr>
  <tr>
    <td>SecVulEval</td>
    <td>2025</td>
    <td>human-evaluated scoring rubric</td>
    <td>[<a href="https://arxiv.org/abs/2505.19828">Paper</a>]</td>
    <td>[<a href="https://huggingface.co/datasets/arag0rn/SecVulEval">Link</a>]</td>
  </tr>
  <tr>
    <td>JITVUL</td>
    <td>2025</td>
    <td>Precision, Recall, F1, Accuracy</td>
    <td>[<a href="https://aclanthology.org/2025.acl-long.1490.pdf">Paper</a>]</td>
    <td>[<a href="https://anonymous.4open.science/r/JitVul-C6C7/">Link</a>]</td>
  </tr>
  <tr>
    <td>Li et al.</td>
    <td>2025</td>
    <td>Precision, Recall, F1, Accuracy</td>
    <td>[<a href="https://arxiv.org/abs/2503.01449">Paper</a>]</td>
    <td>[<a href="https://github.com/soarsmu/SVD-Bench">Link</a>]</td>
  </tr>
  <tr>
    <td>BinPool</td>
    <td>2025</td>
    <td>Precision, Recall, F1, Accuracy</td>
    <td>[<a href="https://dl.acm.org/doi/10.1145/3696630.3728606">Paper</a>]</td>
    <td>[<a href="https://docs.google.com/spreadsheets/d/1qztIwB8xJ10H-2HLX15vI29Ze7yFDOrv7kDQ4JUi1g8/edit?gid=1679944928#gid=1679944928">Link</a>]</td>
  </tr>
  <tr>
    <td>ICVul</td>
    <td>2025</td>
    <td>Precision, Recall, F1, Accuracy</td>
    <td>[<a href="https://arxiv.org/abs/2505.08503">Paper</a>]</td>
    <td>[<a href="https://github.com/Chaomeng-Lu/ICVul">Link</a>]</td>
  </tr>
</table>


