# Function: <code>usb_get_std_status</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8171815a)
Location: include/linux/usb.h:1774
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81722a8a)
Location: include/linux/usb.h:1774
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81756f9b)
Location: include/linux/usb.h:1793
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817616ea)
Location: include/linux/usb.h:1793
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8177b43b)
Location: include/linux/usb.h:1793
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81785baa)
Location: include/linux/usb.h:1793
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b8e4d)
Location: include/linux/usb.h:1793
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817c4073)
Location: include/linux/usb.h:1793
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e969d)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817f4b33)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b8a2e)
Location: include/linux/usb.h:1805
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff818c487a)
Location: include/linux/usb.h:1805
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c731d)
Location: include/linux/usb.h:1820
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff818d076a)
Location: include/linux/usb.h:1820
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818aa753)
Location: include/linux/usb.h:1829
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff818b3d87)
Location: include/linux/usb.h:1829
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
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
In drivers/usb/core/hub.c (ffffffff8193f6ad)
Location: include/linux/usb.h:1822
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff8194927e)
Location: include/linux/usb.h:1822
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
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
In drivers/usb/core/hub.c (ffffffff81a9789d)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81aa1eb4)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
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
In drivers/usb/core/hub.c (ffffffff81c1a5b3)
Location: include/linux/usb.h:1842
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81c2781c)
Location: include/linux/usb.h:1842
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
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
In drivers/usb/core/hub.c (ffffffff81c815da)
Location: include/linux/usb.h:1881
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81c8e9a8)
Location: include/linux/usb.h:1881
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
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
In drivers/usb/core/hub.c (ffffffff81d35e25)
Location: include/linux/usb.h:1848
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81d434f8)
Location: include/linux/usb.h:1848
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a18d58)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/driver.c (ffff800010a256e8)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0af0f20)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (c0afbe88)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ad203c)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/driver.c (c000000000ae0b28)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063d960)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/driver.c (ffffffe00064797e)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817a1a7d)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817acf13)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817938b7)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff8179e913)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817de51d)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817e99b3)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f88de)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81803ee3)
Location: include/linux/usb.h:1798
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend_both
```
</details>
</li>
</ul>

## Differences
