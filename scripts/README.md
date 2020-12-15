# Distributed Scripts Usage
### Agent Package
```bash
#install agent script via wget
#the script file format <revision>.<os arch>.txt. E.g. v1.1beta.linux64.txt
source <(wget -O - https://raw.githubusercontent.com/EC-Release/sdk/disty/scripts/agt/v1beta.linux64.txt)

#install a latest agent release script via wget
source <(wget -O - https://raw.githubusercontent.com/EC-Release/sdk/disty/scripts/agt/v1.2.linux64.txt)

#install agent script in MacOS
bash <(curl -k https://raw.githubusercontent.com/EC-Release/sdk/disty/scripts/agt/v1.2.darwin.txt)

```
### Cipher Usage
to be continue

### Plugin package
following the same format from the agent package
```bash
#install tls package
source <(wget -O - https://raw.githubusercontent.com/EC-Release/sdk/disty/scripts/plg/tls/v1.linux64.txt)
#vln package
source <(wget -O - https://raw.githubusercontent.com/EC-Release/sdk/disty/scripts/plg/vln/v1.linux64.txt)
```