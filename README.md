# RestAPI for Creating QR Codes

For this assignment I want you to go over the videos and I've created a X number of errors in the code that you will have to find and fix them.  You should keep running the tests and read the error and try to understand what it mean.  The purpose of this assignment is to get you accustomed to running the project and following the steps that the program uses to process requests.

Here is my repo with the working code: [https://github.com/kaw393939/fastapi_spring2024](https://github.com/kaw393939/fastapi_spring2024)

You can get this repo working with the install instructions below.  The assignment repo will not work because its filled with broken code.

**To submit this assignment, you should make your own repository and add the remote to git and then push your fixed code to your own repo.** 

## Grading

You will only get 100 if the entire QR program passes GitHub actions, so you will need to update the production.yml file to have your info and setup your environment variables on the repository.

# Instructor Videos
* [Rest API Project Overview](https://youtu.be/xEcBKSSXxhQ)
* [QR Code Overview for Assignment](https://youtu.be/E6b9VkQpQ-U)


## Optional but extremely helpful:

1. [Best Series to Learn Bash Scripting Seriously learn this!!!](https://www.youtube.com/playlist?list=PLIhvC56v63IKioClkSNDjW7iz-6TFvLwS)

2.  [Listen to someone else explain FastAPI and go through a project](https://www.youtube.com/watch?v=cbASjoZZGIw)

# Install
1. Clone
2. Make virtual environment:  python3 -m venv venv
3. Activate virtual environment: source venv/bin/activate
4. Install requirements: pip install -r requirements.txt
5. **IMPORTANT** run: mkdir qr_codes to create a qr codes directory to save in, permissions will be messed up and the docker container won't be able to write to the qr_codes directory if you don't.
6. Note: make sure docker is started
7. run pytest locally to check that it works locally
8. Start the app with docker compose up --build
9. Goto http://localhost/docs to view openapi spec documentation
10. Click "authorize" input username: admin password: secret
11. Test making,  retrieving, and deleting QR codes on the spec page.



# Screenshot

![Screenshot 2024-07-23 232317](https://github.com/user-attachments/assets/b8412fe7-e980-4425-90cc-17899305e9ee)

![Screenshot 2024-07-23 232244](https://github.com/user-attachments/assets/b99a7c05-0287-42be-aeb3-40660455d4cf)

![Screenshot (187)](https://github.com/user-attachments/assets/6fe10be0-1f69-4e67-9adb-96955629f711)

![Screenshot (188)](https://github.com/user-attachments/assets/47e77afe-6181-4ace-bbdf-80140626db06)

![Screenshot (189)](https://github.com/user-attachments/assets/7f0003a0-15dc-4511-a52f-8e08addf6ddc)

![Screenshot (190)](https://github.com/user-attachments/assets/505ed034-17d0-414d-a870-b693b0bbddd9)

![Screenshot (191)](https://github.com/user-attachments/assets/72d9ffe4-16c6-4181-8a82-6685e07474ff)

![aHR0cHM6Ly9naXRodWIuY29tL2NoYWl0YW55YS1rdW1hcjMz](https://github.com/user-attachments/assets/c2d80eb6-74f1-407f-83fc-bc0c789efbf7)







