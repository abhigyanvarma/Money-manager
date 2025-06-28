
# MONEY MANAGER APP
A simple and beautiful React-based money management app to track your **income**, **expenses**, and overall **financial balance**. Featuring dynamic charts, transaction history, dark mode, and downloadable data.


## FEATURES

-  Add Income or Expense transactions
-  View real-time balance, income & expense summaries
-  History table with delete option
-  Light & Dark mode toggle
-  Persistent data using `localStorage`
-  Download transaction history in table format
-  Responsive UI with Tailwind CSS

---



### PREREQUISITES

- Node.js and npm installed

### INSTALLATION 
```bash
git clone https://github.com/your-username/money-manager.git
cd money-manager
npm install
npm run dev
````

Open your browser at [http://localhost:5173](http://localhost:5173)

---

## 🧱 Project Structure

```
money-manager/
├── public/
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── OverviewCards.jsx
│   │   ├── AddTransaction.jsx
│   │   ├── TransactionList.jsx
│   │   └── TransactionHistory.jsx
│   ├── App.jsx
│   └── index.css
├── package.json
└── README.md
```


---

## TECHNOLOGIES USED

* React
* Tailwind CSS
* Vite
* JavaScript
* localStorage

---

## DEPLOYMENT

You can deploy this app using:

* [Vercel](https://vercel.com/)
* [Netlify](https://www.netlify.com/)


---

##  AUTHOR

**Abhigyan Varma Chiluvuri**

* GitHub: (https://github.com/abhigyanvarma)
* Email: (abhigyanvarmachiluvuri@gmail.com)



# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
