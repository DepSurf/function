# Function: <code>pty_unix98_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff814ec780)
Location: drivers/tty/pty.c:609
Inline: True
```
**Symbols:**

```
ffffffff814ec780-ffffffff814ec82b: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8153db20)
Location: drivers/tty/pty.c:596
Inline: True
```
**Symbols:**

```
ffffffff8153db20-ffffffff8153dbcb: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8156a170)
Location: drivers/tty/pty.c:596
Inline: True
```
**Symbols:**

```
ffffffff8156a170-ffffffff8156a21b: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8157e6c0)
Location: drivers/tty/pty.c:654
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff8157e6c0-ffffffff8157e76b: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff815e3230)
Location: drivers/tty/pty.c:655
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff815e3230-ffffffff815e32db: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8161c500)
Location: drivers/tty/pty.c:658
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff8161c500-ffffffff8161c5a7: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81639780)
Location: drivers/tty/pty.c:663
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff81639780-ffffffff81639827: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8166da80)
Location: drivers/tty/pty.c:663
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff8166da80-ffffffff8166db2f: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff816900f0)
Location: drivers/tty/pty.c:663
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff816900f0-ffffffff8169019f: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81742800)
Location: drivers/tty/pty.c:663
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff81742800-ffffffff817428e3: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8175e6a0)
Location: drivers/tty/pty.c:663
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff8175e6a0-ffffffff8175e783: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81742440)
Location: drivers/tty/pty.c:667
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff81742440-ffffffff817424fd: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (0)
Location: drivers/tty/pty.c:652
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff817c2f40-ffffffff817c3009: pty_unix98_ioctl (STB_LOCAL)
ffffffff81cf8d71-ffffffff81cf8d94: pty_unix98_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (0)
Location: drivers/tty/pty.c:642
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff818ff090-ffffffff818ff1ad: pty_unix98_ioctl (STB_LOCAL)
ffffffff81ec0e1e-ffffffff81ec0e41: pty_unix98_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (0)
Location: drivers/tty/pty.c:642
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff81a58b80-ffffffff81a58c9d: pty_unix98_ioctl (STB_LOCAL)
ffffffff820952e0-ffffffff82095303: pty_unix98_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (0)
Location: drivers/tty/pty.c:642
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff81aa31b0-ffffffff81aa32d1: pty_unix98_ioctl (STB_LOCAL)
ffffffff82116114-ffffffff82116137: pty_unix98_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (0)
Location: drivers/tty/pty.c:642
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff81af5b20-ffffffff81af5c41: pty_unix98_ioctl (STB_LOCAL)
ffffffff821f3e24-ffffffff821f3e47: pty_unix98_ioctl.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffff800010862ca8)
Location: drivers/tty/pty.c:663
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffff800010862ca8-ffff800010862efc: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (c0968b9c)
Location: drivers/tty/pty.c:663
Inline: True
```
**Symbols:**

```
c0968b9c-c0968c8c: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (c000000000901960)
Location: drivers/tty/pty.c:663
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
c000000000901960-c000000000901a90: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffe000539948)
Location: drivers/tty/pty.c:663
Inline: True
```
**Symbols:**

```
ffffffe000539948-ffffffe000539a72: pty_unix98_ioctl (STB_LOCAL)
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
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81655b70)
Location: drivers/tty/pty.c:663
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff81655b70-ffffffff81655c1f: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81635f10)
Location: drivers/tty/pty.c:663
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff81635f10-ffffffff81635fbf: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81683f30)
Location: drivers/tty/pty.c:663
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff81683f30-ffffffff81683fdf: pty_unix98_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pty_unix98_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8169e020)
Location: drivers/tty/pty.c:663
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_compat_ioctl
```
**Symbols:**

```
ffffffff8169e020-ffffffff8169e0cf: pty_unix98_ioctl (STB_LOCAL)
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
