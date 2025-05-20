# Function: <code>vm_area_alloc</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b5f0)
Location: kernel/fork.c:316
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff8108b5f0-ffffffff8108b634: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810934e0)
Location: kernel/fork.c:334
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff810934e0-ffffffff81093537: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810975f0)
Location: kernel/fork.c:340
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff810975f0-ffffffff81097647: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109dcb0)
Location: kernel/fork.c:349
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff8109dcb0-ffffffff8109dd07: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a52c0)
Location: kernel/fork.c:352
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - fs/exec.c:__bprm_mm_init
```
**Symbols:**

```
ffffffff810a52c0-ffffffff810a531a: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a09e0)
Location: kernel/fork.c:349
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - fs/exec.c:__bprm_mm_init
```
**Symbols:**

```
ffffffff810a09e0-ffffffff810a0a3a: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1770)
Location: kernel/fork.c:350
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - fs/exec.c:__bprm_mm_init
```
**Symbols:**

```
ffffffff810a1770-ffffffff810a17ca: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b2ba0)
Location: kernel/fork.c:350
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - fs/exec.c:__bprm_mm_init
```
**Symbols:**

```
ffffffff810b2ba0-ffffffff810b2bfa: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c8da0)
Location: kernel/fork.c:460
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810c8da0-ffffffff810c8e06: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e6260)
Location: kernel/fork.c:459
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810e6260-ffffffff810e62c0: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f1ae0)
Location: kernel/fork.c:486
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810f1ae0-ffffffff810f1b8f: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fae70)
Location: kernel/fork.c:466
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810fae70-ffffffff810faf1f: vm_area_alloc (STB_GLOBAL)
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
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f28a8)
Location: kernel/fork.c:349
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffff8000100f28a8-ffff8000100f2934: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c035119c)
Location: kernel/fork.c:349
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
c035119c-c0351200: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000138450)
Location: kernel/fork.c:349
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
c000000000138450-c0000000001384dc: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bf4fc)
Location: kernel/fork.c:349
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
ffffffe0000bf4fc-ffffffe0000bf560: vm_area_alloc (STB_GLOBAL)
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
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810975d0)
Location: kernel/fork.c:349
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff810975d0-ffffffff81097627: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086050)
Location: kernel/fork.c:349
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff81086050-ffffffff810860a7: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097580)
Location: kernel/fork.c:349
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff81097580-ffffffff810975d7: vm_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f180)
Location: kernel/fork.c:349
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
**Symbols:**

```
ffffffff8109f180-ffffffff8109f1d7: vm_area_alloc (STB_GLOBAL)
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
