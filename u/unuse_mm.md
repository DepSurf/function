# Function: <code>unuse_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff811afb90)
Location: mm/mmu_context.c:51
Inline: False
```
```
In mm/swapfile.c (ffffffff811d4030)
Location: mm/swapfile.c:1301
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff811d4030-ffffffff811d479e: unuse_mm (STB_LOCAL)
ffffffff811afb90-ffffffff811afbf6: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff811c90c0)
Location: mm/mmu_context.c:51
Inline: False
```
```
In mm/swapfile.c (ffffffff811f1e60)
Location: mm/swapfile.c:1291
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff811f1e60-ffffffff811f2665: unuse_mm (STB_LOCAL)
ffffffff811c90c0-ffffffff811c9126: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff811d91a0)
Location: mm/mmu_context.c:51
Inline: False
```
```
In mm/swapfile.c (ffffffff81202850)
Location: mm/swapfile.c:1312
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81202850-ffffffff81203061: unuse_mm (STB_LOCAL)
ffffffff811d91a0-ffffffff811d9206: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff811e1fb0)
Location: mm/mmu_context.c:53
Inline: False
```
```
In mm/swapfile.c (ffffffff8120d930)
Location: mm/swapfile.c:1744
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8120d930-ffffffff8120e087: unuse_mm (STB_LOCAL)
ffffffff811e1fb0-ffffffff811e2016: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff811f7f50)
Location: mm/mmu_context.c:53
Inline: False
```
```
In mm/swapfile.c (ffffffff81228ae0)
Location: mm/swapfile.c:1956
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81228ae0-ffffffff8122938f: unuse_mm (STB_LOCAL)
ffffffff811f7f50-ffffffff811f7faa: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff81219200)
Location: mm/mmu_context.c:53
Inline: False
```
```
In mm/swapfile.c (ffffffff8124a5b0)
Location: mm/swapfile.c:1956
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8124a5b0-ffffffff8124a670: unuse_mm (STB_LOCAL)
ffffffff81219200-ffffffff8121925a: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff8122c160)
Location: mm/mmu_context.c:53
Inline: False
```
```
In mm/swapfile.c (ffffffff8125ec00)
Location: mm/swapfile.c:1928
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8125ec00-ffffffff8125ecc0: unuse_mm (STB_LOCAL)
ffffffff8122c160-ffffffff8122c1ba: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff8123be70)
Location: mm/mmu_context.c:53
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In mm/swapfile.c (ffffffff8127b761)
Location: mm/swapfile.c:2067
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8123be70-ffffffff8123beca: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff8124a2c0)
Location: mm/mmu_context.c:53
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In mm/swapfile.c (ffffffff8128b241)
Location: mm/swapfile.c:2067
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8124a2c0-ffffffff8124a31a: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812be41f)
Location: mm/swapfile.c:2097
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unuse_mm(struct mm_struct *mm, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c9bb0)
Location: mm/swapfile.c:2113
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff812c9bb0-ffffffff812c9c84: unuse_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812d0aab)
Location: mm/swapfile.c:2114
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81316186)
Location: mm/swapfile.c:2101
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81381319)
Location: mm/swapfile.c:1990
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813ffb59)
Location: mm/swapfile.c:1990
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff814329e9)
Location: mm/swapfile.c:1981
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146be09)
Location: mm/swapfile.c:1989
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffff8000102dfe48)
Location: mm/mmu_context.c:53
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In mm/swapfile.c (ffff800010326634)
Location: mm/swapfile.c:2067
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffff8000102dfe48-ffff8000102dff20: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (c050495c)
Location: mm/mmu_context.c:53
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In mm/swapfile.c (c053d478)
Location: mm/swapfile.c:2067
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
c053d478-c053db18: unuse_mm (STB_LOCAL)
c050495c-c05049bc: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (c00000000039f880)
Location: mm/mmu_context.c:53
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In mm/swapfile.c (c0000000003fccf8)
Location: mm/swapfile.c:2067
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
c00000000039f880-c00000000039f948: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffe0001f7812)
Location: mm/mmu_context.c:53
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In mm/swapfile.c (ffffffe0002267f0)
Location: mm/swapfile.c:2067
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffe0001f7812-ffffffe0001f7892: unuse_mm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff81242910)
Location: mm/mmu_context.c:53
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In mm/swapfile.c (ffffffff81283821)
Location: mm/swapfile.c:2067
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81242910-ffffffff8124296a: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff812358e0)
Location: mm/mmu_context.c:53
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In mm/swapfile.c (ffffffff812756df)
Location: mm/swapfile.c:2067
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff812358e0-ffffffff8123593a: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff812406b0)
Location: mm/mmu_context.c:53
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In mm/swapfile.c (ffffffff81281631)
Location: mm/swapfile.c:2067
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff812406b0-ffffffff8124070a: unuse_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void unuse_mm(struct mm_struct *mm);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_context.c (ffffffff8124fe30)
Location: mm/mmu_context.c:53
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In mm/swapfile.c (ffffffff8129136c)
Location: mm/swapfile.c:2067
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8124fe30-ffffffff8124fe88: unuse_mm (STB_GLOBAL)
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
