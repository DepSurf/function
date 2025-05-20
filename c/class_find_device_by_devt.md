# Function: <code>class_find_device_by_devt</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81685de7)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff816fa48c)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffff81737858)
Location: include/linux/device/class.h:164
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff817b355c)
Location: include/linux/device/class.h:164
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffff81753c18)
Location: include/linux/device/class.h:164
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff817c80ec)
Location: include/linux/device/class.h:164
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffff81737ab8)
Location: include/linux/device/class.h:164
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff817ab5fc)
Location: include/linux/device/class.h:164
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffff817b8554)
Location: include/linux/device/class.h:164
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff81834a7c)
Location: include/linux/device/class.h:164
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffff818f44c6)
Location: include/linux/device/class.h:164
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff819765cb)
Location: include/linux/device/class.h:164
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffff81a4cd2f)
Location: include/linux/device/class.h:164
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff81ae270b)
Location: include/linux/device/class.h:164
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffff81a9701f)
Location: include/linux/device/class.h:144
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff81b3062b)
Location: include/linux/device/class.h:144
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffff81ae9a3f)
Location: include/linux/device/class.h:142
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff81b87e2b)
Location: include/linux/device/class.h:142
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffff8000108537dc)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffff8000108e4ca8)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (c095e154)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (c09d36f8)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (c0000000008f2bb4)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (c00000000097a234)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffe00053009a)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffe000579aae)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffff8164b867)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff816bfc7c)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffff8162bcb7)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff8169af2c)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffff81679c27)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff816ee14c)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
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
In drivers/tty/tty_io.c (ffffffff81694287)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/base/core.c (ffffffff8170898c)
Location: include/linux/device.h:683
Inline: True
Inline callers:
  - drivers/base/core.c:device_destroy
```
</details>
</li>
</ul>

## Differences
