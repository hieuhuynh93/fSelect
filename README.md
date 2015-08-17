# fSelect
A jQuery select box replacement library

<img src="http://i.imgur.com/yXOv8DG.png" width="208" height="223" />

### Usage

```javascript
$('.your-select-box').fSelect();
```

### Available options

```javascript
$('.your-select-box').fSelect({
    placeholder: 'Select some options',
    numDisplayed: 3,
    overflowText: '{n} selected',
    searchText: 'Search',
    showSearch: true
});
```

* **placeholder** (str) - the default placeholder text
* **numDisplayed** (int) - the number of values to show before switching to the `overflowText`
* **overflowText** (str) - the text to show after exceeding the `numDisplayed` limit
* **searchText** (str) - the search box placeholder text
* **showSearch** (bool) - show the search box?
