# Function: <code>usb_disable_usb2_hardware_lpm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817870d0)
Location: drivers/usb/core/driver.c:1923
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
**Symbols:**

```
ffffffff817870d0-ffffffff8178711f: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817c5550)
Location: drivers/usb/core/driver.c:1910
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff817c5550-ffffffff817c559f: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817f5ef0)
Location: drivers/usb/core/driver.c:1912
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff817f5ef0-ffffffff817f5f3f: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818c5e00)
Location: drivers/usb/core/driver.c:2010
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff818c5e00-ffffffff818c5e52: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818d1cd0)
Location: drivers/usb/core/driver.c:2020
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff818d1cd0-ffffffff818d1d22: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818b52d0)
Location: drivers/usb/core/driver.c:2016
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff818b52d0-ffffffff818b5322: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8194a850)
Location: drivers/usb/core/driver.c:2016
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff8194a850-ffffffff8194a8a2: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81aa3570)
Location: drivers/usb/core/driver.c:2018
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff81aa3570-ffffffff81aa35d8: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c29120)
Location: drivers/usb/core/driver.c:2018
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff81c29120-ffffffff81c29188: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c900f0)
Location: drivers/usb/core/driver.c:2018
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff81c900f0-ffffffff81c90156: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81d44ca0)
Location: drivers/usb/core/driver.c:2024
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff81d44ca0-ffffffff81d44d06: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffff800010a26f30)
Location: drivers/usb/core/driver.c:1912
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffff800010a26f30-ffff800010a26fa0: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c0afcfbc)
Location: drivers/usb/core/driver.c:1912
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
c0afcfbc-c0afd01c: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c000000000ae2a40)
Location: drivers/usb/core/driver.c:1912
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
c000000000ae2a40-c000000000ae2af0: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffe000648d5e)
Location: drivers/usb/core/driver.c:1912
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffe000648d5e-ffffffe000648daa: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817ae2d0)
Location: drivers/usb/core/driver.c:1912
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff817ae2d0-ffffffff817ae31f: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8179fcd0)
Location: drivers/usb/core/driver.c:1912
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff8179fcd0-ffffffff8179fd1f: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817ead70)
Location: drivers/usb/core/driver.c:1912
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff817ead70-ffffffff817eadbf: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81804fb0)
Location: drivers/usb/core/driver.c:1912
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:usb_port_shutdown
```
**Symbols:**

```
ffffffff81804fb0-ffffffff81804fff: usb_disable_usb2_hardware_lpm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
