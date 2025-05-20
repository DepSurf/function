# Function: <code>pty_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff814ec310)
Location: drivers/tty/pty.c:200
Inline: True
```
**Symbols:**

```
ffffffff814ec310-ffffffff814ec366: pty_signal.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff8153d360)
Location: drivers/tty/pty.c:200
Inline: True
```
**Symbols:**

```
ffffffff8153d360-ffffffff8153d3b6: pty_signal.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff815699b0)
Location: drivers/tty/pty.c:200
Inline: True
```
**Symbols:**

```
ffffffff815699b0-ffffffff81569a06: pty_signal.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff8157e260)
Location: drivers/tty/pty.c:203
Inline: True
```
**Symbols:**

```
ffffffff8157e260-ffffffff8157e2b8: pty_signal.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff815e2ae0)
Location: drivers/tty/pty.c:204
Inline: True
```
**Symbols:**

```
ffffffff815e2ae0-ffffffff815e2b38: pty_signal.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff8161bdb0)
Location: drivers/tty/pty.c:207
Inline: True
```
**Symbols:**

```
ffffffff8161bdb0-ffffffff8161be07: pty_signal.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff81639030)
Location: drivers/tty/pty.c:208
Inline: True
```
**Symbols:**

```
ffffffff81639030-ffffffff81639087: pty_signal.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff8166d310)
Location: drivers/tty/pty.c:208
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff8166d310-ffffffff8166d36b: pty_signal.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff8168f980)
Location: drivers/tty/pty.c:208
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff8168f980-ffffffff8168f9db: pty_signal.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pty_signal(struct tty_struct *tty, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81741af0)
Location: drivers/tty/pty.c:208
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff81741af0-ffffffff81741b4f: pty_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pty_signal(struct tty_struct *tty, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8175d9b0)
Location: drivers/tty/pty.c:208
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff8175d9b0-ffffffff8175da0f: pty_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pty_signal(struct tty_struct *tty, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81741780)
Location: drivers/tty/pty.c:211
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff81741780-ffffffff817417df: pty_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pty_signal(struct tty_struct *tty, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff817c21d0)
Location: drivers/tty/pty.c:198
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff817c21d0-ffffffff817c222f: pty_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pty_signal(struct tty_struct *tty, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff818fed50)
Location: drivers/tty/pty.c:188
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff818fed50-ffffffff818fedb3: pty_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pty_signal(struct tty_struct *tty, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81a58580)
Location: drivers/tty/pty.c:188
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff81a58580-ffffffff81a585e3: pty_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pty_signal(struct tty_struct *tty, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81aa2ba0)
Location: drivers/tty/pty.c:188
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff81aa2ba0-ffffffff81aa2c03: pty_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pty_signal(struct tty_struct *tty, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81af5510)
Location: drivers/tty/pty.c:188
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff81af5510-ffffffff81af5573: pty_signal (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffff800010861918)
Location: drivers/tty/pty.c:208
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffff800010861918-ffff80001086198c: pty_signal.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pty_signal(struct tty_struct *tty, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (c0968004)
Location: drivers/tty/pty.c:208
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
c0968004-c0968068: pty_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pty_signal(struct tty_struct *tty, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (c000000000900600)
Location: drivers/tty/pty.c:208
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
c000000000900600-c0000000009006a8: pty_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pty_signal(struct tty_struct *tty, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffe000538d12)
Location: drivers/tty/pty.c:208
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffe000538d12-ffffffe000538d7a: pty_signal (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff81655400)
Location: drivers/tty/pty.c:208
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff81655400-ffffffff8165545b: pty_signal.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff816357b0)
Location: drivers/tty/pty.c:208
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff816357b0-ffffffff8163580b: pty_signal.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff816837c0)
Location: drivers/tty/pty.c:208
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff816837c0-ffffffff8168381b: pty_signal.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (ffffffff8169def0)
Location: drivers/tty/pty.c:208
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff8169def0-ffffffff8169df4b: pty_signal.isra.0 (STB_LOCAL)
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
</ul>
