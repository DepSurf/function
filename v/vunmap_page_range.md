# Function: <code>vunmap_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ce240)
Location: mm/vmalloc.c:104
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:remove_vm_area
```
**Symbols:**

```
ffffffff811ce240-ffffffff811ce565: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811eade0)
Location: mm/vmalloc.c:105
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff811eade0-ffffffff811eb156: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fc040)
Location: mm/vmalloc.c:105
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff811fc040-ffffffff811fc3b6: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81206d20)
Location: mm/vmalloc.c:121
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81206d20-ffffffff81207084: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121fda0)
Location: mm/vmalloc.c:119
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff8121fda0-ffffffff81220176: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81241030)
Location: mm/vmalloc.c:119
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81241030-ffffffff812413a8: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81255710)
Location: mm/vmalloc.c:119
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81255710-ffffffff81255a91: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff81267dfb)
Location: mm/vmalloc.c:122
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81267a70-ffffffff81267dfd: vunmap_page_range (STB_LOCAL)
ffffffff8126bb26-ffffffff8126bb51: vunmap_page_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812763c0)
Location: mm/vmalloc.c:122
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff812763c0-ffffffff81276748: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030c638)
Location: mm/vmalloc.c:122
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffff80001030c638-ffff80001030c864: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0528224)
Location: mm/vmalloc.c:122
Inline: True
Direct callers:
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:free_unmap_vmap_area
```
**Symbols:**

```
c0528224-c0528374: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dc9c0)
Location: mm/vmalloc.c:122
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
c0000000003dc9c0-c0000000003dd068: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe0002155c4)
Location: mm/vmalloc.c:122
Inline: True
Direct callers:
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffe0002155c4-ffffffe000215728: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126ea10)
Location: mm/vmalloc.c:122
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff8126ea10-ffffffff8126ed98: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81260390)
Location: mm/vmalloc.c:122
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81260390-ffffffff812606f2: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126c7b0)
Location: mm/vmalloc.c:122
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff8126c7b0-ffffffff8126cb38: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127c2f0)
Location: mm/vmalloc.c:122
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff8127c2f0-ffffffff8127c678: vunmap_page_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
