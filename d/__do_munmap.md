# Function: <code>__do_munmap</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81249a40)
Location: mm/mmap.c:2724
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81249a40-ffffffff81249ea2: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125bd60)
Location: mm/mmap.c:2729
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff8125bd60-ffffffff8125c1aa: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126a450)
Location: mm/mmap.c:2734
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff8126a450-ffffffff8126a902: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129aea0)
Location: mm/mmap.c:2743
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff8129aea0-ffffffff8129b395: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a6060)
Location: mm/mmap.c:2806
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff812a6060-ffffffff812a6577: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ab3c0)
Location: mm/mmap.c:2810
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff812ab3c0-ffffffff812ab897: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ecaa0)
Location: mm/mmap.c:2796
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff812ecaa0-ffffffff812ecf98: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134fdb0)
Location: mm/mmap.c:2803
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff8134fdb0-ffffffff813502ff: __do_munmap (STB_GLOBAL)
```
</details>
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
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010301bb0)
Location: mm/mmap.c:2734
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__arm64_sys_brk
  - mm/mremap.c:__arm64_sys_mremap
```
**Symbols:**

```
ffff800010301bb0-ffff800010301ffc: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c052030c)
Location: mm/mmap.c:2734
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__se_sys_brk
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
c052030c-c0520748: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cde00)
Location: mm/mmap.c:2734
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__se_sys_brk
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
c0000000003cde00-c0000000003ce3d4: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020ed46)
Location: mm/mmap.c:2734
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__se_sys_brk
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
ffffffe00020ed46-ffffffe00020f06a: __do_munmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81262aa0)
Location: mm/mmap.c:2734
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81262aa0-ffffffff81262f52: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81254ec0)
Location: mm/mmap.c:2734
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81254ec0-ffffffff81255372: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81260840)
Location: mm/mmap.c:2734
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81260840-ffffffff81260cf2: __do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf, bool downgrade);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81270210)
Location: mm/mmap.c:2734
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81270210-ffffffff812706c2: __do_munmap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
