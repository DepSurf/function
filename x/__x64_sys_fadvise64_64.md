# Function: <code>__x64_sys_fadvise64_64</code>

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
long int __x64_sys_fadvise64_64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81244990)
Location: mm/fadvise.c:193
Inline: False
```
**Symbols:**

```
ffffffff81244990-ffffffff812449b2: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812062f0)
Location: mm/fadvise.c:207
Inline: False
```
**Symbols:**

```
ffffffff812062f0-ffffffff81206312: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff8121d670)
Location: mm/fadvise.c:207
Inline: False
```
**Symbols:**

```
ffffffff8121d670-ffffffff8121d692: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810caea0)
Location: kernel/sys_ni.c:270
Inline: False
```
**Symbols:**

```
ffffffff8122b050-ffffffff8122b072: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81257e20)
Location: kernel/sys_ni.c:270
Inline: True
```
**Symbols:**

```
ffffffff81257e20-ffffffff81257e42: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff812626f0)
Location: kernel/sys_ni.c:272
Inline: True
```
**Symbols:**

```
ffffffff812626f0-ffffffff81262712: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81267180)
Location: kernel/sys_ni.c:278
Inline: True
```
**Symbols:**

```
ffffffff81267180-ffffffff812671a0: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff812a3bc0)
Location: kernel/sys_ni.c:278
Inline: True
```
**Symbols:**

```
ffffffff812a3bc0-ffffffff812a3be0: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff812fbb00)
Location: kernel/sys_ni.c:279
Inline: True
```
**Symbols:**

```
ffffffff812fbb00-ffffffff812fbb2c: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81365c90)
Location: kernel/sys_ni.c:279
Inline: True
```
**Symbols:**

```
ffffffff81365c90-ffffffff81365cbc: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81398170)
Location: kernel/sys_ni.c:171
Inline: True
```
**Symbols:**

```
ffffffff81398170-ffffffff8139819c: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813c1fa0)
Location: kernel/sys_ni.c:172
Inline: True
```
**Symbols:**

```
ffffffff813c1fa0-ffffffff813c1fcc: __x64_sys_fadvise64_64 (STB_GLOBAL)
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
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c5220)
Location: kernel/sys_ni.c:270
Inline: False
```
**Symbols:**

```
ffffffff812236a0-ffffffff812236c2: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b3a40)
Location: kernel/sys_ni.c:270
Inline: False
```
**Symbols:**

```
ffffffff81216850-ffffffff81216872: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c4770)
Location: kernel/sys_ni.c:270
Inline: False
```
**Symbols:**

```
ffffffff81221440-ffffffff81221462: __x64_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810ccbb0)
Location: kernel/sys_ni.c:270
Inline: False
```
**Symbols:**

```
ffffffff81230600-ffffffff81230622: __x64_sys_fadvise64_64 (STB_GLOBAL)
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
