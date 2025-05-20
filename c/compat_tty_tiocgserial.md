# Function: <code>compat_tty_tiocgserial</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162bdb0)
Location: drivers/tty/tty_io.c:2724
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff8162bdb0-ffffffff8162bece: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8165fd20)
Location: drivers/tty/tty_io.c:2728
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff8165fd20-ffffffff8165fe40: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81682340)
Location: drivers/tty/tty_io.c:2728
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81682340-ffffffff8168248e: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817338a0)
Location: drivers/tty/tty_io.c:2727
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff817338a0-ffffffff817339ee: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8174f9e0)
Location: drivers/tty/tty_io.c:2815
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff8174f9e0-ffffffff8174fb2e: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81733950)
Location: drivers/tty/tty_io.c:2864
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81733950-ffffffff81733a94: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b42c0)
Location: drivers/tty/tty_io.c:2864
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff817b42c0-ffffffff817b4404: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f0040)
Location: drivers/tty/tty_io.c:2837
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff818f0040-ffffffff818f018e: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a48150)
Location: drivers/tty/tty_io.c:2836
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81a48150-ffffffff81a4829e: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a92270)
Location: drivers/tty/tty_io.c:2845
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81a92270-ffffffff81a923be: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae4c50)
Location: drivers/tty/tty_io.c:2862
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81ae4c50-ffffffff81ae4d9e: compat_tty_tiocgserial (STB_LOCAL)
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
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010851d58)
Location: drivers/tty/tty_io.c:2728
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffff800010851d58-ffff800010851f90: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ed070)
Location: drivers/tty/tty_io.c:2728
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
c0000000008ed070-c0000000008ed1d8: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81647dc0)
Location: drivers/tty/tty_io.c:2728
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81647dc0-ffffffff81647f0e: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81628220)
Location: drivers/tty/tty_io.c:2728
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81628220-ffffffff8162836e: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81676180)
Location: drivers/tty/tty_io.c:2728
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81676180-ffffffff816762ce: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compat_tty_tiocgserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816908a0)
Location: drivers/tty/tty_io.c:2728
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff816908a0-ffffffff816909ee: compat_tty_tiocgserial (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
