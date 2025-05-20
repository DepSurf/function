# Function: <code>userfaultfd_unmap_complete</code>

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
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812a5610)
Location: fs/userfaultfd.c:780
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:SyS_brk
  - mm/mmap.c:SyS_brk
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff812a5610-ffffffff812a5704: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812c8b20)
Location: fs/userfaultfd.c:824
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:SyS_brk
  - mm/mmap.c:SyS_brk
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff812c8b20-ffffffff812c8c14: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812f1e40)
Location: fs/userfaultfd.c:839
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff812f1e40-ffffffff812f1f34: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81306800)
Location: fs/userfaultfd.c:844
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81306800-ffffffff813068f4: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81327da0)
Location: fs/userfaultfd.c:856
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81327da0-ffffffff81327e9e: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8133ab80)
Location: fs/userfaultfd.c:856
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff8133ab80-ffffffff8133ac7e: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81374c80)
Location: fs/userfaultfd.c:855
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81374c80-ffffffff81374d7c: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81382b50)
Location: fs/userfaultfd.c:823
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81382b50-ffffffff81382c4c: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81389bc0)
Location: fs/userfaultfd.c:823
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81389bc0-ffffffff81389cbc: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813d6ea0)
Location: fs/userfaultfd.c:824
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff813d6ea0-ffffffff813d6f9c: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81460830)
Location: fs/userfaultfd.c:833
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81460830-ffffffff8146093b: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814f0750)
Location: fs/userfaultfd.c:849
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff814f0750-ffffffff814f085b: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81527530)
Location: fs/userfaultfd.c:879
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81527530-ffffffff8152763b: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8155c330)
Location: fs/userfaultfd.c:876
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff8155c330-ffffffff8155c43b: userfaultfd_unmap_complete (STB_GLOBAL)
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
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffff8000103f9c60)
Location: fs/userfaultfd.c:856
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__arm64_sys_brk
  - mm/mmap.c:__arm64_sys_brk
  - mm/mremap.c:__arm64_sys_mremap
  - mm/mremap.c:__arm64_sys_mremap
```
**Symbols:**

```
ffff8000103f9c60-ffff8000103f9d44: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c05cdb4c)
Location: fs/userfaultfd.c:856
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__se_sys_brk
  - mm/mmap.c:__se_sys_brk
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
c05cdb4c-c05cdc30: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c000000000502480)
Location: fs/userfaultfd.c:856
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__se_sys_brk
  - mm/mmap.c:__se_sys_brk
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
c000000000502480-c0000000005025e0: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffe0002a8e4a)
Location: fs/userfaultfd.c:856
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__se_sys_brk
  - mm/mmap.c:__se_sys_brk
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
ffffffe0002a8e4a-ffffffe0002a8ef4: userfaultfd_unmap_complete (STB_GLOBAL)
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
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81333160)
Location: fs/userfaultfd.c:856
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81333160-ffffffff8133325e: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81323cb0)
Location: fs/userfaultfd.c:856
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81323cb0-ffffffff81323dae: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81330c30)
Location: fs/userfaultfd.c:856
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81330c30-ffffffff81330d2e: userfaultfd_unmap_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct *mm, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81343580)
Location: fs/userfaultfd.c:856
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81343580-ffffffff8134367e: userfaultfd_unmap_complete (STB_GLOBAL)
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
