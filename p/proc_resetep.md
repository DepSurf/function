# Function: <code>proc_resetep</code>

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
In drivers/usb/core/devio.c (ffffffff8161cdd9)
Location: drivers/usb/core/devio.c:1144
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
In drivers/usb/core/devio.c (ffffffff8167da0c)
Location: drivers/usb/core/devio.c:1258
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
In drivers/usb/core/devio.c (ffffffff816ab790)
Location: drivers/usb/core/devio.c:1258
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
In drivers/usb/core/devio.c (ffffffff816c0a5d)
Location: drivers/usb/core/devio.c:1252
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
In drivers/usb/core/devio.c (ffffffff8172c48d)
Location: drivers/usb/core/devio.c:1242
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
In drivers/usb/core/devio.c (ffffffff8176b616)
Location: drivers/usb/core/devio.c:1237
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
In drivers/usb/core/devio.c (ffffffff8178fba6)
Location: drivers/usb/core/devio.c:1238
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
In drivers/usb/core/devio.c (ffffffff817cd0e5)
Location: drivers/usb/core/devio.c:1227
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
In drivers/usb/core/devio.c (ffffffff817fe624)
Location: drivers/usb/core/devio.c:1271
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int proc_resetep(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1271
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff818cc360-ffffffff818cc407: proc_resetep (STB_LOCAL)
ffffffff818cf578-ffffffff818cf596: proc_resetep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int proc_resetep(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1285
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff818d7540-ffffffff818d75e7: proc_resetep (STB_LOCAL)
ffffffff81c1e466-ffffffff81c1e484: proc_resetep.cold (STB_LOCAL)
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
In drivers/usb/core/devio.c (ffffffff818bccdc)
Location: drivers/usb/core/devio.c:1290
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
In drivers/usb/core/devio.c (ffffffff81952ec5)
Location: drivers/usb/core/devio.c:1368
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
In drivers/usb/core/devio.c (ffffffff81aac421)
Location: drivers/usb/core/devio.c:1384
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
In drivers/usb/core/devio.c (ffffffff81c33a17)
Location: drivers/usb/core/devio.c:1384
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
In drivers/usb/core/devio.c (ffffffff81c9b411)
Location: drivers/usb/core/devio.c:1393
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
In drivers/usb/core/devio.c (ffffffff81d4ffc7)
Location: drivers/usb/core/devio.c:1393
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffff800010a31f3c)
Location: drivers/usb/core/devio.c:1271
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c0b060b4)
Location: drivers/usb/core/devio.c:1271
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c000000000aef5f0)
Location: drivers/usb/core/devio.c:1271
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffe0006504d0)
Location: drivers/usb/core/devio.c:1271
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
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
In drivers/usb/core/devio.c (ffffffff817b6a04)
Location: drivers/usb/core/devio.c:1271
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
In drivers/usb/core/devio.c (ffffffff817a8424)
Location: drivers/usb/core/devio.c:1271
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
In drivers/usb/core/devio.c (ffffffff817f34a4)
Location: drivers/usb/core/devio.c:1271
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
In drivers/usb/core/devio.c (ffffffff8180d71f)
Location: drivers/usb/core/devio.c:1271
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
