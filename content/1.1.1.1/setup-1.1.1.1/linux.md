---
title: Linux
pcx-content-type: how-to
weight: 0
meta:
  title: Set up 1.1.1.1 - Linux
---

# Set up 1.1.1.1 - Linux

Take note of any DNS addresses you might have set up, and save them in a safe place in case you need to use them later.

## Ubuntu

1.  Go to **Show Applications** > **Settings** > **Network**.

2.  Select the adapter you want to configure - like your Ethernet adapter or Wi-Fi card - and click the **settings** button.

3.  Click the **IPv4** tab.

4.  In the **DNS** section, disable the **Automatic** toggle.

5.  Change the DNS servers to:

    ```txt
    1.1.1.1
    1.0.0.1
    ```

6.  Click the **IPv6** tab.

7.  In the **DNS** section, disable the **Automatic** toggle.

8.  Change the DNS servers to:

    ```txt
    2606:4700:4700::1111
    2606:4700:4700::1001
    ```

9.  Click **Apply**.

10. Visit [1.1.1.1/help](https://1.1.1.1/help) to make sure your system is connected to 1.1.1.1.

{{<render file="_captive-portals.md">}}
