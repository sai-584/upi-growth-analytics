# UPI Growth Analytics 🇮🇳

An interactive Power BI dashboard analyzing the growth of UPI (Unified Payments Interface) and digital financial inclusion in India from 2016-17 to 2022-23.

## 📊 Project Overview

UPI has transformed India's payments landscape — from a niche digital experiment in 2016 to a national infrastructure processing tens of billions of transactions a year. This project explores that growth story using real government and NPCI-sourced data, combining SQL-style analytical thinking with Power BI's Power Query and DAX.

## 🎯 Objectives

- Analyze UPI transaction volume and value growth (yearly and monthly)
- Track bank adoption of UPI over time
- Understand how average transaction size evolved — and what that reveals about changing usage patterns
- Practice real-world DAX, including CALCULATE, DIVIDE, and explicit measures

## 🗂️ Data Sources

- **Yearly UPI transactional data (2016-17 to 2022-23)** — Rajya Sabha parliamentary reply, sourced via data.gov.in
- **Monthly UPI data (April 2016 – December 2021)** — NPCI-sourced dataset, via Kaggle

## 🏗️ Dashboard Structure

| Page | Contents |
|---|---|
| **Home** | Project title, navigation |
| **Yearly Overview** | UPI Volume vs Value growth (2016-17 to 2022-23) |
| **Monthly Trends & Bank Adoption** | Monthly transaction volume, bank adoption curve, combined Volume vs Value trend |
| **Key Metrics & Insights** | Average transaction size by year, year-wise summary table, total volume/value, CALCULATE-based year isolation, growth % |

## 🔑 Key Insights

- ~47x growth in UPI transaction volume between 2016-17 and 2022-23
- A visible dip in monthly volume during the COVID-19 lockdown (early 2020), followed by a sharp recovery — suggesting digital payments became more essential, not less, once restrictions eased
- Average transaction size dropped sharply from 2016-17 to 2017-18 as mass adoption brought in large volumes of small, everyday payments — then stabilized in a ₹120–190 range as UPI matured
- Bank adoption grew steadily (21 → 282 banks), but at a far slower rate than transaction volume — indicating growth was driven primarily by user/merchant adoption rather than infrastructure expansion alone

## 🛠️ Tools & Techniques

- **Power Query** — data cleaning, type correction, row filtering
- **DAX** — explicit measures using SUM, AVERAGE, DIVIDE, CALCULATE, RANKX
- **Data Modeling** — deliberate use of independent tables at different time granularities (monthly vs yearly) rather than forcing a single relationship
- **Visualization** — combo charts (bar + line, dual-axis), line charts, summary tables, KPI cards

## 🔗 Connect

Tadepalli Sai Dedeepya
LinkedIn: linkedin.com/in/tadepalli-sai-dedeepya-a79927393
