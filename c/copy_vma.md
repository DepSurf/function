# Function: <code>copy_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c7f00)
Location: mm/mmap.c:2926
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff811c7f00-ffffffff811c8177: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e27d0)
Location: mm/mmap.c:2862
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff811e27d0-ffffffff811e2a5e: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f27a0)
Location: mm/mmap.c:3015
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff811f27a0-ffffffff811f2a2e: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fd740)
Location: mm/mmap.c:3069
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff811fd740-ffffffff811fd9bf: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81215ce0)
Location: mm/mmap.c:3112
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff81215ce0-ffffffff81215f62: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81236b20)
Location: mm/mmap.c:3169
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff81236b20-ffffffff81236d75: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124a3d0)
Location: mm/mmap.c:3213
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff8124a3d0-ffffffff8124a62f: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125c710)
Location: mm/mmap.c:3219
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff8125c710-ffffffff8125c99a: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126ae70)
Location: mm/mmap.c:3225
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff8126ae70-ffffffff8126b0fa: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129d090)
Location: mm/mmap.c:3237
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff8129d090-ffffffff8129d31a: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a8490)
Location: mm/mmap.c:3295
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff812a8490-ffffffff812a871a: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812abea0)
Location: mm/mmap.c:3266
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff812abea0-ffffffff812ac106: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ed5a0)
Location: mm/mmap.c:3246
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff812ed5a0-ffffffff812ed823: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81350940)
Location: mm/mmap.c:3239
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff81350940-ffffffff81350bc0: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813ca370)
Location: mm/mmap.c:3185
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff813ca370-ffffffff813ca5d4: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fe8e0)
Location: mm/mmap.c:3278
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff813fe8e0-ffffffff813febaa: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142ad70)
Location: mm/mmap.c:3372
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff8142ad70-ffffffff8142b018: copy_vma (STB_GLOBAL)
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
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff8000103025b0)
Location: mm/mmap.c:3225
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffff8000103025b0-ffff8000103027d4: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0520c6c)
Location: mm/mmap.c:3225
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
c0520c6c-c0520e94: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003ceb20)
Location: mm/mmap.c:3225
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
c0000000003ceb20-c0000000003cee30: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020f4c4)
Location: mm/mmap.c:3225
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffe00020f4c4-ffffffe00020f652: copy_vma (STB_GLOBAL)
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
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812634c0)
Location: mm/mmap.c:3225
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff812634c0-ffffffff8126374a: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812558e0)
Location: mm/mmap.c:3225
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff812558e0-ffffffff81255b6a: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81261260)
Location: mm/mmap.c:3225
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff81261260-ffffffff812614ea: copy_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_area_struct *copy_vma(struct vm_area_struct **vmap, long unsigned int addr, long unsigned int len, long unsigned int pgoff, bool *need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81270c30)
Location: mm/mmap.c:3225
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
```
**Symbols:**

```
ffffffff81270c30-ffffffff81270eba: copy_vma (STB_GLOBAL)
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
