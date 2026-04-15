# 🐍 Python Test Task — Minimal Accounting Web App 🐍

## Why we use this task

This task is designed to test three things.

* First, we want to see whether you can learn a small business domain fast. In this case, the domain is basic accounting. You do not need deep accounting knowledge before you start, but you should be able to study the topic, make reasonable choices, and explain your logic.
* Second, we want to see whether you can deliver a working solution, not only a prototype idea. The final result should run, be reviewable, and be easy to start.
* Third, we want to see how you work with constraints and ambiguity. The task is intentionally not fully specified. In real work, you will often need to move from a vague request to a converged solution that is clear, practical, and usable.

## Main constraints

Your solution must follow all of these constraints.

* 🐍 Use Python.
* Use (Streamlit)[https://streamlit.io/] for the web UI.
* ⚠️ Do not use ready-made accounting libraries or accounting engines.
* 🐳 A Dockerfile is mandatory.
* ⚠️ If there is no Dockerfile, the submission is not accepted.

## LLM usage

* ⚠️ Use of LLM tools is mandatory for this task.
* ✅ We do not treat LLM usage as cheating. We want to see whether you can use AI well and still stay in control of the solution.
* ⚠️ Your submission must include a prompt history.
* ℹ️ This must show the prompts or prompt log you used while working on the task. It can be a markdown file, text file, or another clear format inside the repository.
* ⚠️ Without prompt history, the submission is not accepted.

## Delivery format

Your final delivery must be a public GitHub repository.

Please make sure that:

* the repository is publicly accessible
* all code needed to run the solution is inside the repository
* the repository contains the Dockerfile
* the repository contains setup and run instructions
* the repository contains the prompt history

⚠️ Before sending the result, double-check that the repository is public and can be opened without access request.

## 🤔 What we will evaluate

We will evaluate the submission using the following criteria.

### 1. Domain understanding

We want to see whether you can understand a small part of accounting well enough to build a useful and coherent solution.

### 2. Working delivery

We want to see a working solution that can be started and reviewed with low effort.

### 3. Convergence under constraints

We want to see whether you can make reasonable product and technical decisions under limited time, limited scope, and incomplete specification.

### 4. Code and structure

We will look at clarity of code, separation of logic, naming, and overall maintainability.

### 5. AI usage quality

We will look at whether you used LLM tools as a support system or only copied output without understanding it.

## 🎯 Product goal

Build a minimal accounting web application that demonstrates a small but coherent accounting flow.

The product should be simple, but it should still make it possible to understand how the system posts basic business events and how those postings affect simple reporting.

## 📋 Goals and success criteria

Your solution should aim to satisfy these goals.

### Goal 1 — Show basic accounting logic

The app should reflect core accounting logic in a small and understandable way.

Success signs:

* the user can create and view basic accounting-related records
* the system applies consistent posting logic
* the behavior is explainable

### Goal 2 — Support a very small reporting layer

The app should make it possible to see a simplified Profit and Loss view and a small partner ledger view.

Success signs:

* the P&L view reflects income and expense movement in a simple way
* the partner ledger view makes it possible to understand balances or movements for customers and vendors

### Goal 3 — Stay pragmatic

The app should be small enough to finish well.

Success signs:

* the solution is focused
* the UI is simple but usable
* the implementation avoids unnecessary complexity

## Fixed accounts

Use a fixed chart of accounts. Do not build account management.

A reasonable starting set is:

* 1000 — Cash
* 1100 — Accounts Receivable
* 2000 — Accounts Payable
* 4000 — Revenue
* 5000 — Expense

You may refine naming or structure slightly if your logic stays simple and coherent.

## Required product direction

Your solution should make it possible to work with a small set of business events that can reasonably affect:

* revenue
* expenses
* customer-side partner balances
* vendor-side partner balances

A good direction is to support small business documents or operations that can later be reflected in reports.

We are not looking for a full accounting system. We are looking for a minimal but sensible product slice.

## Required reports

Your solution should include:

* a simplified Profit and Loss report
* a small partner ledger

The exact report layout is up to you.

The report logic should be understandable and consistent with the model you choose.

## ℹ️ Explicit simplifications

This task is intentionally simplified.

You should keep the solution small and avoid trying to imitate a full ERP or a full accounting package.

The following simplifications are expected and acceptable:

* fixed accounts instead of full chart-of-accounts management
* a narrow set of business flows instead of full accounting coverage
* simplified partner handling
* simplified posting logic
* simplified reporting logic
* no tax engine
* no multi-currency support
* no reconciliation logic
* no advanced permissions model
* no need for production-grade audit features

You may add small improvements if they support the core idea, but do not let them distract from the main task.

## 🚊 Scope guidance

The task is intentionally not fully specified.

This is part of the test.

You are expected to decide:

* what minimal product flow is enough
* what data model is enough
* how posting should work in your design
* how to represent partner ledger in a simple and coherent way
* how to keep the UI small and clear

We care more about quality of judgment than about amount of features.

## ✍️ Repository contents

Your GitHub repository should contain at least:

* application source code
* Dockerfile
* README with run instructions
* prompt history used during the task
* short explanation of your product and technical decisions

## 🧪 Acceptance conditions

The submission will not be accepted if any of the following is missing:

* public GitHub repository
* working Python and Streamlit solution in the repository
* Dockerfile
* prompt history

Please verify public access before sending the repository.

## Final note

Do not try to build too much.

A smaller solution with clear logic, working flow, and good judgment is stronger than a larger solution with weak structure and unclear behavior.
