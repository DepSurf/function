# Function: <code>__x32_compat_sys_setsockopt</code>

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
long int __x32_compat_sys_setsockopt(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818c9510)
Location: net/compat.c:414
Inline: False
```
**Symbols:**

```
ffffffff818c9510-ffffffff818c9538: __x32_compat_sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __x32_compat_sys_setsockopt(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818f43e0)
Location: net/compat.c:418
Inline: False
```
**Symbols:**

```
ffffffff818f43e0-ffffffff818f4408: __x32_compat_sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __x32_compat_sys_setsockopt(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81953e40)
Location: net/compat.c:394
Inline: False
```
**Symbols:**

```
ffffffff81953e40-ffffffff81953e69: __x32_compat_sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __x32_compat_sys_setsockopt(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8198a390)
Location: net/compat.c:394
Inline: False
```
**Symbols:**

```
ffffffff8198a390-ffffffff8198a3b9: __x32_compat_sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __x32_compat_sys_setsockopt(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81a62720)
Location: kernel/sys_ni.c:244
Inline: False
```
**Symbols:**

```
ffffffff81a62720-ffffffff81a62749: __x32_compat_sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __x32_compat_sys_setsockopt(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:246
Inline: False
```
**Symbols:**

```
ffffffff810ce0e0-ffffffff810ce0f2: __x32_compat_sys_setsockopt (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __x32_compat_sys_setsockopt(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:247
Inline: False
```
**Symbols:**

```
ffffffff810cfc00-ffffffff810cfc12: __x32_compat_sys_setsockopt (STB_WEAK)
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
<summary>In <code>aws</code>: ✅</summary>

```c
long int __x32_compat_sys_setsockopt(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8192a200)
Location: net/compat.c:394
Inline: False
```
**Symbols:**

```
ffffffff8192a200-ffffffff8192a229: __x32_compat_sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __x32_compat_sys_setsockopt(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818e3fb0)
Location: net/compat.c:394
Inline: False
```
**Symbols:**

```
ffffffff818e3fb0-ffffffff818e3fd9: __x32_compat_sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __x32_compat_sys_setsockopt(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8197b390)
Location: net/compat.c:394
Inline: False
```
**Symbols:**

```
ffffffff8197b390-ffffffff8197b3b9: __x32_compat_sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __x32_compat_sys_setsockopt(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8199d8e0)
Location: net/compat.c:394
Inline: False
```
**Symbols:**

```
ffffffff8199d8e0-ffffffff8199d909: __x32_compat_sys_setsockopt (STB_GLOBAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
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
