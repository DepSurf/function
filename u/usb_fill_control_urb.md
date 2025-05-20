# Function: <code>usb_fill_control_urb</code>

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
In drivers/usb/core/message.c (ffffffff81610f71)
Location: include/linux/usb.h:1512
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff81670b81)
Location: include/linux/usb.h:1509
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff8169e831)
Location: include/linux/usb.h:1509
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff816b3a41)
Location: include/linux/usb.h:1580
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff8171f1f5)
Location: include/linux/usb.h:1581
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff8175df85)
Location: include/linux/usb.h:1600
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff81782555)
Location: include/linux/usb.h:1600
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff817c0a1d)
Location: include/linux/usb.h:1600
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff817f139d)
Location: include/linux/usb.h:1605
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818c0cdb)
Location: include/linux/usb.h:1612
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff818ccdcb)
Location: include/linux/usb.h:1618
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff818b03dd)
Location: include/linux/usb.h:1627
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8194563d)
Location: include/linux/usb.h:1620
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
```
```
In drivers/usb/core/devio.c (ffffffff8194fd0d)
Location: include/linux/usb.h:1620
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81a9dce4)
Location: include/linux/usb.h:1611
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
```
```
In drivers/usb/core/devio.c (ffffffff81aab202)
Location: include/linux/usb.h:1611
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c22db4)
Location: include/linux/usb.h:1640
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
```
```
In drivers/usb/core/devio.c (ffffffff81c32682)
Location: include/linux/usb.h:1640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c89d34)
Location: include/linux/usb.h:1671
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
```
```
In drivers/usb/core/devio.c (ffffffff81c99952)
Location: include/linux/usb.h:1671
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81d3e751)
Location: include/linux/usb.h:1659
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
```
```
In drivers/usb/core/devio.c (ffffffff81d4e521)
Location: include/linux/usb.h:1659
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
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
In drivers/usb/core/message.c (ffff800010a217d4)
Location: include/linux/usb.h:1605
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (c0af81d8)
Location: include/linux/usb.h:1605
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (c000000000adb964)
Location: include/linux/usb.h:1605
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffe00064432c)
Location: include/linux/usb.h:1605
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff817a977d)
Location: include/linux/usb.h:1605
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff8179b17d)
Location: include/linux/usb.h:1605
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff817e621d)
Location: include/linux/usb.h:1605
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
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
In drivers/usb/core/message.c (ffffffff8180047d)
Location: include/linux/usb.h:1605
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_control_msg
```
</details>
</li>
</ul>

## Differences
