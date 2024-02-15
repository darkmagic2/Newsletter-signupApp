public api
edit this part in the app.js with correspoding listid and apikey from mail chimp

  const jsonData = JSON.stringify(data);
  const url = "https:us18.api.mailchimp.com/3.0/lists/listidhere"
  const options = {
    method:"POST",
    auth: "apikeyhere"
  }

  
