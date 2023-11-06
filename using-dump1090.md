# Using dump1090

Refer to https://github.com/antirez/dump1090 for the original instructions

Clone the code:
```console
git clone https://github.com/antirez/dump1090.git && cd dump1090
```

Install required packages:
```console
sudo apt update && sudo apt install librtlsdr-dev -y
```

Build the code:
```console
make
```

Run the code:
```console
./dump1090 --net
```