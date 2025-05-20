# Function: <code>move_page_tables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff811c92c0)
Location: mm/mremap.c:163
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811c92c0-ffffffff811c9a04: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff811e56a0)
Location: mm/mremap.c:166
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811e56a0-ffffffff811e5e91: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff811f58c0)
Location: mm/mremap.c:184
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811f58c0-ffffffff811f6177: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812006a0)
Location: mm/mremap.c:195
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812006a0-ffffffff81200f56: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81218e90)
Location: mm/mremap.c:196
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81218e90-ffffffff81219904: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8123a820)
Location: mm/mremap.c:194
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8123a820-ffffffff8123b1db: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8124ea10)
Location: mm/mremap.c:240
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8124ea10-ffffffff8124f59e: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:240
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812625d9-ffffffff812625f9: move_page_tables.cold (STB_LOCAL)
ffffffff81260d60-ffffffff812618f5: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8126f4f0)
Location: mm/mremap.c:240
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8126f4f0-ffffffff812700d0: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812a0270)
Location: mm/mremap.c:259
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812a0270-ffffffff812a08b0: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812ab6d0)
Location: mm/mremap.c:410
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812ab6d0-ffffffff812abfa7: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812b0ad0)
Location: mm/mremap.c:409
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812b0ad0-ffffffff812b12a9: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812f2460)
Location: mm/mremap.c:479
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812f2460-ffffffff812f2e6b: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81356230)
Location: mm/mremap.c:479
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81356230-ffffffff81356bca: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff813d0860)
Location: mm/mremap.c:481
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff813d0860-ffffffff813d115d: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81405270)
Location: mm/mremap.c:492
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81405270-ffffffff81405b3d: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks, bool for_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81431750)
Location: mm/mremap.c:544
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81431750-ffffffff81432236: move_page_tables (STB_GLOBAL)
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
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffff800010305df8)
Location: mm/mremap.c:240
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffff800010305df8-ffff8000103065ec: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c0523d1c)
Location: mm/mremap.c:240
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
c0523d1c-c05241c8: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c0000000003d3a60)
Location: mm/mremap.c:240
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
c0000000003d3a60-c0000000003d4424: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffe000211a3a)
Location: mm/mremap.c:240
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffe000211a3a-ffffffe000211e38: move_page_tables (STB_GLOBAL)
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
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81267b40)
Location: mm/mremap.c:240
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81267b40-ffffffff81268720: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81259e90)
Location: mm/mremap.c:240
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81259e90-ffffffff8125aa0a: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812658e0)
Location: mm/mremap.c:240
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812658e0-ffffffff812664c0: move_page_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int move_page_tables(struct vm_area_struct *vma, long unsigned int old_addr, struct vm_area_struct *new_vma, long unsigned int new_addr, long unsigned int len, bool need_rmap_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81275290)
Location: mm/mremap.c:240
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81275290-ffffffff81275e5f: move_page_tables (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool for_stack</code>
</li>
</ul>
</details>
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
