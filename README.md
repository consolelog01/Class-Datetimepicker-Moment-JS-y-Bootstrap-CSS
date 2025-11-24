For get elements of the calendar "Datetimepicker" MomentJS 

-------------------------------------------------------------------------------------------------------------------

*** Class for get days checked:

  > .bootstrap-datetimepicker-widget ul.list-unstyled li.show div.datepicker div.datepicker-days table tbody tr 

      •  Children:

          ▲ td.day.old.disabled
          ▲ td.day.old.disabled
          ▲ td.day
          ▲ td.day.active
          ▲ td.day.weekend
          ▲ td.day.disabled.weekend

> Example:     

  ```javascript
  
    setTimeout(() => { 
      console.log($(".bootstrap-datetimepicker-widget ul.list-unstyled li.show div.datepicker div.datepicker-days table tbody tr")) 
      }, 5000
    )

<p>
  <img src="https://github.com/consolelog01/Class-Datetimepicker-Moment-JS-y-Bootstrap-CSS/blob/585afd3818f3a4167aa33b88f0bf2db2eb40a1ee/datetimepicker_filter_days.png">
</p>
