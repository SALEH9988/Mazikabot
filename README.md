from pyrogram import Client

app = Client("my_account")

with app:
    app.send_message("me", "Hi!")
