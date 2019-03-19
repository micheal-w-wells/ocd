#openshift CLI dude 

#launch image, get newest version of sdk and sample bot:

docker run -it -u 0 a8fd5c530c44 --entrypoint /bin/bash 'npm install @rocket.chat/sdk --save && git clone https://github.com/micheal-w-wells/ocd.git && node bot.js'

