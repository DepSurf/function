# Function: <code>__x64_sys_geteuid16</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_geteuid16();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8112d7e0)
Location: kernel/uid16.c:208
Inline: True
```
**Symbols:**

```
ffffffff8112d7e0-ffffffff8112d836: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_geteuid16();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811390d0)
Location: kernel/uid16.c:208
Inline: True
```
**Symbols:**

```
ffffffff811390d0-ffffffff81139126: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_geteuid16();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811442c0)
Location: kernel/uid16.c:208
Inline: True
```
**Symbols:**

```
ffffffff811442c0-ffffffff81144316: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cc0e0)
Location: kernel/sys_ni.c:433
Inline: True
```
**Symbols:**

```
ffffffff8114fda0-ffffffff8114fdf6: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:456
Inline: False
```
**Symbols:**

```
ffffffff81160580-ffffffff811605dc: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:457
Inline: False
```
**Symbols:**

```
ffffffff8115c510-ffffffff8115c56c: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:463
Inline: False
```
**Symbols:**

```
ffffffff8115d730-ffffffff8115d78c: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:460
Inline: False
```
**Symbols:**

```
ffffffff81182a30-ffffffff81182a8c: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:463
Inline: False
```
**Symbols:**

```
ffffffff811b9330-ffffffff811b939c: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:463
Inline: False
```
**Symbols:**

```
ffffffff811fa890-ffffffff811fa8fc: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:356
Inline: False
```
**Symbols:**

```
ffffffff8120fc30-ffffffff8120fc9c: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:375
Inline: False
```
**Symbols:**

```
ffffffff81227200-ffffffff8122726c: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c6460)
Location: kernel/sys_ni.c:433
Inline: True
```
**Symbols:**

```
ffffffff811483c0-ffffffff81148416: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b4c80)
Location: kernel/sys_ni.c:433
Inline: True
```
**Symbols:**

```
ffffffff8113b670-ffffffff8113b6c6: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c59b0)
Location: kernel/sys_ni.c:433
Inline: True
```
**Symbols:**

```
ffffffff81146270-ffffffff811462c6: __x64_sys_geteuid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_geteuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cddf0)
Location: kernel/sys_ni.c:433
Inline: True
```
**Symbols:**

```
ffffffff81152e80-ffffffff81152ed6: __x64_sys_geteuid16 (STB_GLOBAL)
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
