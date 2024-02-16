# Zero Knowledge Proofs Security Review Report: Summa, Proof of Solvency Protocol (Version V1)

## Table of Contents

## 1. Executive Summary

## 2. Summa Security Review Dashboard

#### Table 2.1: Application Summary

| Name        | Version         | Type | Platform |
|-------------|-----------------|------|----------|
| Summa-Solvency | 95d63fe1a55935542810138aa5d8de7f50f4e94b | Rust,Solidity | Ethereum, |

#### Table 2.2: Engagement Summary

| Date        | Method         | No. of Reviewers | Level of Effort |
|-------------|-----------------|------|----------|
| Jan 12 -Feb 28, 2024 | Manual and Tools | 10 | 60 person-weeks |

#### Table 2.3: Vulnerability Summary

| Name                           | Number | Resolved |
|--------------------------------|--------|----------|
| Critical-Severity Issues       | 0      | 0        |
| High-Severity Issues           | 0      | 0        |
| Medium-Severity Issues         | 0      | 0        |
| Low-Severity Issues            | 0      | 0        |
| Warning-Severity Issues        | 0      | 0        |
| Informational-Severity Issues  | 0      | 0        |
| **TOTAL**                      | **0**  | **0**    |


#### Table 2.4: Vulnerability Category Summary

| Name                      | Quantity |
|---------------------------|--------|
| Cryptographic Vulnerability | 0      |
| Data Validation            | 0      |
| Maintainability            | 0      |



## Audit Goals and Scope
### Audit Goals
### Audit Methodlogy and Scope
### Classification of Vulnerabilities

#### Table 3.1: Severity Level Definitions

| Likelihood/Severity | Somewhat Bad | Bad      | Very Bad | Protocol Breaking |
|---------------------|--------------|----------|----------|-------------------|
| Not Likely          | Info         | Warning  | Low      | Medium            |
| Likely              | Warning      | Low      | Medium   | High              |
| Very Likely         | Low          | Medium   | High     | Critical          |

#### Table 3.2: Likelihood Level Definitions

| Likelihood Level  | Description |
|--------------|-------------|
| Not Likely   | A small set of users must make a specific mistake |
| Likely       | Requires a complex series of steps by almost any user(s) -OR- Requires a small set of users to perform an action |
| Very Likely  | Can be easily performed by almost anyone |

#### Table 3.3: Impact Level Definitions

| Impact Level   | Description |
|------------------|-------------|
| Somewhat Bad     | Inconveniences a small number of users and can be fixed by the user |
| Bad              | Affects a large number of people and can be fixed by the user -OR- Affects a very small number of people and requires aid to fix |
| Very Bad         | Affects a large number of people and requires aid to fix -OR- Disrupts the intended behavior of the protocol for a small group of users through no fault of their own |
| Protocol Breaking| Disrupts the intended behavior of the protocol for a large group of users through no fault of their own |



## Vulnerability Report
### Detailed descriptions of the issues


