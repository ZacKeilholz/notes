* Monday 4/16 - Data Persistance Locally in Browser
** TODO get code from Jake
** TODO Read up/download Postman

** Saving data on refresh
*** Use Client Side Because:
    1. Cost
    2. Performance
    3. --

** Modern Day Browser Tech:
    1. Cookies- original way sites made data available to servers (most complicated- very long string)
    2. Local Storage- Similar to JS object stored by browser (city stored by browser)- Not Shared with server
    3. Session Storage- Variant of local storage- it's more private... also ONLY used in current browser session. Example- online banking.  

** Using Local Storage
    1. Inspectable in Chrome Dev Tools >>>  Application > Storage > Local Storage > File://
    2. Stores Values/Keys
    3. localStorage.clear();   //A built-in browser method.  Clears any data you've saved for this specific webpage
    4. localStoragesetItem("name",username);
    5. $("Target").text(localStorage.getItem("name"));
    



