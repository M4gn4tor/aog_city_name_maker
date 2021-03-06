# aog_city_name_maker
<h1>
Google Actions Getting Started Project
</h1>
This project has been created for developers, interested to getting started with Google Actions using Dialogflow and Google Actions Console.
<h2>
Instructions to use the repo
</h2>
<p><br>
  1. Users can download the source code as zip from <a href="https://github.com/chefgs/aog_city_name_maker/archive/master.zip">here</a><br>
  or <br> 
  Install <a href="https://git-scm.com/downloads">Git Bash for Windows</a> and use below commands to checkout code<br>
2. Use git command to checkout the code<br>
git clone https://github.com/chefgs/aog_city_name_maker.git<br>
cd aog_city_name_maker<br>
git checkout master<br>
</p>
<h2>
Source file details
</h2>
<p>
agent.json - Dialog flow agent file<br>
package.json - Agent version file<br>
"entities" Directory - contains the Diagflow entity used in the agent<br>
"intent" Directory - contains the Default intents and custom intents made for the Google actions conversations<br>
"fulfillment_webhook" Directory - contains the node.js source files. These files can be used to create the Fulfillment webhook for the agent.
These webhooks are written in node.js, uses "Google Cloud functions" deployed in Google Firebase.<br>
</p>
<h2>
  Tutorials and Guides
</h2>
<p>
Google Actions Getting Started<br>
https://developers.google.com/actions/smarthome/<br>

Google Actions create actions<br>
https://codelabs.developers.google.com/codelabs/actions-1/#0<br>

Dialogflow Console Getting Started<br>
https://dialogflow.com/docs/getting-started<br>

Dialogflow Agents<br>
https://dialogflow.com/docs/agents<br>

Dialogflow Fullfillment for Google Actions<br>
https://dialogflow.com/docs/getting-started/integrate-services-actions-on-google<br>
Use source files available in "fulfillment_webhook" Directory
</p>


<h2>
  Quick start tips
</h2>
<p>
  Developers who has experience in Dialoagflow can download the "aog_city_name_maker.zip" file.<br>
  Create an agent with the preferred name.<br>
  Export the aog_city_name_maker.zip file as instant agent from "Dialoagflow agent settings".<br>
  Once the agent is created fullfilment webhook can be enabled and use the files available in "fulfillment_webhook" Directory to add firebase code.<br>
  </p>
