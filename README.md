
   - When the user clicks on the `#submit_button` Button:
     - If the user has any field left blank, send an `alert()` informing the user to “Please fill in all fields”
     - If the user has all fields filled out:
       - Parse the inputs into the following “Ad Lib” text, putting the corresponding inputs in the appropriate spots: “Last night I ate a {`#noun`}, and today I just had to {`#verb`}. What a {`#adjective`} day!”
       - Hide the `.form_container`
       - Populate `#story_result` with the finalized text
     - *Tip: Remember to [`.preventDefault()`](https://developer.mozilla.org/en-US/docs/Web/API/Event/preventDefault) or else the button will attempt to submit the form, refreshing the page*
