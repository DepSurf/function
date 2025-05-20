# Function: <code>__ia32_sys_bdflush</code>

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
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_bdflush(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:3294
Inline: False
```
**Symbols:**

```
ffffffff812dae35-ffffffff812dae6b: __ia32_sys_bdflush.cold.59 (STB_LOCAL)
ffffffff812d6800-ffffffff812d6845: __ia32_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_bdflush(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:3306
Inline: False
```
**Symbols:**

```
ffffffff812f0315-ffffffff812f034b: __ia32_sys_bdflush.cold.62 (STB_LOCAL)
ffffffff812ebc80-ffffffff812ebcc5: __ia32_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_bdflush(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:3313
Inline: False
```
**Symbols:**

```
ffffffff81311bfc-ffffffff81311c32: __ia32_sys_bdflush.cold (STB_LOCAL)
ffffffff8130d3a0-ffffffff8130d3e5: __ia32_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cbec0)
Location: kernel/sys_ni.c:410
Inline: False
```
**Symbols:**

```
ffffffff81324c09-ffffffff81324c3f: __ia32_sys_bdflush.cold (STB_LOCAL)
ffffffff81320370-ffffffff813203b5: __ia32_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:410
Inline: False
```
**Symbols:**

```
ffffffff8135e75a-ffffffff8135e790: __ia32_sys_bdflush.cold (STB_LOCAL)
ffffffff81359550-ffffffff81359598: __ia32_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:411
Inline: False
```
**Symbols:**

```
ffffffff81bea9fe-ffffffff81beaa34: __ia32_sys_bdflush.cold (STB_LOCAL)
ffffffff81367310-ffffffff81367358: __ia32_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:417
Inline: False
```
**Symbols:**

```
ffffffff81bdca2d-ffffffff81bdca63: __ia32_sys_bdflush.cold (STB_LOCAL)
ffffffff8136dd10-ffffffff8136dd58: __ia32_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c6240)
Location: kernel/sys_ni.c:410
Inline: False
```
**Symbols:**

```
ffffffff8131d1e9-ffffffff8131d21f: __ia32_sys_bdflush.cold (STB_LOCAL)
ffffffff81318950-ffffffff81318995: __ia32_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b4a60)
Location: kernel/sys_ni.c:410
Inline: False
```
**Symbols:**

```
ffffffff8130dd89-ffffffff8130ddbf: __ia32_sys_bdflush.cold (STB_LOCAL)
ffffffff81309540-ffffffff81309585: __ia32_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c5790)
Location: kernel/sys_ni.c:410
Inline: False
```
**Symbols:**

```
ffffffff8131acb9-ffffffff8131acef: __ia32_sys_bdflush.cold (STB_LOCAL)
ffffffff81316420-ffffffff81316465: __ia32_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cdbd0)
Location: kernel/sys_ni.c:410
Inline: False
```
**Symbols:**

```
ffffffff8132c95f-ffffffff8132c995: __ia32_sys_bdflush.cold (STB_LOCAL)
ffffffff813281e0-ffffffff81328225: __ia32_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct pt_regs *__unused</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct pt_regs *regs</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
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
