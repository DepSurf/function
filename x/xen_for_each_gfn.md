# Function: <code>xen_for_each_gfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff814d6ee0)
Location: drivers/xen/xlate_mmu.c:44
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
```
**Symbols:**

```
ffffffff814d6ee0-ffffffff814d6fb8: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81527ca0)
Location: drivers/xen/xlate_mmu.c:47
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81527ca0-ffffffff81527d79: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81554220)
Location: drivers/xen/xlate_mmu.c:47
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81554220-ffffffff815542e9: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81568d90)
Location: drivers/xen/xlate_mmu.c:47
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81568d90-ffffffff81568e51: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff815ccf40)
Location: drivers/xen/xlate_mmu.c:47
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff815ccf40-ffffffff815cd003: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81605650)
Location: drivers/xen/xlate_mmu.c:47
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81605650-ffffffff81605729: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81620730)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81620730-ffffffff81620809: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81653cb0)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81653cb0-ffffffff81653d6c: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81676250)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81676250-ffffffff8167630c: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81726dc0)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81726dc0-ffffffff81726e80: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81743320)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81743320-ffffffff817433e0: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81726d20)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81726d20-ffffffff81726de0: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff817a5d50)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff817a5d50-ffffffff817a5e10: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff818dfcd0)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff818dfcd0-ffffffff818dfda2: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81a34140)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81a34140-ffffffff81a34212: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81a7db60)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81a7db60-ffffffff81a7dc32: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81ad0000)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81ad0000-ffffffff81ad00d2: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffff800011492378)
Location: drivers/xen/xlate_mmu.c:48
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff8163bf40)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff8163bf40-ffffffff8163bffc: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff8166a090)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff8166a090-ffffffff8166a14c: xen_for_each_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_for_each_gfn(struct page **pages, unsigned int nr_gfn, xen_gfn_fn_t fn, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81684650)
Location: drivers/xen/xlate_mmu.c:48
Inline: False
Direct callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81684650-ffffffff8168470c: xen_for_each_gfn (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
