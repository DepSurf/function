# Function: <code>__tty_check_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e0160)
Location: drivers/tty/tty_io.c:393
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff814e0160-ffffffff814e0244: __tty_check_change.part.22 (STB_LOCAL)
ffffffff814e1d10-ffffffff814e1d42: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81533b73)
Location: drivers/tty/tty_io.c:396
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff81531990-ffffffff81531ad2: __tty_check_change.part.23 (STB_LOCAL)
ffffffff81532fc0-ffffffff81532ff2: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815602a3)
Location: drivers/tty/tty_io.c:396
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff8155e0d0-ffffffff8155e206: __tty_check_change.part.25 (STB_LOCAL)
ffffffff8155f6f0-ffffffff8155f722: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8157d7ae)
Location: drivers/tty/tty_jobctrl.c:30
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8157ceb0-ffffffff8157cfbf: __tty_check_change.part.0 (STB_LOCAL)
ffffffff8157d000-ffffffff8157d032: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff815e22d3)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff815e17e0-ffffffff815e18ef: __tty_check_change.part.0 (STB_LOCAL)
ffffffff815e1b20-ffffffff815e1b53: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8161b5c0)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8161aa90-ffffffff8161abb0: __tty_check_change.part.2 (STB_LOCAL)
ffffffff8161ade0-ffffffff8161ae0d: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff816388cc)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81637d00-ffffffff81637e20: __tty_check_change.part.2 (STB_LOCAL)
ffffffff81638050-ffffffff8163807d: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8166cb5e)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8166bfb0-ffffffff8166c0b6: __tty_check_change.part.0 (STB_LOCAL)
ffffffff8166c340-ffffffff8166c36c: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8168f1ce)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8168e620-ffffffff8168e726: __tty_check_change.part.0 (STB_LOCAL)
ffffffff8168e9b0-ffffffff8168e9dc: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81740d75)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tiocspgrp
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tiocspgrp
```
**Symbols:**

```
ffffffff817408d0-ffffffff817409d6: __tty_check_change.part.0 (STB_LOCAL)
ffffffff81740f40-ffffffff81740f6c: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8175c800)
Location: drivers/tty/tty_jobctrl.c:32
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff8175c800-ffffffff8175c90b: __tty_check_change.part.0 (STB_LOCAL)
ffffffff8175ce70-ffffffff8175ce9c: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8174147d)
Location: drivers/tty/tty_jobctrl.c:33
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81740690-ffffffff8174079b: __tty_check_change.part.0 (STB_LOCAL)
ffffffff81740b30-ffffffff81740b5c: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff817c1edd)
Location: drivers/tty/tty_jobctrl.c:33
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff817c10c0-ffffffff817c11fa: __tty_check_change.part.0 (STB_LOCAL)
ffffffff81cf8cac-ffffffff81cf8ccb: __tty_check_change.part.0.cold (STB_LOCAL)
ffffffff817c1590-ffffffff817c15bc: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff818fe959)
Location: drivers/tty/tty_jobctrl.c:33
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff818fda50-ffffffff818fdbae: __tty_check_change.part.0 (STB_LOCAL)
ffffffff81ec0dc8-ffffffff81ec0e09: __tty_check_change.part.0.cold (STB_LOCAL)
ffffffff818fdf70-ffffffff818fdfb0: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81a58199)
Location: drivers/tty/tty_jobctrl.c:33
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81a571c0-ffffffff81a5731f: __tty_check_change.part.0 (STB_LOCAL)
ffffffff8209528b-ffffffff820952cb: __tty_check_change.part.0.cold (STB_LOCAL)
ffffffff81a57730-ffffffff81a57770: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81aa27b6)
Location: drivers/tty/tty_jobctrl.c:33
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81aa17a0-ffffffff81aa191b: __tty_check_change.part.0 (STB_LOCAL)
ffffffff821160bd-ffffffff821160ff: __tty_check_change.part.0.cold (STB_LOCAL)
ffffffff81aa1d30-ffffffff81aa1d70: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81af5196)
Location: drivers/tty/tty_jobctrl.c:33
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81af4200-ffffffff81af437b: __tty_check_change.part.0 (STB_LOCAL)
ffffffff821f3dcd-ffffffff821f3e0f: __tty_check_change.part.0.cold (STB_LOCAL)
ffffffff81af4790-ffffffff81af47d0: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffff800010860cf4)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffff80001085fd50-ffff80001085fed8: __tty_check_change.part.0 (STB_LOCAL)
ffff8000108600b8-ffff80001086010c: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (c0967b78)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
c09670c0-c0967200: __tty_check_change.part.0 (STB_LOCAL)
c0967248-c096728c: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (c0000000008ffe54)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
c0000000008ff340-c0000000008ff4d4: __tty_check_change.part.0 (STB_LOCAL)
c0000000008ff520-c0000000008ff554: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffe0005388f0)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffe000537fb8-ffffffe0005380a2: __tty_check_change.part.0 (STB_LOCAL)
ffffffe0005380e6-ffffffe000538130: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81654c4e)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff816540a0-ffffffff816541a6: __tty_check_change.part.0 (STB_LOCAL)
ffffffff81654430-ffffffff8165445c: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81635018)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81634480-ffffffff81634586: __tty_check_change.part.0 (STB_LOCAL)
ffffffff81634810-ffffffff8163483c: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8168300e)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81682460-ffffffff81682566: __tty_check_change.part.0 (STB_LOCAL)
ffffffff816827f0-ffffffff8168281c: __tty_check_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tty_check_change(struct tty_struct *tty, int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8169d641)
Location: drivers/tty/tty_jobctrl.c:31
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8169caa0-ffffffff8169cbc1: __tty_check_change.part.0 (STB_LOCAL)
ffffffff8169ce50-ffffffff8169ce7c: __tty_check_change (STB_GLOBAL)
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
