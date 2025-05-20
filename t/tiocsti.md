# Function: <code>tiocsti</code>

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
In drivers/tty/tty_io.c (ffffffff814e2632)
Location: drivers/tty/tty_io.c:2279
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff8153400d)
Location: drivers/tty/tty_io.c:2284
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81560738)
Location: drivers/tty/tty_io.c:2284
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81573d10)
Location: drivers/tty/tty_io.c:2042
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff815d81f4)
Location: drivers/tty/tty_io.c:2149
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81611b1e)
Location: drivers/tty/tty_io.c:2167
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff8162e88e)
Location: drivers/tty/tty_io.c:2179
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81662358)
Location: drivers/tty/tty_io.c:2183
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff816849c8)
Location: drivers/tty/tty_io.c:2183
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tiocsti(struct tty_struct *tty, char *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81733f90)
Location: drivers/tty/tty_io.c:2182
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81733f90-ffffffff81734076: tiocsti (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tiocsti(struct tty_struct *tty, char *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817500e0)
Location: drivers/tty/tty_io.c:2266
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff817500e0-ffffffff817501c6: tiocsti (STB_LOCAL)
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
In drivers/tty/tty_io.c (ffffffff81736a5c)
Location: drivers/tty/tty_io.c:2301
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff817b741c)
Location: drivers/tty/tty_io.c:2295
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff818f27d2)
Location: drivers/tty/tty_io.c:2278
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81a4ad84)
Location: drivers/tty/tty_io.c:2274
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81a95118)
Location: drivers/tty/tty_io.c:2283
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81ae7b08)
Location: drivers/tty/tty_io.c:2281
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffff80001085236c)
Location: drivers/tty/tty_io.c:2183
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (c095d2a4)
Location: drivers/tty/tty_io.c:2183
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (c0000000008f124c)
Location: drivers/tty/tty_io.c:2183
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffe00052f664)
Location: drivers/tty/tty_io.c:2183
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff8164a448)
Location: drivers/tty/tty_io.c:2183
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff8162a898)
Location: drivers/tty/tty_io.c:2183
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81678808)
Location: drivers/tty/tty_io.c:2183
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
In drivers/tty/tty_io.c (ffffffff81692448)
Location: drivers/tty/tty_io.c:2183
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
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
