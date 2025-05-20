# Function: <code>__x64_sys_remap_file_pages</code>

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
long int __x64_sys_remap_file_pages(const struct pt_regs *regs);
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
ffffffff81238fd4-ffffffff81238ff9: __x64_sys_remap_file_pages.cold.42 (STB_LOCAL)
ffffffff81238880-ffffffff81238b77: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *regs);
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
ffffffff8124c994-ffffffff8124c9b9: __x64_sys_remap_file_pages.cold.36 (STB_LOCAL)
ffffffff8124c240-ffffffff8124c537: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *regs);
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
ffffffff8125eddc-ffffffff8125ee01: __x64_sys_remap_file_pages.cold (STB_LOCAL)
ffffffff8125e690-ffffffff8125e963: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cb160)
Location: kernel/sys_ni.c:283
Inline: False
```
**Symbols:**

```
ffffffff8126d5ec-ffffffff8126d611: __x64_sys_remap_file_pages.cold (STB_LOCAL)
ffffffff8126cea0-ffffffff8126d173: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8129cc40)
Location: kernel/sys_ni.c:283
Inline: False
```
**Symbols:**

```
ffffffff8129cc40-ffffffff8129cc67: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff812a7ff0)
Location: kernel/sys_ni.c:286
Inline: False
```
**Symbols:**

```
ffffffff812a7ff0-ffffffff812a8017: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff812adbd0)
Location: kernel/sys_ni.c:292
Inline: False
```
**Symbols:**

```
ffffffff812adbd0-ffffffff812adbf7: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff812ef340)
Location: kernel/sys_ni.c:293
Inline: False
```
**Symbols:**

```
ffffffff812ef340-ffffffff812ef367: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81352790)
Location: kernel/sys_ni.c:295
Inline: False
```
**Symbols:**

```
ffffffff81352790-ffffffff813527c6: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813cc7c0)
Location: kernel/sys_ni.c:295
Inline: False
```
**Symbols:**

```
ffffffff813cc7c0-ffffffff813cc7f6: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81401090)
Location: kernel/sys_ni.c:187
Inline: False
```
**Symbols:**

```
ffffffff81401090-ffffffff814010c6: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8142d6d0)
Location: kernel/sys_ni.c:191
Inline: False
Direct callers:
  - arch/x86/entry/syscall_64.c:x64_sys_call
```
**Symbols:**

```
ffffffff8142d6d0-ffffffff8142d706: __x64_sys_remap_file_pages (STB_GLOBAL)
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
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c54e0)
Location: kernel/sys_ni.c:283
Inline: False
```
**Symbols:**

```
ffffffff81265c3c-ffffffff81265c61: __x64_sys_remap_file_pages.cold (STB_LOCAL)
ffffffff812654f0-ffffffff812657c3: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b3d00)
Location: kernel/sys_ni.c:283
Inline: False
```
**Symbols:**

```
ffffffff8125805c-ffffffff81258081: __x64_sys_remap_file_pages.cold (STB_LOCAL)
ffffffff81257910-ffffffff81257be3: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c4a30)
Location: kernel/sys_ni.c:283
Inline: False
```
**Symbols:**

```
ffffffff812639dc-ffffffff81263a01: __x64_sys_remap_file_pages.cold (STB_LOCAL)
ffffffff81263290-ffffffff81263563: __x64_sys_remap_file_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cce70)
Location: kernel/sys_ni.c:283
Inline: False
```
**Symbols:**

```
ffffffff8127339c-ffffffff812733c1: __x64_sys_remap_file_pages.cold (STB_LOCAL)
ffffffff81272c50-ffffffff81272f23: __x64_sys_remap_file_pages (STB_GLOBAL)
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
