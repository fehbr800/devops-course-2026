# Structure of a Systematic Review Report

A systematic review report provides a comprehensive summary of the methods and results of a review. It follows a structured format to ensure clarity, transparency, and reproducibility.

---

## 1. Title Page

- **Title:** Using metrics in integration testing to optimize change validation time in DevOps pipelines in Fintech systems.
- **Authors:** Gabriel Alves, Matheus Emanoel, Sara Cristina.
- **Date:** 2026/04/13.  
- **Contact:** g.alves@aluno.ufr.edu.br, matheus.emanoel@aluno.ufr.edu.br, sara.cristina@aluno.ufr.edu.br
---

## 2. Abstract

- **Context:**  
  In software development environments, the use of integration testing metrics helps reveal points of productivity loss and, consequently, time waste. This creates a clear need to define and apply countermeasures that mitigate such bottlenecks, preventing delays in final delivery and preserving overall process efficiency. Identifying the most effective testing tools is especially relevant for financial institutions, where informed tool selection improves productivity and avoids inefficient experimentation with low-impact alternatives.
  
  Within this scenario, the use of metrics in integration testing becomes a strategic approach for understanding the performance of the change-validation process. The analysis of these metrics enables teams to identify bottlenecks, improve testing efficiency, and provide faster feedback to development teams. Therefore, understanding how metrics can be used to optimize change-validation time in DevOps pipelines is essential for improving software quality and increasing development-process efficiency.

- **Objectives:** Clear statement of the main objectives. 
  - Analysis of test architectures used by fintech companies, including tests between microservices, integration with databases, payment APIs, and external services.

  - Analysis of tools used for integration test automation, as well as tools related to security, compliance, and monitoring within DevOps pipelines.

  - Analysis of metrics related to pipeline performance, such as test execution time, total pipeline duration, feedback time for developers, and frequency of test failures.
 
 
- **Methods:** Summary of the methods used, including:
   - This study was conducted as a systematic literature review based on bibliographic research, including analysis of scientific articles, technical documentation, and technical reports. The primary data source was Google Scholar, searched using structured query strings combining terms related to fintech, DevOps pipelines, integration testing, and performance metrics. The search was restricted to articles published between 2022 and 2025, written in English, and categorized as review articles. Applying these filters, 16 articles were identified. Studies were then screened by title and abstract relevance, followed by full-text reading, resulting in 5 articles included in the final synthesis.

- **Results:** Main findings, including:
  - Number of studies included  
  - Main results  
- **Conclusions:** Main conclusions and implications for practice and research.  


## 3. Introduction

- **Context:** Detailed description of the problem and motivation for the review.  
  - As equipes de desenvolvimento de software que operam em ambientes de ritmo acelerado enfrentam uma pressão crescente para entregar sistemas confiáveis ​​com ciclos de lançamento mais curtos. Nesse contexto, as práticas de DevOps e os pipelines de CI/CD tornaram-se essenciais para garantir a entrega contínua, mantendo a qualidade do software. No entanto, a eficiência desses pipelines é diretamente afetada pelo desempenho dos testes de integração — uma etapa crítica responsável por validar as interações entre serviços, bancos de dados, APIs externas e módulos internos.
  Em ambientes de tecnologia financeira (fintech), esse desafio é amplificado. A alta complexidade dos sistemas distribuídos, os rigorosos requisitos regulatórios e a baixa tolerância a falhas exigem estratégias de teste robustas e bem monitoradas. Apesar disso, muitas equipes ainda carecem de dados objetivos para identificar onde o tempo está sendo perdido em seus pipelines, quais ferramentas são mais eficazes para seu contexto e quais contramedidas podem ser aplicadas para reduzir os gargalos de produtividade.  O uso de métricas de teste de integração surge como uma abordagem estratégica para abordar essas lacunas. Ao coletar e analisar sistematicamente métricas — como tempo de execução de teste, duração do pipeline, taxa de falhas e tempo de feedback do desenvolvedor — as equipes podem tomar decisões baseadas em dados que melhoram diretamente a velocidade de entrega e a confiabilidade do software.

- **Objectives:** Research questions or specific objectives.  
  - RQ-1: During software development, what are the main productivity and time bottlenecks correlated with integration testing metrics, and what countermeasures should be applied to reduce their impact on productivity and final delivery?
  - RQ-2: How can the use of metrics accelerate the software delivery process and improve quality, ensuring greater reliability based on concrete data and making the process more efficient?
  - RQ-3: What is the importance of identifying the most efficient testing tools for the financial market?

- **Justification:** Importance of the review and expected impact. 
    - The relevance of this review lies in the growing adoption of DevOps practices within fintech companies and the lack of consolidated evidence on which metrics and tools most effectively optimize change-validation time in integration pipelines. Understanding these factors is essential not only for improving internal development efficiency, but also for reducing costs, minimizing failure risks, and accelerating time-to-market in a highly regulated sector.
    Furthermore, identifying the most suitable testing tools for the financial market prevents teams from investing time and resources in low-impact solutions, contributing directly to more productive and reliable development workflows. This review aims to synthesize existing evidence and provide actionable insights for both practitioners and researchers working at the intersection of DevOps, software testing, and financial systems.



## 4. Methods

- **Protocol and Registration:**  
  - This review did not follow a formally registered protocol. However, the study selection and reporting process was guided by the PRISMA (Preferred Reporting Items for Systematic Reviews and Meta-Analyses) framework adapted for bibliographic reviews.

- **Eligibility Criteria:**  
  Use the PICOS model:
  - Population: Fintechs
  - Intervention: *Testing, performance evaluation, and metrics in Fintechs*
  - Comparison  
  - Outcomes  
  - Study type: *Systematic reviews, literature reviews, and empirical studies published between 2022 and 2025, written in English.* 

- **Information Sources:**  
  *Google Scholar*  

- **Search Strategy:**  
  Search strings used, terms and filters applied.  

  *("fintech" OR "financial technology" OR "digital banking") AND ("DevOps" OR "CI/CD" OR "continuous delivery") AND ("DORA metrics" OR "deployment frequency" OR "change failure rate" OR "pipeline metrics")*

**Study Selection:**  
  Screening and article selection process.  

<!-- - **Data Extraction:**  
  How the data were collected and organized.  

- **Quality Assessment:**  
  Risk of bias assessment (e.g., Cochrane, GRADE).  

- **Data Synthesis:**  
  Methods used:
  - Meta-analysis  
  - Qualitative synthesis  

- **Heterogeneity:**  
  Statistical methods:
  - I²  
  - Cochran's Q test  

- **Publication Bias:**  
  - Funnel plot  
  - Egger's test  

---

## 5. Results

- **Study Selection:**  
  Flowchart (e.g., PRISMA).  

- **Study Characteristics:**  
  Tables with:
  - Study type  
  - Sample  
  - Interventions  
  - Results  

- **Quality Assessment:**  
  Results of the risk of bias analysis.  

### Synthesis of Results

- **Quantitative (Meta-analysis):**
  - Effect size  
  - Confidence intervals  
  - Graphs (forest plot)  

- **Qualitative:**
  - Identified themes  
  - Patterns across studies  

- **Additional Analyses:**
  - Subgroups  
  - Sensitivity  
  - Meta-regression  

---

## 6. Discussion

- **Summary of Evidence:** Main results and conclusions.  
- **Comparison with Studies:** Relationship with previous research.  
- **Strengths and Limitations:** Strengths and limitations of the study.  
- **Practical Implications:** Applications in practice and industry.  
- **Research Implications:** Suggestions for future work.  

---

## 7. Conclusion

- **General Conclusions:** Final synthesis of the study.  
- **Key Messages:** Main takeaways.  

---

## 8. Acknowledgments

- **Contributors:** People who contributed but are not authors.  
- **Funding:** Sources of support and conflicts of interest.  

---

## 9. References

- Complete list of references used (APA, ABNT, etc.).  

---

## 10. Appendices

- Search strings  
- Extraction forms  
- Supplementary materials   -->
