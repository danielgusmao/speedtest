# SpeedTest

Docker SpeedTest e Alpine Linux

Este Projeto usa o SpeedTest https://github.com/sivel/speedtest-cli no docker com a distribuição Alpine Linux.

Com menos de 80 Megas

# Fazer o pull do container.
    docker pull danielgusmao/speedtest

# Execultar.
    docker run --rm danielgusmao/speedtest

# Menu de ajuda do SpeedTest.      
    docker run --rm danielgusmao/speedtest --help

# Exemplos
    docker run --rm danielgusmao/speedtest --simple

    Ping: 24.464 ms
    Download: 3.64 Mbit/s
    Upload: 6.40 Mbit/s
    
   
    docker run --rm danielgusmao/speedtest --share
    Retrieving speedtest.net configuration...
    Testing from NET Virtua (111.000.222.33)...
    Retrieving speedtest.net server list...
    Selecting best server based on ping...
    Hosted by ITS Telecom (Salvador) [2.23 km]: 17.115 ms
    Testing download speed....................................... Download: 11.09 Mbit/s
    Testing upload speed......................................... Upload: 3.62 Mbit/s
    Share results: http://www.speedtest.net/result/5989705581.png
