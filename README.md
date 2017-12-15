* Create new folder
* express --pug
* npm install mongoose --save
* npm install dotenv --save {you can check this and mongoose by looking into package.json}
* put darksky api key into the .env folder {that is in the top level folder of your project}
* npm install request --save
* go put the api key in your .env folder :) 


## To push to Heroku
* git init
* git add .
* git commit -m "First commit"
* heroku create
* git remote -v 
        * Make sure it has a name
* git push heroku master       


## Info for angular
* weatherCtrl.$inject = ['$scope', 'SelectedData', 'DarkskyWeather'];
  * selected data stays the same for ours --> found them in app_client/common/services
  *  must have services in app
  *  NEED SELECTEDDATA STUFF IF GOING TO CLICK AND SELECT!!!!
  *  the first is what the method is known as externally and the second is internally when it says
    * .service('DarkskyWeather', 'darkskyWeather'); <-- in the darkskyWeather.service.json
  *  selectedData.factory.js --> can change selectedDepartureICAO to what I need such as selectedTribe or selectedContestant
  *  The order of things in the index.html MATTERS!!!! 
  *inject means use these things in this order
  * what you call controller as 'vm' must put var vm = this; in the weather.controller.js
  * KEEP THE SELECTED DATA STUFF
            
## If weather is finished by Monday we don't have to do attendance ... take out departure and arrival NO EXTRAAA STUFF
    * make sure final project doesn't look anything like airplane app thingy ma bobber deal hicky!
    * 
    * 
    * 
Need part from 215 to 219 and put in controller so you can get position