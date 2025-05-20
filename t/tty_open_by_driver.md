# Function: <code>tty_open_by_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81535133)
Location: drivers/tty/tty_io.c:2022
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff8156185e)
Location: drivers/tty/tty_io.c:2022
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tty_struct *tty_open_by_driver(dev_t device, struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81575250)
Location: drivers/tty/tty_io.c:1804
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81575250-ffffffff81575483: tty_open_by_driver (STB_GLOBAL)
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
In drivers/tty/tty_io.c (ffffffff815d9c1f)
Location: drivers/tty/tty_io.c:1906
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff81612bad)
Location: drivers/tty/tty_io.c:1924
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff8162fc4d)
Location: drivers/tty/tty_io.c:1936
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff81663b0c)
Location: drivers/tty/tty_io.c:1940
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff8168617c)
Location: drivers/tty/tty_io.c:1940
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tty_struct *tty_open_by_driver(dev_t device, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81737d30)
Location: drivers/tty/tty_io.c:1939
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81737d30-ffffffff8173806b: tty_open_by_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tty_struct *tty_open_by_driver(dev_t device, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817540f0)
Location: drivers/tty/tty_io.c:2023
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff817540f0-ffffffff8175442b: tty_open_by_driver (STB_LOCAL)
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
In drivers/tty/tty_io.c (ffffffff817381b8)
Location: drivers/tty/tty_io.c:2058
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff817b8c58)
Location: drivers/tty/tty_io.c:2054
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff818f4c17)
Location: drivers/tty/tty_io.c:2042
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff81a4d242)
Location: drivers/tty/tty_io.c:2037
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff81a97548)
Location: drivers/tty/tty_io.c:2046
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff81ae9f87)
Location: drivers/tty/tty_io.c:2044
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffff800010853b7c)
Location: drivers/tty/tty_io.c:1940
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (c095e5f8)
Location: drivers/tty/tty_io.c:1940
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (c0000000008f30c0)
Location: drivers/tty/tty_io.c:1940
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffe0005303ea)
Location: drivers/tty/tty_io.c:1940
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff8164bbfc)
Location: drivers/tty/tty_io.c:1940
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff8162c04c)
Location: drivers/tty/tty_io.c:1940
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff81679fbc)
Location: drivers/tty/tty_io.c:1940
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff8169461c)
Location: drivers/tty/tty_io.c:1940
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
