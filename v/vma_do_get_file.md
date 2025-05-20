# Function: <code>vma_do_get_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff811b9fe0)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:copy_vma
```
**Symbols:**

```
ffffffff811b9fe0-ffffffff811ba00d: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff811d4400)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:SyS_remap_file_pages
```
**Symbols:**

```
ffffffff811d4400-ffffffff811d442d: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff811e4450)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:SyS_remap_file_pages
```
**Symbols:**

```
ffffffff811e4450-ffffffff811e447d: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff811ee8b0)
Location: mm/prfile.c:46
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff811ee8b0-ffffffff811ee8dd: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81204d20)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:SyS_remap_file_pages
```
**Symbols:**

```
ffffffff81204d20-ffffffff81204d4d: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81225bc0)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81225bc0-ffffffff81225bed: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81239280)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81239280-ffffffff812392ad: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff8124a2e0)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff8124a2e0-ffffffff8124a30d: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81258720)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81258720-ffffffff8125874d: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81286f30)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81286f30-ffffffff81286f5d: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81291250)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81291250-ffffffff8129127d: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff812d6fd0)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff812d6fd0-ffffffff812d6ffd: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81336830)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81336830-ffffffff81336867: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff813adaa0)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff813adaa0-ffffffff813adad1: vma_do_get_file (STB_GLOBAL)
```
</details>
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
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffff8000102f0640)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffff8000102f0640-ffff8000102f06d0: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (c0513c10)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
c0513c10-c0513c74: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (c0000000003b4ff0)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
c0000000003b4ff0-c0000000003b503c: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffe000203ef2)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffe000203ef2-ffffffe000203f2c: vma_do_get_file (STB_GLOBAL)
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
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81250d70)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81250d70-ffffffff81250d9d: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81243cb0)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81243cb0-ffffffff81243cdd: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff8124eb10)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff8124eb10-ffffffff8124eb3d: vma_do_get_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vma_do_get_file(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff8125e490)
Location: mm/prfile.c:47
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff8125e490-ffffffff8125e4bd: vma_do_get_file (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
