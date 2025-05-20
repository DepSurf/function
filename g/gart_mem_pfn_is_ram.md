# Function: <code>gart_mem_pfn_is_ram</code>

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
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107b410)
Location: arch/x86/kernel/aperture_64.c:70
Inline: False
```
**Symbols:**

```
ffffffff8107b410-ffffffff8107b446: gart_mem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107c500)
Location: arch/x86/kernel/aperture_64.c:70
Inline: False
```
**Symbols:**

```
ffffffff8107c500-ffffffff8107c536: gart_mem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81083b00)
Location: arch/x86/kernel/aperture_64.c:70
Inline: False
```
**Symbols:**

```
ffffffff81083b00-ffffffff81083b36: gart_mem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff810850f0)
Location: arch/x86/kernel/aperture_64.c:70
Inline: False
```
**Symbols:**

```
ffffffff810850f0-ffffffff81085126: gart_mem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81085e20)
Location: arch/x86/kernel/aperture_64.c:70
Inline: False
```
**Symbols:**

```
ffffffff81085e20-ffffffff81085e56: gart_mem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81094f10)
Location: arch/x86/kernel/aperture_64.c:70
Inline: False
```
**Symbols:**

```
ffffffff81094f10-ffffffff81094f46: gart_mem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff810a7265)
Location: arch/x86/kernel/aperture_64.c:70
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_oldmem_pfn_is_ram
```
**Symbols:**

```
ffffffff810a7210-ffffffff810a7251: gart_mem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff810c0555)
Location: arch/x86/kernel/aperture_64.c:70
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_oldmem_pfn_is_ram
```
**Symbols:**

```
ffffffff810c04f0-ffffffff810c0531: gart_mem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff810c3c35)
Location: arch/x86/kernel/aperture_64.c:70
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_oldmem_pfn_is_ram
```
**Symbols:**

```
ffffffff810c3bd0-ffffffff810c3c11: gart_mem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff810cc075)
Location: arch/x86/kernel/aperture_64.c:70
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_oldmem_pfn_is_ram
```
**Symbols:**

```
ffffffff810cc010-ffffffff810cc051: gart_mem_pfn_is_ram (STB_LOCAL)
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
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107b500)
Location: arch/x86/kernel/aperture_64.c:70
Inline: False
```
**Symbols:**

```
ffffffff8107b500-ffffffff8107b536: gart_mem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8106ac30)
Location: arch/x86/kernel/aperture_64.c:70
Inline: False
```
**Symbols:**

```
ffffffff8106ac30-ffffffff8106ac66: gart_mem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107b4b0)
Location: arch/x86/kernel/aperture_64.c:70
Inline: False
```
**Symbols:**

```
ffffffff8107b4b0-ffffffff8107b4e6: gart_mem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gart_mem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107d5b0)
Location: arch/x86/kernel/aperture_64.c:70
Inline: False
```
**Symbols:**

```
ffffffff8107d5b0-ffffffff8107d5e6: gart_mem_pfn_is_ram (STB_LOCAL)
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
