# Sri Lanka Income Tax Calculator

A simple, responsive, and user-friendly web-based calculator designed to estimate Personal Income Tax (PAYE/APIT) for residents of Sri Lanka, based on the tax rates effective from **April 1st, 2025**.

## ✨ Features

* **Real-time Calculation:** Get instant tax estimations as you type your monthly income.
* **Progressive Tax System:** Accurately calculates tax based on Sri Lanka's progressive income tax slabs.
* **Detailed Breakdown:** Provides a clear table showing how your income is taxed across different brackets.
* **Monthly & Annual View:** Displays both monthly and annual income and tax amounts.
* **Simple Interface:** Clean and intuitive design for ease of use.
* **Responsive Design:** Works well on various screen sizes (desktops, tablets, mobile phones).

## 🚀 How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/sri-lanka-tax-calculator.git](https://github.com/your-username/sri-lanka-tax-calculator.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd sri-lanka-tax-calculator
    ```
3.  **Open `index.html`:** Simply open the `index.html` file in your web browser.

    Alternatively, you can just download the `index.html` file and open it directly.

4.  **Enter your Monthly Income (LKR):** Type your gross monthly income into the designated input field.
5.  **View Results:** The calculator will automatically update to show your Monthly Income, Annual Income, Monthly Tax, and Annual Tax.
6.  **Review Tax Breakdown:** The table below the results will detail how your income falls into each tax slab and the tax amount for each.
7.  **Reset:** Click the "Reset Calculator" button to clear all fields and start over.

## 📊 Tax Slabs (Effective from 01.04.2025 - Monthly Income)

| Monthly Income (LKR) | Tax Rate | Tax Applied |
| :------------------- | :------- | :---------- |
| 0 – 150,000          | 0%       | Relief      |
| 150,001 – 233,333    | 6%       | (Income - 150,000) * 6% |
| 233,334 – 333,333    | 12%      | (Income - 233,333) * 12% + Tax from previous slabs |
| 333,334 – 433,333    | 18%      | (Income - 333,333) * 18% + Tax from previous slabs |
| 433,334 – 533,333    | 24%      | (Income - 433,333) * 24% + Tax from previous slabs |
| 533,334 – 633,333    | 30%      | (Income - 533,333) * 30% + Tax from previous slabs |
| Above 633,333        | 36%      | (Income - 633,333) * 36% + Tax from previous slabs |

*This calculator provides an estimation based on the provided tax rates and should not be considered legal or financial advice. Always consult with a qualified professional for precise tax planning.*

## 🛠️ Technologies Used

* **HTML5:** For the page structure.
* **CSS3:** For styling and responsiveness.
* **JavaScript (ES6+):** For the tax calculation logic and dynamic content updates.

## 🤝 Credits

Developed by [TechSeed Lanka (Pvt)Ltd.](https://www.techseed.lk)
