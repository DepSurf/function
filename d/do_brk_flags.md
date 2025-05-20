# Function: <code>do_brk_flags</code>

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
int do_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fde00)
Location: mm/mmap.c:2864
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:SyS_brk
```
**Symbols:**

```
ffffffff811fde00-ffffffff811fe127: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812163b0)
Location: mm/mmap.c:2890
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:SyS_brk
```
**Symbols:**

```
ffffffff812163b0-ffffffff812166d7: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81237180)
Location: mm/mmap.c:2945
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff81237180-ffffffff8123746f: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124aa30)
Location: mm/mmap.c:2997
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff8124aa30-ffffffff8124ad33: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125cdb0)
Location: mm/mmap.c:3003
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff8125cdb0-ffffffff8125d0f1: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126b580)
Location: mm/mmap.c:3009
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff8126b580-ffffffff8126b8c1: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129b3a0)
Location: mm/mmap.c:3019
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_brk
```
**Symbols:**

```
ffffffff8129b3a0-ffffffff8129b710: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a6580)
Location: mm/mmap.c:3082
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_brk
```
**Symbols:**

```
ffffffff812a6580-ffffffff812a68ec: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ac570)
Location: mm/mmap.c:3053
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_brk
```
**Symbols:**

```
ffffffff812ac570-ffffffff812ac891: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812edcc0)
Location: mm/mmap.c:3039
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_brk
```
**Symbols:**

```
ffffffff812edcc0-ffffffff812edfe1: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813510c0)
Location: mm/mmap.c:3039
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_brk
```
**Symbols:**

```
ffffffff813510c0-ffffffff813513de: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_brk_flags(struct ma_state *mas, struct vm_area_struct *vma, long unsigned int addr, long unsigned int len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813ca750)
Location: mm/mmap.c:2945
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_brk
```
**Symbols:**

```
ffffffff813ca750-ffffffff813caa24: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_brk_flags(struct vma_iterator *vmi, struct vm_area_struct *vma, long unsigned int addr, long unsigned int len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fed20)
Location: mm/mmap.c:3042
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_brk
```
**Symbols:**

```
ffffffff813fed20-ffffffff813ff09a: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_brk_flags(struct vma_iterator *vmi, struct vm_area_struct *vma, long unsigned int addr, long unsigned int len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142b190)
Location: mm/mmap.c:3131
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_brk
```
**Symbols:**

```
ffffffff8142b190-ffffffff8142b5e4: do_brk_flags (STB_LOCAL)
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010302d50)
Location: mm/mmap.c:3009
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__arm64_sys_brk
```
**Symbols:**

```
ffff800010302d50-ffff800010303024: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0521390)
Location: mm/mmap.c:3009
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__se_sys_brk
```
**Symbols:**

```
c0521390-c05216b8: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cf520)
Location: mm/mmap.c:3009
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__se_sys_brk
```
**Symbols:**

```
c0000000003cf520-c0000000003cf8e4: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020fa8a)
Location: mm/mmap.c:3009
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__se_sys_brk
```
**Symbols:**

```
ffffffe00020fa8a-ffffffe00020fca8: do_brk_flags (STB_LOCAL)
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81263bd0)
Location: mm/mmap.c:3009
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff81263bd0-ffffffff81263f11: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81255ff0)
Location: mm/mmap.c:3009
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff81255ff0-ffffffff81256331: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81261970)
Location: mm/mmap.c:3009
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff81261970-ffffffff81261cb1: do_brk_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head *uf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81271330)
Location: mm/mmap.c:3009
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
**Symbols:**

```
ffffffff81271330-ffffffff81271671: do_brk_flags (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int len</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int request</code>
</li>
</ul>
</details>
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
<code>struct ma_state *mas</code>
</li>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param removed. </b>
<code>struct list_head *uf</code>
</li>
<li>
<b>Param reordered. </b>
<code>addr, len, flags, uf</code> ➡️ <code>mas, vma, addr, len, flags</code>
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
<code>struct vma_iterator *vmi</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ma_state *mas</code>
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
