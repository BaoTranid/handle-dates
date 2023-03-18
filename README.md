<h1 align='center'>Functions that handle dates</h1>

Synthesis of functions to handle date time or calendar

## **The start and end date of a month**
![The start and end date of a month](https://github.com/BaoTranid/handle-dates/blob/master/images/the-start-and-end-date-of-a-month.svg?raw=true)
```
const startOfMonth = moment().startOf('month').format('YYYY-MM-DD hh:mm');
const endOfMonth = moment().endOf('month').format('YYYY-MM-DD hh:mm');
const startOfCalendar = moment(startOfMonth ).startOf('week').format('YYYY-MM-DD hh:mm');
const endOfCalendar = moment(endOfMonth).endOf('week').format('YYYY-MM-DD hh:mm');
```
> Use moment() format library