# Function: <code>__x64_sys_bdflush</code>

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
long int __x64_sys_bdflush(const struct pt_regs *regs);
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
ffffffff812dae6b-ffffffff812daea1: __x64_sys_bdflush.cold.60 (STB_LOCAL)
ffffffff812d6b60-ffffffff812d6ba5: __x64_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_bdflush(const struct pt_regs *regs);
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
ffffffff812f034b-ffffffff812f0381: __x64_sys_bdflush.cold.63 (STB_LOCAL)
ffffffff812ec1a0-ffffffff812ec1e5: __x64_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_bdflush(const struct pt_regs *regs);
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
ffffffff81311c32-ffffffff81311c68: __x64_sys_bdflush.cold (STB_LOCAL)
ffffffff8130d7f0-ffffffff8130d835: __x64_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cbea0)
Location: kernel/sys_ni.c:410
Inline: False
```
**Symbols:**

```
ffffffff81324c3f-ffffffff81324c75: __x64_sys_bdflush.cold (STB_LOCAL)
ffffffff813207c0-ffffffff81320805: __x64_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_bdflush(const struct pt_regs *__unused);
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
ffffffff8135e790-ffffffff8135e7c6: __x64_sys_bdflush.cold (STB_LOCAL)
ffffffff813598f0-ffffffff81359938: __x64_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_bdflush(const struct pt_regs *__unused);
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
ffffffff81beaa34-ffffffff81beaa6a: __x64_sys_bdflush.cold (STB_LOCAL)
ffffffff813679d0-ffffffff81367a18: __x64_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_bdflush(const struct pt_regs *__unused);
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
ffffffff81bdca63-ffffffff81bdca99: __x64_sys_bdflush.cold (STB_LOCAL)
ffffffff8136e5d0-ffffffff8136e618: __x64_sys_bdflush (STB_GLOBAL)
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
long int __x64_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c6220)
Location: kernel/sys_ni.c:410
Inline: False
```
**Symbols:**

```
ffffffff8131d21f-ffffffff8131d255: __x64_sys_bdflush.cold (STB_LOCAL)
ffffffff81318da0-ffffffff81318de5: __x64_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b4a40)
Location: kernel/sys_ni.c:410
Inline: False
```
**Symbols:**

```
ffffffff8130ddbf-ffffffff8130ddf5: __x64_sys_bdflush.cold (STB_LOCAL)
ffffffff81309990-ffffffff813099d5: __x64_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c5770)
Location: kernel/sys_ni.c:410
Inline: False
```
**Symbols:**

```
ffffffff8131acef-ffffffff8131ad25: __x64_sys_bdflush.cold (STB_LOCAL)
ffffffff81316870-ffffffff813168b5: __x64_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_bdflush(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cdbb0)
Location: kernel/sys_ni.c:410
Inline: False
```
**Symbols:**

```
ffffffff8132c995-ffffffff8132c9cb: __x64_sys_bdflush.cold (STB_LOCAL)
ffffffff813287c0-ffffffff81328805: __x64_sys_bdflush (STB_GLOBAL)
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
