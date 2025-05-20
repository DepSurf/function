# Function: <code>dup_userfaultfd</code>

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
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812a5170)
Location: fs/userfaultfd.c:608
Inline: False
```
**Symbols:**

```
ffffffff812a5170-ffffffff812a52bd: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812c8680)
Location: fs/userfaultfd.c:652
Inline: False
```
**Symbols:**

```
ffffffff812c8680-ffffffff812c87cd: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812f1980)
Location: fs/userfaultfd.c:662
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
```
**Symbols:**

```
ffffffff812f1980-ffffffff812f1ad0: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81306340)
Location: fs/userfaultfd.c:659
Inline: False
```
**Symbols:**

```
ffffffff81306340-ffffffff8130647c: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813278c0)
Location: fs/userfaultfd.c:671
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff813278c0-ffffffff81327a06: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8133a6a0)
Location: fs/userfaultfd.c:671
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8133a6a0-ffffffff8133a7e6: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81374700)
Location: fs/userfaultfd.c:670
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81374700-ffffffff81374874: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813825b0)
Location: fs/userfaultfd.c:638
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff813825b0-ffffffff81382724: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81389630)
Location: fs/userfaultfd.c:638
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81389630-ffffffff813897ab: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813d6910)
Location: fs/userfaultfd.c:640
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff813d6910-ffffffff813d6a89: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81460210)
Location: fs/userfaultfd.c:649
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81460210-ffffffff8146037e: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814f0080)
Location: fs/userfaultfd.c:663
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff814f0080-ffffffff814f020a: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81526ef0)
Location: fs/userfaultfd.c:698
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81526ef0-ffffffff81527065: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8155bc10)
Location: fs/userfaultfd.c:693
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8155bc10-ffffffff8155bdf1: dup_userfaultfd (STB_GLOBAL)
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
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffff8000103f96e8)
Location: fs/userfaultfd.c:671
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffff8000103f96e8-ffff8000103f9860: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c05cd630)
Location: fs/userfaultfd.c:671
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
c05cd630-c05cd794: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c000000000501d50)
Location: fs/userfaultfd.c:671
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
c000000000501d50-c000000000501f28: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffe0002a8a0c)
Location: fs/userfaultfd.c:671
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffe0002a8a0c-ffffffe0002a8b1e: dup_userfaultfd (STB_GLOBAL)
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
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81332c80)
Location: fs/userfaultfd.c:671
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81332c80-ffffffff81332dc6: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813237d0)
Location: fs/userfaultfd.c:671
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff813237d0-ffffffff81323916: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81330750)
Location: fs/userfaultfd.c:671
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81330750-ffffffff81330896: dup_userfaultfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dup_userfaultfd(struct vm_area_struct *vma, struct list_head *fcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813430a0)
Location: fs/userfaultfd.c:671
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff813430a0-ffffffff813431e6: dup_userfaultfd (STB_GLOBAL)
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
