# Function: <code>userfaultfd_unmap_prep</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812a5500)
Location: fs/userfaultfd.c:754
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
```
**Symbols:**

```
ffffffff812a5500-ffffffff812a5602: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812c8a10)
Location: fs/userfaultfd.c:798
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
```
**Symbols:**

```
ffffffff812c8a10-ffffffff812c8b12: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812f1d20)
Location: fs/userfaultfd.c:812
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
```
**Symbols:**

```
ffffffff812f1d20-ffffffff812f1e33: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813066e0)
Location: fs/userfaultfd.c:817
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff813066e0-ffffffff813067f3: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81327c90)
Location: fs/userfaultfd.c:829
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff81327c90-ffffffff81327d9b: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8133aa70)
Location: fs/userfaultfd.c:829
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff8133aa70-ffffffff8133ab7b: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81374b50)
Location: fs/userfaultfd.c:828
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff81374b50-ffffffff81374c79: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81382a20)
Location: fs/userfaultfd.c:796
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff81382a20-ffffffff81382b49: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81389a90)
Location: fs/userfaultfd.c:796
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff81389a90-ffffffff81389bb9: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813d6d70)
Location: fs/userfaultfd.c:797
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff813d6d70-ffffffff813d6e99: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814606e0)
Location: fs/userfaultfd.c:806
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff814606e0-ffffffff81460828: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct mm_struct *mm, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814f05c0)
Location: fs/userfaultfd.c:820
Inline: False
Direct callers:
  - mm/mmap.c:do_mas_align_munmap
```
**Symbols:**

```
ffffffff814f05c0-ffffffff814f0735: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81527410)
Location: fs/userfaultfd.c:855
Inline: False
Direct callers:
  - mm/mmap.c:do_vmi_align_munmap
```
**Symbols:**

```
ffffffff81527410-ffffffff8152751a: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8155c1e0)
Location: fs/userfaultfd.c:852
Inline: False
Direct callers:
  - mm/mmap.c:do_vmi_align_munmap
```
**Symbols:**

```
ffffffff8155c1e0-ffffffff8155c319: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffff8000103f9b30)
Location: fs/userfaultfd.c:829
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffff8000103f9b30-ffff8000103f9c5c: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c05cda30)
Location: fs/userfaultfd.c:829
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
c05cda30-c05cdb4c: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c0000000005022d0)
Location: fs/userfaultfd.c:829
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
c0000000005022d0-c000000000502480: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffe0002a8d54)
Location: fs/userfaultfd.c:829
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffe0002a8d54-ffffffe0002a8e4a: userfaultfd_unmap_prep (STB_GLOBAL)
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
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81333050)
Location: fs/userfaultfd.c:829
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff81333050-ffffffff8133315b: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81323ba0)
Location: fs/userfaultfd.c:829
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff81323ba0-ffffffff81323cab: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81330b20)
Location: fs/userfaultfd.c:829
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff81330b20-ffffffff81330c2b: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int userfaultfd_unmap_prep(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *unmaps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81343470)
Location: fs/userfaultfd.c:829
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff81343470-ffffffff8134357b: userfaultfd_unmap_prep (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
