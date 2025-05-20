# Function: <code>task_size_64bit</code>

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
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81077ed0)
Location: arch/x86/mm/mmap.c:47
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff81077ed0-ffffffff81077ee5: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff8107a940)
Location: arch/x86/mm/mmap.c:47
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff8107a940-ffffffff8107a955: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81081280)
Location: arch/x86/mm/mmap.c:47
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff81081280-ffffffff81081295: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81084ee0)
Location: arch/x86/mm/mmap.c:34
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff81084ee0-ffffffff81084ef5: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81085bd0)
Location: arch/x86/mm/mmap.c:34
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff81085bd0-ffffffff81085be5: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810893e6)
Location: arch/x86/mm/mmap.c:36
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff810892f0-ffffffff81089330: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810895c6)
Location: arch/x86/mm/mmap.c:36
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff810894d0-ffffffff81089510: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff8108a1f0)
Location: arch/x86/mm/mmap.c:36
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff8108a1f0-ffffffff8108a213: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81099730)
Location: arch/x86/mm/mmap.c:36
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff81099730-ffffffff81099753: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810ac610)
Location: arch/x86/mm/mmap.c:36
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff810ac610-ffffffff810ac639: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810c6660)
Location: arch/x86/mm/mmap.c:36
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff810c6660-ffffffff810c6689: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810c9df0)
Location: arch/x86/mm/mmap.c:36
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff810c9df0-ffffffff810c9e19: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810d2250)
Location: arch/x86/mm/mmap.c:36
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff810d2250-ffffffff810d2279: task_size_64bit (STB_GLOBAL)
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
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81084bd0)
Location: arch/x86/mm/mmap.c:34
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff81084bd0-ffffffff81084be5: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810738a0)
Location: arch/x86/mm/mmap.c:34
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff810738a0-ffffffff810738b5: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81084b80)
Location: arch/x86/mm/mmap.c:34
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff81084b80-ffffffff81084b95: task_size_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int task_size_64bit(int full_addr_space);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81086cd0)
Location: arch/x86/mm/mmap.c:34
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff81086cd0-ffffffff81086ce5: task_size_64bit (STB_GLOBAL)
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
