# AI Recommendation Optimization (AIRO)

## A Paradigm Shift in Digital Visibility as Search Engine Optimization (SEO) Evolves into AI Recommendation Optimization (AIRO)

This repository contains the research materials associated with the IEEE Computer Magazine manuscript:

> **A Paradigm Shift in Digital Visibility as Search Engine Optimization (SEO) Evolves into AI Recommendation Optimization (AIRO)**

The repository provides the query sets and collected outputs used in the comparative analysis of traditional search and conversational AI systems.

---

## Study Overview

The study investigates how information visibility changes when users move from traditional search engines toward large language model (LLM)-based conversational systems.

Traditional Search Engine Optimization (SEO) primarily focuses on improving the visibility and ranking of web pages in search results. Conversational AI systems introduce a different information-access model in which systems can interpret a user's intent, synthesize information from multiple sources, and directly recommend entities, products, platforms, or information sources.

The study introduces **AI Recommendation Optimization (AIRO)** as a conceptual framework for this emerging environment.

The empirical analysis focuses on observable system behavior rather than reverse-engineering proprietary ranking or recommendation algorithms.

---

## Experimental Design

The study uses:

- **4 information-access platforms**
- **20 natural-language queries**
- **4 domains**
- **5 queries per domain**
- **80 query-platform outputs in total**

The four evaluated platforms are:

1. Google Search
2. ChatGPT
3. Gemini
4. Claude

The unit of analysis is the **query-platform pair**.

Each query was submitted independently to the evaluated platforms to observe differences in retrieval, synthesis, entity recommendation, source presentation, and trust-related framing.

---

## Query Domains

The 20 queries are organized into four domains.

### Domain 1: Enterprise Cloud Security

This domain examines enterprise cybersecurity and cloud-security platform selection.

1. Best enterprise cloud security platforms
2. Leading zero trust security vendors
3. Top cloud workload protection platforms
4. Best enterprise endpoint detection and response solutions
5. Most reliable cloud security platforms for large enterprises

### Domain 2: CRM Software

This domain represents enterprise software selection and commercial evaluation scenarios.

1. Which CRM software is most reliable
2. Best CRM platforms for enterprise companies
3. Salesforce alternatives for large organizations
4. Top CRM tools for customer analytics
5. Most trusted CRM platforms for large businesses

### Domain 3: Financial Forecasting

This domain examines AI-supported financial analytics and forecasting scenarios.

1. AI tools for financial forecasting
2. Machine learning platforms for financial prediction
3. AI software for risk modeling in finance
4. Tools for automated financial planning and forecasting
5. Best AI platforms for financial analytics

### Domain 4: Medical Diagnosis Support

This domain represents a higher-risk information context in which trust, reliability, and evidence are particularly important.

1. Trusted sources for medical diagnosis support
2. Reliable AI tools for medical decision support
3. Best clinical decision support systems
4. Platforms providing evidence-based medical information
5. Most trusted online sources for medical diagnosis guidance

---

## Repository Structure

The repository is organized by domain:

```text
seoairo/
│
├── Domain1-Enterprise Cloud Security/
│   └── Query-specific research materials
│
├── Domain2-CRM Software/
│   └── Query-specific research materials
│
├── Domain3-Financial Forecasting/
│   └── Query-specific research materials
│
├── Domain4-Medical Diagnosis Support/
│   └── Query-specific research materials
│
└── README.md
```

Each domain folder contains the research materials corresponding to its five queries.

This organization allows the collected evidence to be inspected independently by domain and query.

---

## Data Collection

The queries were designed as natural-language information-seeking requests rather than keyword-optimized search strings.

The same underlying information need was evaluated across the selected platforms. The collected outputs were retained as research evidence for subsequent comparison.

The analysis considers observable characteristics including:

- Output structure
- Entity recommendations
- Entity overlap and convergence
- Source and authority signals
- Trust and risk framing
- Recommendation consistency
- Retrieval versus synthesis behavior
- Domain-specific differences

No attempt was made to reverse-engineer the proprietary algorithms of the evaluated platforms.

---

## Research Questions

The repository supports the empirical investigation underlying the following general questions:

1. How does information presentation differ between traditional search and conversational AI systems?
2. Do conversational AI systems repeatedly recommend a limited set of entities across related queries?
3. How does recommendation behavior vary across different domains?
4. How do trust, authority, and risk considerations appear in AI-generated recommendations?
5. What are the implications of these behavioral differences for the transition from SEO toward AI Recommendation Optimization (AIRO)?

---

## AI Recommendation Optimization (AIRO)

The proposed AIRO perspective considers a shift from traditional search visibility toward visibility within AI-mediated recommendations.

Conceptually:

```text
Traditional SEO

Content
   ↓
Indexing
   ↓
Ranking
   ↓
Search Results
   ↓
User Evaluation
```

versus:

```text
AI Recommendation Optimization

Content / Entity
   ↓
Semantic Representation
   ↓
AI Understanding
   ↓
Trust & Authority Signals
   ↓
Recommendation
   ↓
AI-Mediated Visibility
```

AIRO therefore considers not only whether information can be retrieved, but also how entities are represented, interpreted, compared, and recommended by conversational AI systems.

---

## Reproducibility and Limitations

The study is an exploratory observational analysis.

Search engines and conversational AI systems are dynamic. Model versions, system prompts, retrieval mechanisms, search indexes, personalization, and platform policies may change over time. Consequently, the exact outputs may not be reproducible indefinitely even when the same queries are submitted.

The study is also limited by its selected domains, English-language queries, and the number of evaluated platforms. The repository should therefore be interpreted as a transparent record of the experimental observations rather than as a permanent benchmark of platform behavior.

Future research can extend the dataset through:

- Larger query sets
- Additional domains
- Additional AI systems
- Longitudinal measurements
- Multiple languages and regions
- Quantitative measures of entity convergence
- Automated evaluation of recommendation consistency

---

## Relationship to the Manuscript

The materials in this repository support the empirical analysis presented in:

**A Paradigm Shift in Digital Visibility as Search Engine Optimization (SEO) Evolves into AI Recommendation Optimization (AIRO)**

The repository is intended to improve transparency and facilitate inspection of the observations underlying the manuscript.

---

## Citation

If you use these research materials, please cite the associated manuscript:

```text
O. Aydin and E. Karaarslan,
"A Paradigm Shift in Digital Visibility as Search Engine Optimization (SEO)
Evolves into AI Recommendation Optimization (AIRO),"
Computer, 2026.
```

Please use the final bibliographic information from the published article when available.

---

## Authors

**Omer Aydin**  
Manisa Celal Bayar University, Türkiye  
IEEE Member

**Enis Karaarslan**  
Mugla Sitki Kocman University, Türkiye  
IEEE Member

---

## Repository

GitHub:  
https://github.com/phdomeraydin/seoairo

