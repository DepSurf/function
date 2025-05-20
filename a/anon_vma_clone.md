# Function: <code>anon_vma_clone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811cb8e0)
Location: mm/rmap.c:257
Inline: False
Direct callers:
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:copy_vma
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff811cb8e0-ffffffff811cbad2: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e8ad0)
Location: mm/rmap.c:258
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff811e8ad0-ffffffff811e8cc4: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f9e30)
Location: mm/rmap.c:257
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff811f9e30-ffffffff811fa024: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81204b60)
Location: mm/rmap.c:259
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff81204b60-ffffffff81204d1e: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121db10)
Location: mm/rmap.c:260
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff8121db10-ffffffff8121dcce: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123f9c0)
Location: mm/rmap.c:261
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff8123f9c0-ffffffff8123fb88: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812540c0)
Location: mm/rmap.c:261
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff812540c0-ffffffff81254288: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81266380)
Location: mm/rmap.c:261
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff81266380-ffffffff81266547: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81274ca0)
Location: mm/rmap.c:262
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff81274ca0-ffffffff81274e67: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a60b0)
Location: mm/rmap.c:274
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff812a60b0-ffffffff812a6283: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b1530)
Location: mm/rmap.c:274
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff812b1530-ffffffff812b1703: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b6c10)
Location: mm/rmap.c:274
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff812b6c10-ffffffff812b6de0: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f9030)
Location: mm/rmap.c:275
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff812f9030-ffffffff812f9200: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135f8b0)
Location: mm/rmap.c:279
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff8135f8b0-ffffffff8135fa89: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813da730)
Location: mm/rmap.c:279
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff813da730-ffffffff813da8f4: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140ee70)
Location: mm/rmap.c:281
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_expand
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff8140ee70-ffffffff8140f034: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8143b830)
Location: mm/rmap.c:281
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_expand
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff8143b830-ffffffff8143b9f4: anon_vma_clone (STB_GLOBAL)
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
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff80001030a978)
Location: mm/rmap.c:262
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffff80001030a978-ffff80001030ab40: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0526eb0)
Location: mm/rmap.c:262
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
c0526eb0-c052708c: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003da700)
Location: mm/rmap.c:262
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
c0000000003da700-c0000000003da990: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe0002146d4)
Location: mm/rmap.c:262
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffe0002146d4-ffffffe00021485e: anon_vma_clone (STB_GLOBAL)
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
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126d2f0)
Location: mm/rmap.c:262
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff8126d2f0-ffffffff8126d4b7: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125f320)
Location: mm/rmap.c:262
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff8125f320-ffffffff8125f4e7: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126b090)
Location: mm/rmap.c:262
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff8126b090-ffffffff8126b257: anon_vma_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct *dst, struct vm_area_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8127aa00)
Location: mm/rmap.c:262
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
```
**Symbols:**

```
ffffffff8127aa00-ffffffff8127abc7: anon_vma_clone (STB_GLOBAL)
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
