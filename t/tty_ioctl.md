# Function: <code>tty_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e2180)
Location: drivers/tty/tty_io.c:2841
Inline: False
```
**Symbols:**

```
ffffffff814e2180-ffffffff814e2db5: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81533af0)
Location: drivers/tty/tty_io.c:2850
Inline: False
```
**Symbols:**

```
ffffffff81533af0-ffffffff8153475f: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81560220)
Location: drivers/tty/tty_io.c:2850
Inline: False
```
**Symbols:**

```
ffffffff81560220-ffffffff81560e8a: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815739a0)
Location: drivers/tty/tty_io.c:2403
Inline: False
```
**Symbols:**

```
ffffffff815739a0-ffffffff8157422c: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d7e70)
Location: drivers/tty/tty_io.c:2510
Inline: False
```
**Symbols:**

```
ffffffff815d7e70-ffffffff815d8724: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81611870)
Location: drivers/tty/tty_io.c:2528
Inline: False
```
**Symbols:**

```
ffffffff81611870-ffffffff81612116: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162e5e0)
Location: drivers/tty/tty_io.c:2531
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff8162e5e0-ffffffff8162eeb4: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816621c0)
Location: drivers/tty/tty_io.c:2535
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff816621c0-ffffffff81662a9a: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81684830)
Location: drivers/tty/tty_io.c:2535
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81684830-ffffffff8168510a: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81735e90)
Location: drivers/tty/tty_io.c:2534
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81735e90-ffffffff817365df: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817529d0)
Location: drivers/tty/tty_io.c:2622
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff817529d0-ffffffff8175312a: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817368c0)
Location: drivers/tty/tty_io.c:2683
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff817368c0-ffffffff8173716c: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b7280)
Location: drivers/tty/tty_io.c:2681
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff817b7280-ffffffff817b7b45: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f2620)
Location: drivers/tty/tty_io.c:2654
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff818f2620-ffffffff818f2edc: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2653
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff82094fa3-ffffffff82094fb7: tty_ioctl.cold (STB_LOCAL)
ffffffff81a4abe0-ffffffff81a4b4b8: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2662
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff82115dc1-ffffffff82115dd5: tty_ioctl.cold (STB_LOCAL)
ffffffff81a94df0-ffffffff81a956d7: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2679
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff821f3ac8-ffffffff821f3adc: tty_ioctl.cold (STB_LOCAL)
ffffffff81ae77e0-ffffffff81ae80b5: tty_ioctl (STB_GLOBAL)
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
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010851f90)
Location: drivers/tty/tty_io.c:2535
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffff800010851f90-ffff800010852f5c: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095cb14)
Location: drivers/tty/tty_io.c:2535
Inline: False
```
**Symbols:**

```
c095cb14-c095d718: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008f08a0)
Location: drivers/tty/tty_io.c:2535
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
c0000000008f08a0-c0000000008f172c: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052f3d6)
Location: drivers/tty/tty_io.c:2535
Inline: False
```
**Symbols:**

```
ffffffe00052f3d6-ffffffe00052fb18: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8164a2b0)
Location: drivers/tty/tty_io.c:2535
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff8164a2b0-ffffffff8164ab8a: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162a700)
Location: drivers/tty/tty_io.c:2535
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff8162a700-ffffffff8162afda: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81678670)
Location: drivers/tty/tty_io.c:2535
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81678670-ffffffff81678f4a: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int tty_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816922b0)
Location: drivers/tty/tty_io.c:2535
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff816922b0-ffffffff81692b86: tty_ioctl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
