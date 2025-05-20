# Function: <code>proc_bulk_compat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8161d1f9)
Location: drivers/usb/core/devio.c:1751
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8167db67)
Location: drivers/usb/core/devio.c:1948
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816ab8eb)
Location: drivers/usb/core/devio.c:1948
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816c08a1)
Location: drivers/usb/core/devio.c:1938
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8172c2d1)
Location: drivers/usb/core/devio.c:1947
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8176b49d)
Location: drivers/usb/core/devio.c:1958
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8178fa2d)
Location: drivers/usb/core/devio.c:1958
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817cd434)
Location: drivers/usb/core/devio.c:1981
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817fe98a)
Location: drivers/usb/core/devio.c:2026
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int proc_bulk_compat(struct usb_dev_state *ps, struct usbdevfs_bulktransfer32 *p32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818cc090)
Location: drivers/usb/core/devio.c:2026
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff818cc090-ffffffff818cc13d: proc_bulk_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818d9cc6)
Location: drivers/usb/core/devio.c:2040
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818bd21b)
Location: drivers/usb/core/devio.c:2045
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff819533be)
Location: drivers/usb/core/devio.c:2123
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81aac974)
Location: drivers/usb/core/devio.c:2139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c33fba)
Location: drivers/usb/core/devio.c:2139
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c9aaaa)
Location: drivers/usb/core/devio.c:2148
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81d4f67a)
Location: drivers/usb/core/devio.c:2148
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
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
int proc_bulk_compat(struct usb_dev_state *ps, struct usbdevfs_bulktransfer32 *p32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffff800010a2e168)
Location: drivers/usb/core/devio.c:2026
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffff800010a2e168-ffff800010a2e57c: proc_bulk_compat (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_bulk_compat(struct usb_dev_state *ps, struct usbdevfs_bulktransfer32 *p32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c000000000aecdc0)
Location: drivers/usb/core/devio.c:2026
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
c000000000aecdc0-c000000000aed1fc: proc_bulk_compat (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817b6d6a)
Location: drivers/usb/core/devio.c:2026
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817a878a)
Location: drivers/usb/core/devio.c:2026
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817f380a)
Location: drivers/usb/core/devio.c:2026
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8180da85)
Location: drivers/usb/core/devio.c:2026
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
