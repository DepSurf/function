# Function: <code>altmap_alloc_block_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81899721)
Location: mm/sparse-vmemmap.c:129
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff818cddd3)
Location: mm/sparse-vmemmap.c:129
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8190526a)
Location: mm/sparse-vmemmap.c:129
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8198f281)
Location: mm/sparse-vmemmap.c:132
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:__vmemmap_alloc_block_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff819ebad6)
Location: mm/sparse-vmemmap.c:116
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff819ebad6-ffffffff819ebc1a: altmap_alloc_block_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a26d44)
Location: mm/sparse-vmemmap.c:105
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff81a26d44-ffffffff81a26e88: altmap_alloc_block_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a975e9)
Location: mm/sparse-vmemmap.c:105
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff81a975e9-ffffffff81a9772e: altmap_alloc_block_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81aceecb)
Location: mm/sparse-vmemmap.c:105
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff81aceecb-ffffffff81aceff5: altmap_alloc_block_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81bc788c)
Location: mm/sparse-vmemmap.c:104
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
```
**Symbols:**

```
ffffffff81bc788c-ffffffff81bc79b6: altmap_alloc_block_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c405c4)
Location: mm/sparse-vmemmap.c:105
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
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
In mm/sparse-vmemmap.c (ffffffff81c32655)
Location: mm/sparse-vmemmap.c:105
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81d50f3e)
Location: mm/sparse-vmemmap.c:459
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81d50f3e-ffffffff81d51078: altmap_alloc_block_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81f21158)
Location: mm/sparse-vmemmap.c:505
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81f21158-ffffffff81f212a2: altmap_alloc_block_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff820cae60)
Location: mm/sparse-vmemmap.c:106
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
**Symbols:**

```
ffffffff820cae60-ffffffff820cafed: altmap_alloc_block_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8214f0f0)
Location: mm/sparse-vmemmap.c:106
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
**Symbols:**

```
ffffffff8214f0f0-ffffffff8214f274: altmap_alloc_block_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff82231fc0)
Location: mm/sparse-vmemmap.c:106
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
**Symbols:**

```
ffffffff82231fc0-ffffffff82232144: altmap_alloc_block_buf (STB_LOCAL)
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
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffff800010da0b24)
Location: mm/sparse-vmemmap.c:105
Inline: False
```
**Symbols:**

```
ffff800010da0b24-ffff800010da0c74: altmap_alloc_block_buf (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (c000000000eed950)
Location: mm/sparse-vmemmap.c:105
Inline: False
Direct callers:
  - arch/powerpc/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
c000000000eed950-c000000000eedad0: altmap_alloc_block_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffe000048e50)
Location: mm/sparse-vmemmap.c:105
Inline: False
```
**Symbols:**

```
ffffffe000048e50-ffffffe000048f56: altmap_alloc_block_buf (STB_GLOBAL)
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
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a6dd3b)
Location: mm/sparse-vmemmap.c:105
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff81a6dd3b-ffffffff81a6de65: altmap_alloc_block_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a2a282)
Location: mm/sparse-vmemmap.c:105
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff81a2a282-ffffffff81a2a3ac: altmap_alloc_block_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ada14b)
Location: mm/sparse-vmemmap.c:105
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff81ada14b-ffffffff81ada275: altmap_alloc_block_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *altmap_alloc_block_buf(long unsigned int size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ae6601)
Location: mm/sparse-vmemmap.c:105
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff81ae6601-ffffffff81ae672b: altmap_alloc_block_buf (STB_GLOBAL)
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
