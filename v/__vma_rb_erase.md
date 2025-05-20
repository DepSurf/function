# Function: <code>__vma_rb_erase</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f0560)
Location: mm/mmap.c:405
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff811f0560-ffffffff811f0793: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fb3e0)
Location: mm/mmap.c:421
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff811fb3e0-ffffffff811fb64e: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81213910)
Location: mm/mmap.c:422
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff81213910-ffffffff81213b7e: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81234850)
Location: mm/mmap.c:431
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff81234850-ffffffff81234a9e: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81247fd0)
Location: mm/mmap.c:455
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff81247fd0-ffffffff8124821a: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125a200)
Location: mm/mmap.c:457
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff8125a200-ffffffff8125a466: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812686b0)
Location: mm/mmap.c:458
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812686b0-ffffffff812689a4: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81298f40)
Location: mm/mmap.c:461
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff81298f40-ffffffff81299223: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a4100)
Location: mm/mmap.c:461
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812a4100-ffffffff812a43e3: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a9870)
Location: mm/mmap.c:465
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812a9870-ffffffff812a9b53: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812eae70)
Location: mm/mmap.c:463
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812eae70-ffffffff812eb153: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134dbf0)
Location: mm/mmap.c:469
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff8134dbf0-ffffffff8134df00: __vma_rb_erase (STB_LOCAL)
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
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff8000102ff908)
Location: mm/mmap.c:458
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffff8000102ff908-ffff8000102ffc1c: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c051e6ac)
Location: mm/mmap.c:458
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
c051e6ac-c051e9d0: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cb8f0)
Location: mm/mmap.c:458
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
c0000000003cb8f0-c0000000003cbce0: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020d758)
Location: mm/mmap.c:458
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffe00020d758-ffffffe00020d95e: __vma_rb_erase (STB_LOCAL)
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
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81260d00)
Location: mm/mmap.c:458
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff81260d00-ffffffff81260ff4: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81253120)
Location: mm/mmap.c:458
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff81253120-ffffffff81253414: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125eaa0)
Location: mm/mmap.c:458
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff8125eaa0-ffffffff8125ed94: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126e470)
Location: mm/mmap.c:458
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff8126e470-ffffffff8126e764: __vma_rb_erase (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
