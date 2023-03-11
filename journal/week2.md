# Week 2 — Distributed Tracing

To save ourselves some time we updated our gitpod.yml file so that npm is automatically installed.

![npm-install](assets/gitpod_npm_update.png)

## X-Ray Implementation

Update of requirements.txt file to install xray.

![xray_implementation-Cruddur](assets/requirements_xray_update.png)

I implemented x-ray so that we could see trace logs of activities on our site.  I was able to implement successfully, below screenshot shows traces.

![xray_implementation-Cruddur](assets/xray_traces.png)

I then took it a step further and implemented subsegments.  Here are the screenshots from that implementation.

![xray-subsegment-Cruddur](assets/xray_subsegment.png)
![xray-subsegment-Cruddur](assets/subsegment_traces.png)

## Rollbar
Here are the screenshots from Rollbar implementation and output along with the error we generated.

![rollbar-Cruddur](assets/Rollbar.png)
![rollbar-Cruddur](assets/Rollbar_error.png)



