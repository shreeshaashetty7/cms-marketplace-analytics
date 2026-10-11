# 2026 CMS Marketplace Executive Analytics

An executive-level analytics dashboard processing the **2026 OEP Enrollment** and **QHP Landscape** datasets to deliver actionable insights across federal and state exchange platforms.

---

## 🚀 Deliverables & Architecture

* **Data Processing & Modeling:** Python data pipelines and DAX measures (`Market Share %`, `Total Selections`, `Average Premium`).
* **Visual Presentation:** Executive "Light & Navy" theme in Power BI with high-contrast typography, bold headers, container-style visuals (`8px` rounded borders), and custom data labeling.
* **Dashboard File:** `dashboard/cms_marketplace_dashboard.pbix`

---

## 📊 Dashboard Visual Components

| Visual Component | Chart Type | Key Metrics & Dimensions | Business Insight |
| :--- | :--- | :--- | :--- |
| **KPI Card 1** | Single Value Card | `Total Selections` (138M) | Total market volume across selected states. |
| **KPI Card 2** | Single Value Card | `Average Premium` ($555.97) | Overall market benchmark for monthly plan costs. |
| **Metal Share** | Clustered Bar Chart | `Market Share %` by `Metal Level` | Displays Silver (~42.87%) and Bronze (~39.85%) tier dominance. |
| **Metal Pricing** | Clustered Column Chart | `Average Premium` by `Metal Level` | Tracks cost scaling across Gold, Silver, and Bronze tiers. |
| **Platform Distribution** | Donut Chart | `Enrollment Volume` by `Platform` | Contrasts Federal Exchange (`HC.gov`) vs State-Based (`SBE`) volume. |
| **State Price Ranks** | Horizontal Bar Chart | `Average Premium` by `State` | Ranks regional pricing variance across participating states. |
| **Global Filter** | Dropdown Slicer | `Select State` | Enables dynamic state-by-state slice-and-dice across all visuals. |

---

## 🛠️ Version Control & Workflow

```bash
git add dashboard/cms_marketplace_dashboard.pbix README.md
git commit -m "feat(powerbi): finalized executive dashboard layout, navy theme, and documentation"
git push
