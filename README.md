# speedtest

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
