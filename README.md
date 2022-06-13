# Guani 🚀🚀🚀
Guani is the name of the chatbot that will help you book a hotel room in the Hostel Kasa Guane.

## Introduction 🤓
Kasa Guane is a hostel in Bucaramanga, Colombia, with more than ten years of experience. The hotel receives people worldwide and is famous for its excellent services and products.
Talking with the hostel owner, they receive more than 30 calls per day trying to book a room; some of the calls are just asking the price and what services they have. However, other calls are trying to book a hotel in the prestigious hostel.

## Installation 🛠️
Install libraries necessary for the project with requirements
```
pip install virtualenv
virtualenv env -p python3.8
source env/bin/activate
pip install -r requirements.txt
```

Ir install libraries necessary for the project with requirements
```
pip install virtualenv
virtualenv env -p python3.8
source env/bin/activate
pip install rasa==2.6.2
pip install rasa-x==0.40.0 --extra-index-url https://pypi.rasa.com/simple
pip install sanic-jwt==1.6.0
```

## Run 🖥
Run this command to start the app. 
```bash
rasa x
```


## Architecture 🚀
The architecture is based on a question and answer chatbot (Q&A)
The chatbot will be focused on answering questions and saving the information in the booking process.

_These instructions will allow you to know which services are used to deploy the entire application._

Check **Deployment** to know how to deploy the project.

<div align="center">
       <img src="images/gauni_bot.png?raw=true" width="400px"</img> 
</div>


## Deploy 📦

We deploy the chatbot locally and
generate a URL that the user can test,
and we created a channel with
NGROK to try the chatbot for three
days; the steps will be in the
finalization phase.


--------

## Built with 🛠️
_Mention the tools you used to create your project_

* [RASA](https://rasa.com/) - Rasa is the only serious solution for mission-critical conversational AI


## Video 📖
[![ScreenShot](images/video_rasa.png?raw=true)](https://youtu.be/uxx6M1v9fFI)

## Versions 📌
We use [SemVer](http://semver.org/) for versioning. For all available versions, see what[tags in this repository](https://github.com/tu/proyecto/tags).

## Authors ✒️
* **Adonai Vera** - *Member DS4a* - [AdonaiVera](https://github.com/AdonaiVera)


## License 📄

This project is under the License, see the file [LICENSE.md](LICENSE.md) more details.

## Expressions of Gratitude 🎁

* Tell others about this project 📢
* Give thanks publicly 🤓.
* Say Thanks to our Mentor and tutor Tim Schlippe.


---
