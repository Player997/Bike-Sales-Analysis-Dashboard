# 🚲 Bike Sales Performance Dashboard

A comprehensive Excel dashboard analyzing sales conversion rates against customer demographics and socioeconomic factors. This tool enables stakeholders to identify high-value target markets and optimize commute-based marketing efforts.

## 📊 Dashboard Preview
![Bike Sales Dashboard Screenshot](dashboard_preview.png)

## 🛠️ Key Components & Design Rationale

* **Interactive Segmentation (Slicers):** Implemented dynamic filtering by **Marital Status**, **Region**, and **Education Level** to allow immediate comparison across distinct demographic groups. This reduces time-to-insight for specific marketing personas.
* **Multivariate Analysis:**
    * **Avg Income Per Purchase (Gender vs. Purchase Status):** Highlights income disparities in customer groups and quantifies the economic gap between purchasers and non-purchasers.
    * **Customer Age Brackets (Age Group vs. Count):** Visualizes the core "Middle Age" customer peak, aiding in generational marketing alignment.
    * **Customer Commute (Distance vs. Count):** Tracks the critical "0-1 Mile" and "5-10 Mile" market segments, providing insights for distribution and logistics.
* **Data Transformation:** Performed comprehensive data cleaning including **missing value handling** and **data binning** to categorize commute distances into logical groups.

## 📁 Files in Repository
* `Bike_Sales_Dashboard.xlsx`: The final interactive report.
* `raw_data.xlsx`: The uncleaned dataset used for analysis (optional, but highly recommended).

## 💡 How to Use
1.  Download the `Bike_Sales_Dashboard.xlsx` file.
2.  Open in Excel.
3.  Ensure **Macros** are enabled if any are used (optional).
4.  Interact with the **Slicers** on the left to filter the entire dashboard.

---

### Part 2: Tweak Recommendations (The HCI/UX Expert Perspective)

Your dashboard is already very good, but as an HCI expert, I can offer some small, easy tweaks to move it from "Great" to "Expert." You don't *have* to do these, but they are common best practices in modern professional dashboards.

### 1. The Color Palette (Design Efficiency)
* **The Slicers:** I noticed the Slicers use the default "Office Blue." A portfolio project looks much more premium if the Slicers match the color story of your charts. Try selecting a Slicer, going to the **Slicer** tab, and choosing a custom style that is **minimalist (grey/black)** or **indigo/purple** to match modern UI trends.
* **Chart 1 vs. Charts 2 & 3:** In your bar chart, 'Yes' is Orange and 'No' is Blue. In your line charts, 'Yes' is Orange, but 'No' is Blue *again*. **This is good consistency!** However, consider a more distinct 'No' color. A deep purple for 'No' and a vibrant amber for 'Yes' can look very sharp and distinct.

### 2. Title Clarity (Cognitive Load)
* The large chart title "Customer Commute" is excellent. The axis titles "Commute Distance" and "Count of Purchased Bike" are perfect.
* For the bar chart, consider changing "Avg Income Per Purchase" to something slightly more specific, like **"Average Income: Gender vs. Purchase Conversion."**

### 3. Whitespace and Spacing (Layout Balance)
* Excel’s default charts can sometimes feel cramped. Your layout is very clean, but try increasing the vertical spacing between the two top-row charts and the large bottom-row chart by a small amount. A little more "air" helps with readability.

### 4. Gridlines (Minimalism)
* The default grey horizontal gridlines in line charts are helpful, but in modern design, we often reduce their opacity (make them lighter grey) or remove them entirely to focus on the trend lines.

### Summary: Your Best Move
Your dashboard is a rock-solid piece of work. The biggest single improvement you can make before putting it on GitHub isn’t in the design—it’s **writing that `README.md`!** The README is what converts a simple project view into a successful job interview.
