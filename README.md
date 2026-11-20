# mse2_202401100100290

I fixed the indentation because YAML uses indentation to show which settings belong under each key.
I changed port to ports because Compose uses ports to publish container ports.
I changed index.htm to index.html because that is the actual web page filename.
I changed 8080 to 80 because nginx receives website requests on port 80 inside the container.