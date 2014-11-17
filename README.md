This repository include sone useful file: fig.yml

This file is to be used by the Fig (http://fig.sh) which orchestrates Docker container startup.

From OS X this can be installed from Brew:
    ```
    $ brew install fig
    ```

Or on Linux (or if you prefer pip):
    ```
    $ pip install fig
    ```

The 'hyperchannel' and 'sockethub' repositories are expected to be checked out and ran from sibling directories.

Usage of this is like so:

    ```
    $ mkdir 67p
    $ cd 67p

    $ git clone https://github.com/67p/hyperchannel
    $ git clone https://github.com/sockethub/sockethub

    $ git clone https://github.com/67p/orchestration
    $ cd orchestration
    $ fig up
    ```

Afterwards, you can access hyperchannel at http://localhost:4200/ or sockethub examples at http://localhost:10550/
