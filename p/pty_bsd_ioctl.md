# Function: <code>pty_bsd_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff814ec6e0)
Location: drivers/tty/pty.c:482
Inline: True
```
**Symbols:**

```
ffffffff814ec6e0-ffffffff814ec77e: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8153da80)
Location: drivers/tty/pty.c:469
Inline: True
```
**Symbols:**

```
ffffffff8153da80-ffffffff8153db1e: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8156a0d0)
Location: drivers/tty/pty.c:469
Inline: True
```
**Symbols:**

```
ffffffff8156a0d0-ffffffff8156a16e: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8157e600)
Location: drivers/tty/pty.c:467
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff8157e600-ffffffff8157e69e: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff815e3170)
Location: drivers/tty/pty.c:468
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff815e3170-ffffffff815e320e: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8161c430)
Location: drivers/tty/pty.c:471
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff8161c430-ffffffff8161c4d4: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff816396b0)
Location: drivers/tty/pty.c:472
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff816396b0-ffffffff81639754: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8166d9b0)
Location: drivers/tty/pty.c:472
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff8166d9b0-ffffffff8166da53: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81690020)
Location: drivers/tty/pty.c:472
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff81690020-ffffffff816900c3: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81742700)
Location: drivers/tty/pty.c:472
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff81742700-ffffffff817427d8: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8175e5a0)
Location: drivers/tty/pty.c:472
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff8175e5a0-ffffffff8175e67c: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81742535)
Location: drivers/tty/pty.c:476
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff81742380-ffffffff81742436: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (0)
Location: drivers/tty/pty.c:463
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff817c2e50-ffffffff817c2f17: pty_bsd_ioctl (STB_LOCAL)
ffffffff81cf8d4e-ffffffff81cf8d71: pty_bsd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (0)
Location: drivers/tty/pty.c:453
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff818ff950-ffffffff818ffa6b: pty_bsd_ioctl (STB_LOCAL)
ffffffff81ec0ec5-ffffffff81ec0ee8: pty_bsd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (0)
Location: drivers/tty/pty.c:453
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff81a59360-ffffffff81a5947b: pty_bsd_ioctl (STB_LOCAL)
ffffffff82095387-ffffffff820953aa: pty_bsd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (0)
Location: drivers/tty/pty.c:453
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff81aa39a0-ffffffff81aa3aa1: pty_bsd_ioctl (STB_LOCAL)
ffffffff821161bb-ffffffff821161de: pty_bsd_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (0)
Location: drivers/tty/pty.c:453
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff81af6310-ffffffff81af6411: pty_bsd_ioctl (STB_LOCAL)
ffffffff821f3ecd-ffffffff821f3ef0: pty_bsd_ioctl.cold (STB_LOCAL)
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
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffff800010862678)
Location: drivers/tty/pty.c:472
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffff800010862678-ffff8000108627a8: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (c096855c)
Location: drivers/tty/pty.c:472
Inline: False
```
**Symbols:**

```
c096855c-c0968614: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (c000000000901860)
Location: drivers/tty/pty.c:472
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
c000000000901860-c000000000901914: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffe000539846)
Location: drivers/tty/pty.c:472
Inline: False
```
**Symbols:**

```
ffffffe000539846-ffffffe000539948: pty_bsd_ioctl (STB_LOCAL)
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
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81655aa0)
Location: drivers/tty/pty.c:472
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff81655aa0-ffffffff81655b43: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81635e40)
Location: drivers/tty/pty.c:472
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff81635e40-ffffffff81635ee3: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81683e60)
Location: drivers/tty/pty.c:472
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff81683e60-ffffffff81683f03: pty_bsd_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pty_bsd_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8169df50)
Location: drivers/tty/pty.c:472
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff8169df50-ffffffff8169dff3: pty_bsd_ioctl (STB_LOCAL)
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
