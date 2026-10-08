# Park Allgäu 2027

Family trip site for Center Parcs Park Allgäu, 23–30 April 2027.

Everything is in `index.html`. To add a flight option, add an entry to the `FLIGHTS` list near the bottom of the file:

```js
{ airline: "Swiss", outbound: "07:10 → 10:45", return: "16:30 → 21:55", stops: 0, price: 1850, checked: "2026-10-08", source: "Google Flights", link: "https://…", notes: "" }
```

`price` is the total for the family; `stops` is 0 for a direct flight.
