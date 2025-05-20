# Function: <code>arch_ioremap_p4d_supported</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_ioremap_p4d_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828bc863)
Location: arch/x86/mm/ioremap.c:462
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_huge_init
```
**Symbols:**

```
ffffffff828bc863-ffffffff828bc870: arch_ioremap_p4d_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_ioremap_p4d_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c2d0a)
Location: arch/x86/mm/ioremap.c:484
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_huge_init
```
**Symbols:**

```
ffffffff828c2d0a-ffffffff828c2d17: arch_ioremap_p4d_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_ioremap_p4d_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82ce6102)
Location: arch/x86/mm/ioremap.c:484
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_huge_init
```
**Symbols:**

```
ffffffff82ce6102-ffffffff82ce610f: arch_ioremap_p4d_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_ioremap_p4d_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82fd3a88)
Location: arch/x86/mm/ioremap.c:484
Inline: False
Direct callers:
  - mm/ioremap.c:ioremap_huge_init
```
**Symbols:**

```
ffffffff82fd3a88-ffffffff82fd3a95: arch_ioremap_p4d_supported (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int arch_ioremap_p4d_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff800011437c1c)
Location: arch/arm64/mm/mmu.c:935
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_huge_init
```
**Symbols:**

```
ffff800011437c1c-ffff800011437c38: arch_ioremap_p4d_supported (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int arch_ioremap_p4d_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000001356a10)
Location: arch/powerpc/mm/book3s64/radix_pgtable.c:1184
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_huge_init
```
**Symbols:**

```
c000000001356a10-c000000001356a20: arch_ioremap_p4d_supported (STB_GLOBAL)
```
</details>
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
int arch_ioremap_p4d_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828adce0)
Location: arch/x86/mm/ioremap.c:484
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_huge_init
```
**Symbols:**

```
ffffffff828adce0-ffffffff828adced: arch_ioremap_p4d_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_ioremap_p4d_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a5f53)
Location: arch/x86/mm/ioremap.c:484
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_huge_init
```
**Symbols:**

```
ffffffff828a5f53-ffffffff828a5f60: arch_ioremap_p4d_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_ioremap_p4d_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c0bdf)
Location: arch/x86/mm/ioremap.c:484
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_huge_init
```
**Symbols:**

```
ffffffff828c0bdf-ffffffff828c0bec: arch_ioremap_p4d_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_ioremap_p4d_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c3d2a)
Location: arch/x86/mm/ioremap.c:484
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_huge_init
```
**Symbols:**

```
ffffffff828c3d2a-ffffffff828c3d37: arch_ioremap_p4d_supported (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
