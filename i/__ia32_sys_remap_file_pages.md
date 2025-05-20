# Function: <code>__ia32_sys_remap_file_pages</code>

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
long int __ia32_sys_remap_file_pages(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:2817
Inline: False
```
**Symbols:**

```
ffffffff81238faf-ffffffff81238fd4: __ia32_sys_remap_file_pages.cold.41 (STB_LOCAL)
ffffffff81238570-ffffffff81238871: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:2879
Inline: False
```
**Symbols:**

```
ffffffff8124c96f-ffffffff8124c994: __ia32_sys_remap_file_pages.cold.35 (STB_LOCAL)
ffffffff8124bf30-ffffffff8124c231: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:2885
Inline: False
```
**Symbols:**

```
ffffffff8125edb7-ffffffff8125eddc: __ia32_sys_remap_file_pages.cold (STB_LOCAL)
ffffffff8125e3b0-ffffffff8125e681: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cb180)
Location: kernel/sys_ni.c:283
Inline: False
```
**Symbols:**

```
ffffffff8126d5c7-ffffffff8126d5ec: __ia32_sys_remap_file_pages.cold (STB_LOCAL)
ffffffff8126cbc0-ffffffff8126ce91: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8129cc70)
Location: kernel/sys_ni.c:283
Inline: False
```
**Symbols:**

```
ffffffff8129cc70-ffffffff8129cc94: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff812a8020)
Location: kernel/sys_ni.c:286
Inline: False
```
**Symbols:**

```
ffffffff812a8020-ffffffff812a8044: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff812adc00)
Location: kernel/sys_ni.c:292
Inline: False
```
**Symbols:**

```
ffffffff812adc00-ffffffff812adc24: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff812ef370)
Location: kernel/sys_ni.c:293
Inline: False
```
**Symbols:**

```
ffffffff812ef370-ffffffff812ef394: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813527d0)
Location: kernel/sys_ni.c:295
Inline: False
```
**Symbols:**

```
ffffffff813527d0-ffffffff81352802: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813cc810)
Location: kernel/sys_ni.c:295
Inline: False
```
**Symbols:**

```
ffffffff813cc810-ffffffff813cc842: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff814010e0)
Location: kernel/sys_ni.c:187
Inline: False
```
**Symbols:**

```
ffffffff814010e0-ffffffff81401112: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8142d720)
Location: kernel/sys_ni.c:191
Inline: False
Direct callers:
  - arch/x86/entry/syscall_32.c:ia32_sys_call
```
**Symbols:**

```
ffffffff8142d720-ffffffff8142d752: __ia32_sys_remap_file_pages (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c5500)
Location: kernel/sys_ni.c:283
Inline: False
```
**Symbols:**

```
ffffffff81265c17-ffffffff81265c3c: __ia32_sys_remap_file_pages.cold (STB_LOCAL)
ffffffff81265210-ffffffff812654e1: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b3d20)
Location: kernel/sys_ni.c:283
Inline: False
```
**Symbols:**

```
ffffffff81258037-ffffffff8125805c: __ia32_sys_remap_file_pages.cold (STB_LOCAL)
ffffffff81257630-ffffffff81257901: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c4a50)
Location: kernel/sys_ni.c:283
Inline: False
```
**Symbols:**

```
ffffffff812639b7-ffffffff812639dc: __ia32_sys_remap_file_pages.cold (STB_LOCAL)
ffffffff81262fb0-ffffffff81263281: __ia32_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cce90)
Location: kernel/sys_ni.c:283
Inline: False
```
**Symbols:**

```
ffffffff81273377-ffffffff8127339c: __ia32_sys_remap_file_pages.cold (STB_LOCAL)
ffffffff81272970-ffffffff81272c41: __ia32_sys_remap_file_pages (STB_GLOBAL)
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
