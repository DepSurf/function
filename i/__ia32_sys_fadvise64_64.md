# Function: <code>__ia32_sys_fadvise64_64</code>

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
long int __ia32_sys_fadvise64_64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812449c0)
Location: mm/fadvise.c:193
Inline: False
```
**Symbols:**

```
ffffffff812449c0-ffffffff812449e0: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81206320)
Location: mm/fadvise.c:207
Inline: False
```
**Symbols:**

```
ffffffff81206320-ffffffff81206340: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff8121d6a0)
Location: mm/fadvise.c:207
Inline: False
```
**Symbols:**

```
ffffffff8121d6a0-ffffffff8121d6c0: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810caec0)
Location: kernel/sys_ni.c:270
Inline: False
```
**Symbols:**

```
ffffffff8122b080-ffffffff8122b0a0: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81257e50)
Location: kernel/sys_ni.c:270
Inline: True
```
**Symbols:**

```
ffffffff81257e50-ffffffff81257e70: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81262720)
Location: kernel/sys_ni.c:272
Inline: True
```
**Symbols:**

```
ffffffff81262720-ffffffff81262740: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff812671a0)
Location: kernel/sys_ni.c:278
Inline: True
```
**Symbols:**

```
ffffffff812671a0-ffffffff812671be: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff812a3be0)
Location: kernel/sys_ni.c:278
Inline: True
```
**Symbols:**

```
ffffffff812a3be0-ffffffff812a3bfe: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff812fbb30)
Location: kernel/sys_ni.c:279
Inline: True
```
**Symbols:**

```
ffffffff812fbb30-ffffffff812fbb5a: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81365cd0)
Location: kernel/sys_ni.c:279
Inline: True
```
**Symbols:**

```
ffffffff81365cd0-ffffffff81365cfa: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813981b0)
Location: kernel/sys_ni.c:171
Inline: True
```
**Symbols:**

```
ffffffff813981b0-ffffffff813981da: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813c1fe0)
Location: kernel/sys_ni.c:172
Inline: True
```
**Symbols:**

```
ffffffff813c1fe0-ffffffff813c200a: __ia32_sys_fadvise64_64 (STB_GLOBAL)
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
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c5240)
Location: kernel/sys_ni.c:270
Inline: False
```
**Symbols:**

```
ffffffff812236d0-ffffffff812236f0: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b3a60)
Location: kernel/sys_ni.c:270
Inline: False
```
**Symbols:**

```
ffffffff81216880-ffffffff812168a0: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c4790)
Location: kernel/sys_ni.c:270
Inline: False
```
**Symbols:**

```
ffffffff81221470-ffffffff81221490: __ia32_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __ia32_sys_fadvise64_64(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810ccbd0)
Location: kernel/sys_ni.c:270
Inline: False
```
**Symbols:**

```
ffffffff81230630-ffffffff81230650: __ia32_sys_fadvise64_64 (STB_GLOBAL)
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
