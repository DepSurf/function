# Function: <code>is_vmalloc_or_module_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cead0)
Location: mm/vmalloc.c:216
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff811cead0-ffffffff811ceb10: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ebc60)
Location: mm/vmalloc.c:217
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff811ebc60-ffffffff811ebca3: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fce90)
Location: mm/vmalloc.c:217
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff811fce90-ffffffff811fced3: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81207bb0)
Location: mm/vmalloc.c:250
Inline: False
```
**Symbols:**

```
ffffffff81207bb0-ffffffff81207bf3: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81220ca0)
Location: mm/vmalloc.c:248
Inline: False
```
**Symbols:**

```
ffffffff81220ca0-ffffffff81220ce3: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81242b40)
Location: mm/vmalloc.c:248
Inline: False
```
**Symbols:**

```
ffffffff81242b40-ffffffff81242b83: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81257280)
Location: mm/vmalloc.c:248
Inline: False
```
**Symbols:**

```
ffffffff81257280-ffffffff812572c3: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81268600)
Location: mm/vmalloc.c:251
Inline: False
```
**Symbols:**

```
ffffffff81268600-ffffffff81268643: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81276f60)
Location: mm/vmalloc.c:251
Inline: False
```
**Symbols:**

```
ffffffff81276f60-ffffffff81276fa3: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812a8780)
Location: mm/vmalloc.c:332
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812abaf0-ffffffff812abb19: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b3a54)
Location: mm/vmalloc.c:331
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812b7010-ffffffff812b7039: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b9138)
Location: mm/vmalloc.c:597
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812bc910-ffffffff812bc939: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fb6d8)
Location: mm/vmalloc.c:625
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812ff0a0-ffffffff812ff0c9: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81362dd1)
Location: mm/vmalloc.c:626
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81366050-ffffffff81366089: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813de792)
Location: mm/vmalloc.c:645
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff813e1bf0-ffffffff813e1c29: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff814131a2)
Location: mm/vmalloc.c:638
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
Direct callers:
  - lib/iov_iter.c:iov_iter_extract_pages
```
**Symbols:**

```
ffffffff8140fa10-ffffffff8140fa49: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8143fc12)
Location: mm/vmalloc.c:638
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
Direct callers:
  - lib/iov_iter.c:iov_iter_extract_pages
```
**Symbols:**

```
ffffffff8143c370-ffffffff8143c3a9: is_vmalloc_or_module_addr (STB_GLOBAL)
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
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030d488)
Location: mm/vmalloc.c:251
Inline: False
```
**Symbols:**

```
ffff80001030d488-ffff80001030d4c4: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0528fb0)
Location: mm/vmalloc.c:251
Inline: False
```
**Symbols:**

```
c0528fb0-c052900c: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003ddeb0)
Location: mm/vmalloc.c:251
Inline: False
```
**Symbols:**

```
c0000000003ddeb0-c0000000003ddf08: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000216266)
Location: mm/vmalloc.c:251
Inline: False
```
**Symbols:**

```
ffffffe000216266-ffffffe000216294: is_vmalloc_or_module_addr (STB_GLOBAL)
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
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126f5b0)
Location: mm/vmalloc.c:251
Inline: False
```
**Symbols:**

```
ffffffff8126f5b0-ffffffff8126f5f3: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81261520)
Location: mm/vmalloc.c:251
Inline: False
```
**Symbols:**

```
ffffffff81261520-ffffffff81261563: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126d350)
Location: mm/vmalloc.c:251
Inline: False
```
**Symbols:**

```
ffffffff8126d350-ffffffff8126d393: is_vmalloc_or_module_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int is_vmalloc_or_module_addr(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127cce0)
Location: mm/vmalloc.c:251
Inline: False
```
**Symbols:**

```
ffffffff8127cce0-ffffffff8127cd23: is_vmalloc_or_module_addr (STB_GLOBAL)
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
