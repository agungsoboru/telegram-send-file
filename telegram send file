import requests

bot_token = ''
chat_id = ''

#myfilepath = "file path"
#with open(myfilepath, 'rb') as myfile:
#    file = {'document': myfile}
#    requests.post ("https://api.telegram.org/bot" + awdawdawdawdawdawdwadTuk + "/sendDocument?chat_id=" + 2312312321312312 ,files=file)




#with open('fping.txt') as f:
#    line = f.readline()
#    while line:
#        line = f.readline()
#        print(line)
#with open('fping.txt') as f:
#    line = f.readline()
#    while line:
#        line = f.readline()
#       message = line
#requests.post("https://api.telegram.org/bot" + bot_token +"/sendMessage?chat_id=" + chat_id +"&text=" + message)

myfilepath = "/home/user/fping.txt"
with open(myfilepath, 'rb') as myfile:
    file = {'document': myfile}
    requests.post("https://api.telegram.org/bot" + bot_token +"/sendDocument?chat_id=" + chat_id ,files=file)
