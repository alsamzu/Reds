# QUICK FIXES FORTHE PROJECT

##1.  Scrolling cards

- Use the class **.section-scroll,  .d-flex, .flex-row, .flex-nowrap** (PLEASE NOTE: They are already provided by BootStrap)
 
 
 #### STEP 1:
- PLEASE NOTE: .section-scroll is a custom class which has
  
  
  ```css
    .section-scroll {
        overflow-x: scroll;
    }
    ```
 - This is what we have replaced so that we remove from the ID reference so that it is more reusable as a Class
        
```css
        #cards {
            overflow-x: scroll;
         }
           ```
#### STEP 2:
 Then make sure to include the below code to remove the scroll bars

```css    
     ::-webkit-scrollbar {
        display: none;
    }
    ```
    