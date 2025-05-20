# Function: <code>unlink_anon_vmas</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811cb6f0)
Location: mm/rmap.c:372
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:vma_adjust
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff811cb6f0-ffffffff811cb8d7: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e8900)
Location: mm/rmap.c:373
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff811e8900-ffffffff811e8ac8: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f9c60)
Location: mm/rmap.c:372
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff811f9c60-ffffffff811f9e28: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812049c0)
Location: mm/rmap.c:374
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff812049c0-ffffffff81204b5d: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121d970)
Location: mm/rmap.c:375
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff8121d970-ffffffff8121db0d: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123f820)
Location: mm/rmap.c:376
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff8123f820-ffffffff8123f9be: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81253f20)
Location: mm/rmap.c:376
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff81253f20-ffffffff812540be: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812661d0)
Location: mm/rmap.c:376
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff812661d0-ffffffff81266375: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81274af0)
Location: mm/rmap.c:377
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff81274af0-ffffffff81274c95: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a5f00)
Location: mm/rmap.c:389
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff812a5f00-ffffffff812a60a6: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b1380)
Location: mm/rmap.c:389
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff812b1380-ffffffff812b1526: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b6a50)
Location: mm/rmap.c:389
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mremap.c:move_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff812b6a50-ffffffff812b6c0c: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f8e70)
Location: mm/rmap.c:390
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mremap.c:move_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff812f8e70-ffffffff812f902c: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135f6e0)
Location: mm/rmap.c:395
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mremap.c:move_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff8135f6e0-ffffffff8135f8a8: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813da560)
Location: mm/rmap.c:395
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
  - mm/mremap.c:move_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff813da560-ffffffff813da71c: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140eca0)
Location: mm/rmap.c:397
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:copy_vma
  - mm/mmap.c:vma_complete
  - mm/mremap.c:move_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff8140eca0-ffffffff8140ee5c: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8143b660)
Location: mm/rmap.c:397
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:copy_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_complete
  - mm/mremap.c:move_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff8143b660-ffffffff8143b81c: unlink_anon_vmas (STB_GLOBAL)
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
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff80001030a768)
Location: mm/rmap.c:377
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffff80001030a768-ffff80001030a974: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0526c90)
Location: mm/rmap.c:377
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
c0526c90-c0526eb0: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003da400)
Location: mm/rmap.c:377
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
c0000000003da400-c0000000003da6fc: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe000214544)
Location: mm/rmap.c:377
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffe000214544-ffffffe0002146d4: unlink_anon_vmas (STB_GLOBAL)
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
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126d140)
Location: mm/rmap.c:377
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff8126d140-ffffffff8126d2e5: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125f170)
Location: mm/rmap.c:377
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff8125f170-ffffffff8125f315: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126aee0)
Location: mm/rmap.c:377
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff8126aee0-ffffffff8126b085: unlink_anon_vmas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unlink_anon_vmas(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8127a850)
Location: mm/rmap.c:377
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
```
**Symbols:**

```
ffffffff8127a850-ffffffff8127a9f5: unlink_anon_vmas (STB_GLOBAL)
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
