# Function: <code>tioccons</code>

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
In drivers/tty/tty_io.c (ffffffff814e2b94)
Location: drivers/tty/tty_io.c:2385
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
In drivers/tty/tty_io.c (ffffffff8153437c)
Location: drivers/tty/tty_io.c:2392
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
In drivers/tty/tty_io.c (ffffffff81560aa7)
Location: drivers/tty/tty_io.c:2392
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
In drivers/tty/tty_io.c (ffffffff81573ff2)
Location: drivers/tty/tty_io.c:2150
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
In drivers/tty/tty_io.c (ffffffff815d84e5)
Location: drivers/tty/tty_io.c:2257
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
In drivers/tty/tty_io.c (ffffffff81611c32)
Location: drivers/tty/tty_io.c:2275
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
In drivers/tty/tty_io.c (ffffffff8162e9a7)
Location: drivers/tty/tty_io.c:2288
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
In drivers/tty/tty_io.c (ffffffff816625c6)
Location: drivers/tty/tty_io.c:2292
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
In drivers/tty/tty_io.c (ffffffff81684c36)
Location: drivers/tty/tty_io.c:2292
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
int tioccons(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81735dc0)
Location: drivers/tty/tty_io.c:2291
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81735dc0-ffffffff81735e84: tioccons (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tioccons(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817528d0)
Location: drivers/tty/tty_io.c:2374
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff817528d0-ffffffff817529ca: tioccons (STB_LOCAL)
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
In drivers/tty/tty_io.c (ffffffff81736cc3)
Location: drivers/tty/tty_io.c:2409
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
In drivers/tty/tty_io.c (ffffffff817b769c)
Location: drivers/tty/tty_io.c:2406
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
In drivers/tty/tty_io.c (ffffffff818f2c97)
Location: drivers/tty/tty_io.c:2385
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
In drivers/tty/tty_io.c (ffffffff81a4b2ca)
Location: drivers/tty/tty_io.c:2384
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
In drivers/tty/tty_io.c (ffffffff81a95367)
Location: drivers/tty/tty_io.c:2393
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
In drivers/tty/tty_io.c (ffffffff81ae7d45)
Location: drivers/tty/tty_io.c:2391
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
In drivers/tty/tty_io.c (ffff800010852514)
Location: drivers/tty/tty_io.c:2292
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
In drivers/tty/tty_io.c (c095d478)
Location: drivers/tty/tty_io.c:2292
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
In drivers/tty/tty_io.c (c0000000008f0d84)
Location: drivers/tty/tty_io.c:2292
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
In drivers/tty/tty_io.c (ffffffe00052f660)
Location: drivers/tty/tty_io.c:2292
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
In drivers/tty/tty_io.c (ffffffff8164a6b6)
Location: drivers/tty/tty_io.c:2292
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
In drivers/tty/tty_io.c (ffffffff8162ab06)
Location: drivers/tty/tty_io.c:2292
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
In drivers/tty/tty_io.c (ffffffff81678a76)
Location: drivers/tty/tty_io.c:2292
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
In drivers/tty/tty_io.c (ffffffff816926b6)
Location: drivers/tty/tty_io.c:2292
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
