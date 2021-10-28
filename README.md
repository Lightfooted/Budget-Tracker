# Budget-Tracker

  ![badge](https://img.shields.io/badge/License-MIT-informational)

  # Table of Contents

  * [Description](#description)
  * [Deployed Heroku Link](#deployed-heroku-link)
  * [Screenshot](#screenshot)
  * [Usage](#usage)
  * [Built With](#built-with)
  * [License](#license)
  * [Contribution](#contribution)
  * [Questions](#questions)

  ## Description:

  This is a Progressive Web Application (PWA). With the use of service workers, IndexedDB, and the manifest, Budget Tracker allows users to keep track of their expenses without requiring an internet connection. When the user comes back online, their stored offline data will transfer over.
  ## Deployed Heroku Link

  https://agile-scrubland-63874.herokuapp.com/
  ## Screenshot

  ### Empty Form

  ![screenshot](/images/budget-blank.png)
  ### First Online Transaction

  ![screenshot](/images/first-online-transaction.png)
  ### Second Online Transaction

  ![screenshot](/images/second-online-transaction.png)
  ### Dev Tools Network Online

  ![screenshot](/images/networkonline.png)
  ### First Offline Transaction

  ![screenshot](/images/first-offline-transaction.png)
  ### Dev Tools Network offline
  
  ![screenshot](/images/offlinetransaction.png)
  ### Final Transaction With Everything Back Online

  ![screenshot](/images/last-transaction-back-online.png)

  ## Usage

  To use this application, click the provided deployed link and open with Chrome (Firefox works too). While Online, enter the name and the amount of your transaction with the add or subtract buttons. Easy! Now let's try offline mode. In Chrome, right-click and select Inspect to open Dev Tools and select ↑↓ Network Tab. You should see a drop-down list. In Presets select Offline. Refresh the page. The data from online mode should still appear. Now add or subtract a new transaction. Refresh the page and then switch back to Online mode. Refresh again. Offline data should now appear live!
  
  ## Built With

  * Chrome Dev Tools
  * Express
  * Heroku
  * IndexedDB
  * MongoDB
  * Mongoose
  * Node
  ## License

  This project uses the MIT license.
  ## Contribution

  Pull requests 😉
  ## Questions
  
  Have any questions or need further assistance with the project? 
  * Profile: [Lightfooted](http://github.com/Lightfooted)
  * Email: vesselofbalance@hotmail.com