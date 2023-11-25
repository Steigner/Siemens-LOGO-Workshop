FROM nodered/node-red

RUN npm install node-red-contrib-s7
RUN npm install node-red-dashboard

# ! Important ! if you want load flow from dockerfile but
# you cannot have shared volumes

COPY flow.json /data/flows.json