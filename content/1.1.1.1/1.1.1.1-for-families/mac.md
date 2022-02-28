---
title: macOS
pcx-content-type: how-to
weight: 0
meta:
  title: Set up 1.1.1.1 for Families - macOS
---

# Set up 1.1.1.1 for Families - macOS

Follow these steps to configure 1.1.1.1 for Families:

## Block malware

### IPv4

1.  Go to **System Preferences**. You can find it by pressing <kbd>Command</kbd> + <kbd>Space</kbd> on your keyboard and typing `System Preferences`.

2.  Click **Network** > **Advanced**.

3.  Select the **DNS** tab. Take note of any DNS addresses you might have and save them in a safe place in case you need to use them later.

4.  Remove any DNS addresses that may be already listed and replaced them with:

    ```txt
    1.1.1.2
    1.0.0.2
    ```

5.  Click **OK** > **Apply**.

### IPv6

1.  Go to **System Preferences**. You can find it by pressing <kbd>Command</kbd> + <kbd>Space</kbd> on your keyboard and typing `System Preferences`.

2.  Click **Network** > **Advanced**.

3.  Select the **DNS** tab. Take note of any DNS addresses you might have and save them in a safe place in case you need to use them later.

4.  Remove any DNS addresses that may be already listed and replace them with:

    ```txt
    2606:4700:4700::1112
    2606:4700:4700::1002
    ```

5.  Click **OK** > **Apply**.

## Block malware and adult content

### IPv4

1.  Go to **System Preferences**. You can find it by pressing <kbd>Command</kbd> + <kbd>Space</kbd> on your keyboard and typing `System Preferences`.

2.  Click **Network** > **Advanced**.

3.  Select the **DNS** tab. Take note of any DNS addresses you might have and save them in a safe place in case you need to use them later.

4.  Remove any DNS addresses that may be already listed and replace them with:

    ```txt
    1.1.1.3
    1.0.0.3
    ```

5.  Click **OK** > **Apply**.

### IPv6

1.  Go to **System Preferences**. You can find it by pressing <kbd>Command</kbd> + <kbd>Space</kbd> on your keyboard and typing `System Preferences`.

2.  Click **Network** > **Advanced**.

3.  Select the **DNS** tab. Take note of any DNS addresses you might have and save them in a safe place in case you need to use them later.

4.  Remove any DNS addresses that may be already listed and replace them with:

    ```txt
    2606:4700:4700::1113
    2606:4700:4700::1003
    ```

5.  Click **OK** > **Apply**.

{{<render file="_captive-portals.md">}}