1. ## Termux 3.10 Version commands
```shell
termux-setup-storage
```
```shell
pkg update && upgrade
```
```shell
pkg install tur-repo
```
```shell
pkg install python-is-python3.10
```
```shell
pkg install -y rust binutils
```
```shell
CARGO_BUILD_TARGET="$(rustc -Vv | grep "host" | awk '{print $2}')" pip install maturin
```
```shell
pkg install git
```
```shell
pkg install nano
```
```shell
pkg install node
```

## Zain Arain 

## Zain Arain 

## Termux

1. Make sure your device has Python and Git installed.

    Recommendation: Use Python version 3.8+ (3.10)
   
   Python

2. Clone this repository.
   ```shell
   git clone https://github.com/zainarain279/blumauto-main.git
   ```

3. Enter the BlumTod folder
   ```
   cd blumauto-main
   ```

4. Install the required modules/libraries.
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit the `data.txt` file, enter your query data into the `data.txt` file. You can get your query by following [How to Get the Query](#how-to-get-the-query). One line for 1 account, if you want to add a 2nd account, fill it in on a new line.
```shell
nano data.txt
```
6. Run the program/script.
   ```
   python bot-zain.py
   ```
```shell
python bot-main.py
```
## Zain Arain 
