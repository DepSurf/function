# Function: <code>usb_fill_bulk_urb</code>

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
In drivers/usb/core/message.c (ffffffff81611306)
Location: include/linux/usb.h:1543
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff81670f06)
Location: include/linux/usb.h:1540
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff8169ebb6)
Location: include/linux/usb.h:1540
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff816b3db1)
Location: include/linux/usb.h:1611
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff8171f5e1)
Location: include/linux/usb.h:1612
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff8175e391)
Location: include/linux/usb.h:1631
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff81782961)
Location: include/linux/usb.h:1631
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff817c0e0b)
Location: include/linux/usb.h:1631
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff817f178b)
Location: include/linux/usb.h:1636
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff818c10cb)
Location: include/linux/usb.h:1643
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff818cd1bb)
Location: include/linux/usb.h:1649
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff818b07db)
Location: include/linux/usb.h:1658
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff81945a3b)
Location: include/linux/usb.h:1651
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/core/devio.c (ffffffff81950052)
Location: include/linux/usb.h:1651
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
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
In drivers/usb/core/message.c (ffffffff81a9e155)
Location: include/linux/usb.h:1642
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/core/devio.c (ffffffff81aab648)
Location: include/linux/usb.h:1642
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
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
In drivers/usb/core/message.c (ffffffff81c23265)
Location: include/linux/usb.h:1671
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/core/devio.c (ffffffff81c32b28)
Location: include/linux/usb.h:1671
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
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
In drivers/usb/core/message.c (ffffffff81c8a1e4)
Location: include/linux/usb.h:1706
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/core/devio.c (ffffffff81c99ddd)
Location: include/linux/usb.h:1706
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
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
In drivers/usb/core/message.c (ffffffff81d3ec04)
Location: include/linux/usb.h:1694
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/core/devio.c (ffffffff81d4e9ad)
Location: include/linux/usb.h:1694
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
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
In drivers/usb/core/message.c (ffff800010a21c54)
Location: include/linux/usb.h:1636
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (c0af85e8)
Location: include/linux/usb.h:1636
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (c000000000adbfc0)
Location: include/linux/usb.h:1636
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffe0006446da)
Location: include/linux/usb.h:1636
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff817a9b6b)
Location: include/linux/usb.h:1636
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff8179b56b)
Location: include/linux/usb.h:1636
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff817e660b)
Location: include/linux/usb.h:1636
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/message.c (ffffffff8180086b)
Location: include/linux/usb.h:1636
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
</details>
</li>
</ul>

## Differences
