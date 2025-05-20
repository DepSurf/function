# Function: <code>memremap_should_map_decrypted</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81074200)
Location: arch/x86/mm/ioremap.c:484
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff81074200-ffffffff8107428b: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81076c00)
Location: arch/x86/mm/ioremap.c:484
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff81076c00-ffffffff81076c89: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8107d290)
Location: arch/x86/mm/ioremap.c:492
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff8107d290-ffffffff8107d319: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080b40)
Location: arch/x86/mm/ioremap.c:517
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff81080b40-ffffffff81080bcc: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81081c00)
Location: arch/x86/mm/ioremap.c:539
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff81081c00-ffffffff81081c8c: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088bb0)
Location: arch/x86/mm/ioremap.c:539
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff81088bb0-ffffffff81088c29: memremap_should_map_decrypted.part.0 (STB_LOCAL)
ffffffff81088c30-ffffffff81088c77: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088df0)
Location: arch/x86/mm/ioremap.c:539
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff81088df0-ffffffff81088e69: memremap_should_map_decrypted.part.0 (STB_LOCAL)
ffffffff81088e70-ffffffff81088eb7: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81089a70)
Location: arch/x86/mm/ioremap.c:522
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff81089a70-ffffffff81089ae9: memremap_should_map_decrypted.part.0 (STB_LOCAL)
ffffffff81089af0-ffffffff81089b37: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81098f10)
Location: arch/x86/mm/ioremap.c:522
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff81098f10-ffffffff81098f89: memremap_should_map_decrypted.part.0 (STB_LOCAL)
ffffffff81098f90-ffffffff81098fd7: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810ab670)
Location: arch/x86/mm/ioremap.c:528
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff810ab670-ffffffff810ab72c: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c4fe0)
Location: arch/x86/mm/ioremap.c:537
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff810c4fe0-ffffffff810c509c: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c8770)
Location: arch/x86/mm/ioremap.c:542
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff810c8770-ffffffff810c8828: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810d0c40)
Location: arch/x86/mm/ioremap.c:542
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff810d0c40-ffffffff810d0cf8: memremap_should_map_decrypted (STB_LOCAL)
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
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080c00)
Location: arch/x86/mm/ioremap.c:539
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff81080c00-ffffffff81080c8c: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106fb50)
Location: arch/x86/mm/ioremap.c:539
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff8106fb50-ffffffff8106fbdc: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080bb0)
Location: arch/x86/mm/ioremap.c:539
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff81080bb0-ffffffff81080c3c: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool memremap_should_map_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81082cd0)
Location: arch/x86/mm/ioremap.c:539
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff81082cd0-ffffffff81082d5c: memremap_should_map_decrypted (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
