# Function: <code>tty_driver_kref_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e0b63)
Location: include/linux/tty_driver.h:357
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
```
In drivers/tty/pty.c (ffffffff814eca39)
Location: include/linux/tty_driver.h:357
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815351e5)
Location: include/linux/tty_driver.h:357
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff8153d857)
Location: include/linux/tty_driver.h:357
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8156190a)
Location: include/linux/tty_driver.h:357
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff81569ea7)
Location: include/linux/tty_driver.h:357
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815752e5)
Location: include/linux/tty_driver.h:357
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff8157e052)
Location: include/linux/tty_driver.h:357
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d7b4a)
Location: include/linux/tty_driver.h:360
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff815e2fa2)
Location: include/linux/tty_driver.h:360
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff816108ca)
Location: include/linux/tty_driver.h:360
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff8161c25d)
Location: include/linux/tty_driver.h:360
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff8162d7ea)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff816394dd)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff8166141a)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff8166d7cd)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff81683a6a)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff8168fe3d)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff8173447b)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff817424ad)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff817505cb)
Location: include/linux/tty_driver.h:354
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff8175e34d)
Location: include/linux/tty_driver.h:354
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff81734448)
Location: include/linux/tty_driver.h:354
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff8174213d)
Location: include/linux/tty_driver.h:354
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff817b4da8)
Location: include/linux/tty_driver.h:340
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff817c2bfd)
Location: include/linux/tty_driver.h:340
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff818f3720)
Location: include/linux/tty_driver.h:480
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff818ffc2d)
Location: include/linux/tty_driver.h:480
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff81a4bffb)
Location: include/linux/tty_driver.h:479
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff81a5965d)
Location: include/linux/tty_driver.h:479
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff81a9628f)
Location: include/linux/tty_driver.h:479
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff81aa3c8d)
Location: include/linux/tty_driver.h:479
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff81ae8b8f)
Location: include/linux/tty_driver.h:477
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff81af665b)
Location: include/linux/tty_driver.h:477
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffff80001084eb9c)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffff8000108616c4)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (c095ab70)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (c0968718)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (c0000000008edbd4)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (c000000000900d40)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffe00052d08a)
Location: include/linux/tty_driver.h:363
Inline: True
```
```
In drivers/tty/pty.c (ffffffe000539272)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff816494ea)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff816558bd)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff8162994a)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff81635c6d)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff816778aa)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff81683c7d)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
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
In drivers/tty/tty_io.c (ffffffff81691fba)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/pty.c (ffffffff8169e6cd)
Location: include/linux/tty_driver.h:363
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
</details>
</li>
</ul>

## Differences
