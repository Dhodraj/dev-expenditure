# dev-expenditure

Track income and expenses in the browser. Add a transaction, watch the balance change, and see income against expense in a pie chart.

Built in 2021. Live at [devexpenditure.web.app](https://devexpenditure.web.app/).

It is a React app. State lives in a Context with a reducer. The chart uses `@ant-design/charts`, the UI uses Material UI, and react-toastify shows the notices. There is no back end, so transactions clear when you reload the page. Only the totals for the chart are kept in localStorage.

## Run it

```bash
npm install
npm start
```
