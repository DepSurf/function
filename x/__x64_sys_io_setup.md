# Function: <code>__x64_sys_io_setup</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f5a20)
Location: fs/aio.c:1280
Inline: False
```
**Symbols:**

```
ffffffff812f5a20-ffffffff812f5af5: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8130ab10)
Location: fs/aio.c:1312
Inline: False
```
**Symbols:**

```
ffffffff8130ab10-ffffffff8130abe5: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8132cd70)
Location: fs/aio.c:1312
Inline: False
```
**Symbols:**

```
ffffffff8132cd70-ffffffff8132ce49: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c96a0)
Location: kernel/sys_ni.c:39
Inline: False
```
**Symbols:**

```
ffffffff8133fbc0-ffffffff8133fc99: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810d1aa0)
Location: kernel/sys_ni.c:39
Inline: True
```
**Symbols:**

```
ffffffff81379680-ffffffff81379759: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cc540)
Location: kernel/sys_ni.c:39
Inline: True
```
**Symbols:**

```
ffffffff81387300-ffffffff813873e4: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810ce020)
Location: kernel/sys_ni.c:39
Inline: True
```
**Symbols:**

```
ffffffff8138e4c0-ffffffff8138e5a5: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810e1260)
Location: kernel/sys_ni.c:39
Inline: True
```
**Symbols:**

```
ffffffff813dbc40-ffffffff813dbd22: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810fb530)
Location: kernel/sys_ni.c:39
Inline: True
```
**Symbols:**

```
ffffffff81463e50-ffffffff81463f3c: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8111e490)
Location: kernel/sys_ni.c:39
Inline: True
```
**Symbols:**

```
ffffffff814f4150-ffffffff814f423c: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8112b700)
Location: kernel/sys_ni.c:39
Inline: True
```
**Symbols:**

```
ffffffff8152af20-ffffffff8152b00c: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81135e50)
Location: kernel/sys_ni.c:39
Inline: True
Direct callers:
  - arch/x86/entry/syscall_64.c:x64_sys_call
```
**Symbols:**

```
ffffffff8155fdf0-ffffffff8155fedc: __x64_sys_io_setup (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c3a20)
Location: kernel/sys_ni.c:39
Inline: False
```
**Symbols:**

```
ffffffff813381a0-ffffffff81338279: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b2240)
Location: kernel/sys_ni.c:39
Inline: False
```
**Symbols:**

```
ffffffff81328ed0-ffffffff81328fa9: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c2f70)
Location: kernel/sys_ni.c:39
Inline: False
```
**Symbols:**

```
ffffffff81335c70-ffffffff81335d49: __x64_sys_io_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __x64_sys_io_setup(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cb3b0)
Location: kernel/sys_ni.c:39
Inline: False
```
**Symbols:**

```
ffffffff81348d10-ffffffff81348e00: __x64_sys_io_setup (STB_GLOBAL)
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
