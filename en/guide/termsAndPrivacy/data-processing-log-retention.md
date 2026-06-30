
---
title: Data Processing & Log Retention Statement
icon: shield-heart
---

Last updated: 30 June 2026

This statement explains how **HK Word Origin New Wisdom Technology Limited**, operating the TokensMind brand, handles API content, metadata, logs, storage locations, retention, access, and abuse investigation.

## 1. Processing overview

TokensMind acts as an API aggregation and routing platform. When a user sends an API request, TokensMind authenticates the API key, checks balance and limits, routes the request to the selected or applicable model provider, returns the provider response, calculates usage, and records billing/security metadata.

## 2. Data categories

| Data type | Stored by TokensMind? | Typical purpose | Typical retention |
| --- | --- | --- | --- |
| Prompt content | Not persistently stored by default | Transient routing and API delivery | Transient processing only by default |
| Response content | Not persistently stored by default | Return model output to user | Transient processing only by default |
| API request metadata | Yes | Authentication, routing, billing, reliability, abuse detection | Up to 6 years |
| Model selection/routed model | Yes | Billing, audit, troubleshooting, supplier reconciliation | Up to 6 years |
| Token usage/usage units | Yes | Credit deduction, billing, invoices, user dashboard | Up to 6 years |
| IP address | Yes | Security, fraud prevention, abuse detection, legal compliance | Up to 24 months, longer for investigations |
| User agent/device/browser data | Yes | Security, fraud prevention, account protection | Up to 24 months, longer for investigations |
| Error logs/status codes/latency | Yes | Troubleshooting, reliability, billing correction | Up to 24 months, longer for disputes |
| Payment/order/refund records | Yes | Billing, refunds, chargebacks, audit, tax | Up to 7 years |
| Support tickets and user-submitted samples | Yes, if submitted | Support, dispute handling, abuse review | Up to 3 years after closure, longer if legally required |

## 3. Storage location

TokensMind uses cloud infrastructure and service providers selected for security, reliability, and operational needs. Data may be stored or processed in Japan, United States and other regions where our cloud, payment, security, analytics, support, or model provider infrastructure operates.

## 4. Transmission to model providers

Prompt content, request parameters, files, and related payload data are transmitted to the model provider selected by the user or routed by TokensMind to complete the API request.

Model providers may include OpenAI, Anthropic, Google, Qwen, Kimi, MiniMax, DeepSeek, Zhipu AI, or other providers shown in the dashboard or documentation.

Provider processing, logging, safety review, retention, and training-use rules are governed by the relevant provider terms, data policies, and commercial arrangements.

TokensMind does not knowingly use customer prompt or response content to train TokensMind-owned models, and does not knowingly submit customer prompt or response content to third parties for model training.

## 5. Human access

TokensMind personnel do not proactively review prompt or response content. Because prompt and response content is not persistently stored by default, routine human review is not available.

Authorized personnel may access account data, usage metadata, payment records, support materials, and security records where needed for:

- Customer support.
- Billing correction.
- Refund handling.
- Abuse investigation.
- Fraud prevention.
- Security incident response.
- Chargeback evidence.
- Legal or regulatory compliance.

Access is limited to personnel with a business need and is subject to access control.

## 6. Abuse investigation without content retention

TokensMind investigates abuse primarily through:

- Account ID and organization ID.
- API key ID.
- IP address, user agent, device, country, and login history.
- Request timestamp, endpoint, model, routed provider, token volume, status code, and error code.
- Rate, frequency, concurrency, spend velocity, and abnormal usage patterns.
- Payment method, order history, chargeback status, refund requests, and risk signals.
- Upstream provider alerts, moderation outcomes, or safety signals.
- User reports and voluntarily submitted request/response samples.
- Lawful requests from regulators, courts, law enforcement, payment partners, or card networks.

Where legally permitted and necessary, TokensMind may temporarily preserve limited evidence related to suspected serious abuse, fraud, or illegal activity.

## 7. Retention exceptions

We may retain data longer than the normal period where required for:

- Payment disputes or chargebacks.
- Fraud, abuse, or security investigations.
- Tax, accounting, audit, or legal obligations.
- Court orders, regulatory requests, law enforcement requests, or preservation obligations.
- Protection of TokensMind, users, suppliers, payment partners, or third parties.

## 8. Contact

Operator: **HK Word Origin New Wisdom Technology Limited**  
Brand/Product: TokensMind  
Email: leon@tokensmind.ai

