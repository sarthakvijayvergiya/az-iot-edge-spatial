Edge Device-- (Virtual Machine)
    Create Virtual Machine GPU
    Drive Installation
    Install IoT Edge runtime
Create computer vision resource


Create IoT Hub
Create IoT Edge Device-- deviceConnectionString

Configure IoT Edge device with VM(Put connection string /etc/iotedge/config.toml)
sudo systemctl restart iotedge

Deployment of Module..


az iot edge set-modules --hub-name "az-ava-hub" --device-id "mySpatialDevice" --content DeploymentSampleManifest.json --subscription "3c68937c-b5af-44f0-800b-41449297f272"


https://www.nvidia.com/content/dam/en-zz/Solutions/Data-Center/tesla-product-literature/Tesla-K80-BoardSpec-07317-001-v05.pdf

https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/

https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/intro-to-spatial-analysis-public-preview

https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/spatial-analysis-container?tabs=virtual-machine

https://github.com/Azure-Samples/cognitive-services-sample-data-files/blob/master/ComputerVision/spatial-analysis/DeploymentManifest.json

https://github.com/Azure-Samples/cognitive-services-spatial-analysis/blob/main/deployment.json

https://github.com/Azure-Samples/cognitive-services-spatial-analysis