# calendar
A web calendar application made for practice purposes.
          
<img src="https://github.com/ShaviyaVictor/calendar/blob/main/assets/images/calendar.png" width="700" height="350" alt="">             

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)        
* [CSS](https://developer.mozilla.org/en-US/docs/Web/css)             
* [Bootstrap](https://getbootstrap.com/docs/5.2/getting-started/introduction/)         
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)              
* [Github](https://github.com/ShaviyaVictor/shaviya)

This plugin uses pure javascript. No library is required.


## Installation

You can get the widget using the following methods:
- From the [GitHub repository](https://github.com/year-calendar/js-year-calendar/releases)
- From the Node package manager, using the following command: `npm install js-year-calendar`
- From Yarn, using the following command: `yarn add js-year-calendar`
- From the **CDN**, by adding the following script directly in your HTML page
- - just before closing the body tag:

```<script src="https://unpkg.com/js-year-calendar@latest/dist/js-year-calendar.min.js"></script>```

AND
- - just before the custom styles link tag in the header:

```<link rel="stylesheet" type="text/css" href="https://unpkg.com/js-year-calendar@latest/dist/js-year-calendar.min.css" />```

## Usage

You can create a calendar using the following javascript code :
```
new Calendar('.calendar')
```

Or

```
new Calendar(document.querySelector('.calendar'));
```

Where `.calendar` is the selector of a `DIV` element that should contain your calendar.

You can also use the following HTML if you don't want to use javascript to initialize the calendar
```
<div data-provide="calendar"></div>
```
The calendar will be automatically created when the page will finish loading

## Using options

You can specify options to customize the calendar:
```
new Calendar('.calendar', {
    style: 'background',
    minDate: new Date()
})
```

You can find the exhaustive list of options in the [documentation](https://year-calendar.github.io/js-year-calendar/documentation).

## License

This project is licensed under the [Apache License 2.0](https://github.com/ShaviyaVictor/calendar/blob/main/LICENSE).           

## Resources
- [YouTube](https://www.youtube.com/watch?v=hdnt-jdDlao)                  


## Acknowledgments

* @shaviyavictor

### Author

* **Victor Shaviya**        
  - [BioLink](https://bio.link/shaviya)       
  - [LinkedIn](https://www.linkedin.com/in/ShaviyaVictor/)          
  - [Instagram](https://www.instagram.com/shaviyavictor/)        
  
  
**© Victor Shaviya**, Project Guide Template.