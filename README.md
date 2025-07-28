<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <img src = "DTE_Bank_wxO.png"
    	width="auto" height="1200"
         alt = "New Watson Assistant Bank" />

</head>

<script>
  window.watsonAssistantChatOptions = {
    integrationID: "78a2f045-4ca0-4357-8210-4f9123d82a72", // The ID of this integration.
    region: "aws-us-east-1", // The region your integration is hosted in.
    serviceInstanceID: "20240201-1635-4978-90fa-ee7eb719d913", // The ID of your service instance.
    orchestrateUIAgentExtensions: false, // If you wish to enable optional UI Agent extensions.
    onLoad: async (instance) => { await instance.render(); }
  };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>

<body></body>

</html>
