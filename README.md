# slack-file-bot


## TO RUN/BUILD APP

 ```sh
 To Build the app:  go build
 To run the application : go run main.go
 ```
 On running the app you'll get the file uploaded in channel<br/>
![image](https://user-images.githubusercontent.com/19289251/160979221-d6c7ef2e-699b-4b01-918c-5026689f8c87.png)

 ## Technical Dependencies:

* Using godotenv for getting .env configs<br/>
* Using slack-go for connecting and uploading files <br/>
* To install godotenv:  go get github.com/joho/godotenv<br/>
* To install slack-go : go get "github.com/slack-go/slack"<br/>
* The application requires slack SLACK_BOT_TOKEN & CHANNEL_ID in the .env file, so create the .env file on root
* To get those credentials you'll need a slack account with a work space and you'll need to be the admin of that workspace
* Create a bot from scratch, give the nessecery permissions, enable socket mode and install the bot to workspace
* You'll then recive the bot token from oath and permisions when you install to workspace
* You can find the channel if you select open channel details on right click of channel and its to the extreme end
* Add the files you want to upload in root folder and mention the file names in fileArr
