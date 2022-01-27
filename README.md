# Tor for Windows

This is Tor expert bundle for windows

<br/>

## Port numbers

This repository is a configured Tor binaries without any browser. Just a socks v5 proxy on port `9050` (default tor port).

<br/>

## Installation

Download zip file from releases and extract it to `C:\Program Files (x86)\` .You can add this directory to windows path to access it via command line.

<details>
<summary>Click here to view in details</summary>

![](images/installation-directory.png)

</details>
<br/>

## Tor cache directory

Its default path: `%APPDATA%\tor` .

<br/>

## How to use

-   Start Tor:

    -   Manual start:

        Run `tor.vbs` (just double click on it :D ).

    -   Run on windows startup:

        to start Tor on windows startup, put a shortcut of `tor-bg.vbs` into windows startup folder:

        -   system wide:

            ```
            C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp
            ```

        -   user:

            ```
            %APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup
            ```

-   Use it in browser:

    Install `Proxy SwitchyOmega` in [chrome](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif) or [firefox](https://addons.mozilla.org/en-GB/firefox/addon/switchyomega/) to use tor proxy.

    <details>
    <summary>Click here to view in details</summary>

    ![](images/SwitchyOmega-1.png)

    ![](images/SwitchyOmega-2.png)

    ![](images/SwitchyOmega-3.png)

    ![](images/SwitchyOmega-4.png)

    ![](images/SwitchyOmega-5.png)
    </details>

<br/>

## Compatibility

Tested on windows 10 x64 21h2
