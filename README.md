# GeoHaqq

GEO location monitoring for Haqq validator
This location monitoring allows you to determine the decentralization of the blockchain and / or indicate its absence, statistics are compiled on validators: providers, cities and countries, and a map of validators is also built


sudo apt update && sudo apt upgrade -y && sudo apt autoremove -y && sudo apt install screen bash git curl jq awk -y


Specify the path to the addrbook file
By default, we will search for network peers in a specialized file at: $HOME/.haqqd/config/addrbook.json

Run service


cd $HOME && rm -rf Haqq-Network && git clone https://github.com/OnThePluto/Haqq-Network.git && cd Haqq-Network/Monitoring/Geolocation && chmod +x run.sh && bash run.sh


Country & city statistic

<img width="924" alt="country_statistic" src="https://user-images.githubusercontent.com/45524333/195981630-d4c47574-b51c-4d58-b919-06e93b906390.png">

Provider statistic

<img width="851" alt="provider_statistic" src="https://user-images.githubusercontent.com/45524333/195981649-503761d7-6feb-4985-999f-5d8ec7546dc1.png">

Map (in format: .svg)

![map](https://user-images.githubusercontent.com/45524333/195981662-83e914be-53d6-4999-a21d-978e89596854.svg)
