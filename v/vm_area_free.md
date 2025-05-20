# Function: <code>vm_area_free</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108bba7)
Location: kernel/fork.c:336
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff8108bd10-ffffffff8108bd2a: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81093590)
Location: kernel/fork.c:355
Inline: True
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81093590-ffffffff810935aa: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109799f)
Location: kernel/fork.c:361
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81097cb0-ffffffff81097cca: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e05f)
Location: kernel/fork.c:370
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff8109e370-ffffffff8109e38a: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a57d4)
Location: kernel/fork.c:374
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - fs/exec.c:__bprm_mm_init
```
**Symbols:**

```
ffffffff810a5960-ffffffff810a597a: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0fcc)
Location: kernel/fork.c:377
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - fs/exec.c:__bprm_mm_init
```
**Symbols:**

```
ffffffff810a1150-ffffffff810a116a: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1d43)
Location: kernel/fork.c:378
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - fs/exec.c:__bprm_mm_init
```
**Symbols:**

```
ffffffff810a1ec0-ffffffff810a1eda: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b391b)
Location: kernel/fork.c:378
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - fs/exec.c:__bprm_mm_init
```
**Symbols:**

```
ffffffff810b2ca0-ffffffff810b2cba: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c8f40)
Location: kernel/fork.c:489
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810c8f40-ffffffff810c8fa4: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e6400)
Location: kernel/fork.c:487
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
  - mm/mmap.c:remove_vma
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810e6400-ffffffff810e645d: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f29ea)
Location: kernel/fork.c:548
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_complete
  - mm/mmap.c:remove_vma
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810f1db0-ffffffff810f1dcf: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fb6a0)
Location: kernel/fork.c:528
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_complete
  - mm/mmap.c:remove_vma
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810fba30-ffffffff810fba4f: vm_area_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f2c0c)
Location: kernel/fork.c:370
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffff8000100f2f00-ffff8000100f2f34: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c035153c)
Location: kernel/fork.c:370
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
c035178c-c03517b8: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0000000001388a4)
Location: kernel/fork.c:370
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
c000000000138c60-c000000000138ca0: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bf826)
Location: kernel/fork.c:370
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
ffffffe0000bfaf8-ffffffe0000bfb2a: vm_area_free (STB_GLOBAL)
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
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109797f)
Location: kernel/fork.c:370
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81097c90-ffffffff81097caa: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810863ff)
Location: kernel/fork.c:370
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81086700-ffffffff8108671a: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109792f)
Location: kernel/fork.c:370
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81097c40-ffffffff81097c5a: vm_area_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void vm_area_free(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f52f)
Location: kernel/fork.c:370
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff8109f840-ffffffff8109f85a: vm_area_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
