# Function: <code>vm_map_ram</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ce6e0)
Location: mm/vmalloc.c:1117
Inline: False
```
**Symbols:**

```
ffffffff811ce6e0-ffffffff811cea7a: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811eb320)
Location: mm/vmalloc.c:1141
Inline: False
```
**Symbols:**

```
ffffffff811eb320-ffffffff811eb6d3: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fc590)
Location: mm/vmalloc.c:1124
Inline: False
```
**Symbols:**

```
ffffffff811fc590-ffffffff811fc943: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81207260)
Location: mm/vmalloc.c:1175
Inline: False
```
**Symbols:**

```
ffffffff81207260-ffffffff8120762a: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81220350)
Location: mm/vmalloc.c:1173
Inline: False
```
**Symbols:**

```
ffffffff81220350-ffffffff8122071a: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81242130)
Location: mm/vmalloc.c:1160
Inline: False
```
**Symbols:**

```
ffffffff81242130-ffffffff81242501: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81256860)
Location: mm/vmalloc.c:1160
Inline: False
```
**Symbols:**

```
ffffffff81256860-ffffffff81256c32: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1769
Inline: False
```
**Symbols:**

```
ffffffff8126bbc6-ffffffff8126bbdf: vm_map_ram.cold (STB_LOCAL)
ffffffff8126aac0-ffffffff8126aeac: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812799d0)
Location: mm/vmalloc.c:1777
Inline: False
```
**Symbols:**

```
ffffffff812799d0-ffffffff81279dda: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ab9f0)
Location: mm/vmalloc.c:1877
Inline: False
```
**Symbols:**

```
ffffffff812ab9f0-ffffffff812abad8: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b6f10)
Location: mm/vmalloc.c:1859
Inline: False
```
**Symbols:**

```
ffffffff812b6f10-ffffffff812b6ff8: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bc7d0)
Location: mm/vmalloc.c:2129
Inline: False
```
**Symbols:**

```
ffffffff812bc7d0-ffffffff812bc8b5: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fef60)
Location: mm/vmalloc.c:2181
Inline: False
```
**Symbols:**

```
ffffffff812fef60-ffffffff812ff045: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81365db0)
Location: mm/vmalloc.c:2199
Inline: False
```
**Symbols:**

```
ffffffff81365db0-ffffffff81365e95: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e18f0)
Location: mm/vmalloc.c:2261
Inline: False
```
**Symbols:**

```
ffffffff813e18f0-ffffffff813e19d5: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81416680)
Location: mm/vmalloc.c:2382
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:vmap_udmabuf
```
**Symbols:**

```
ffffffff81416680-ffffffff8141676c: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81443150)
Location: mm/vmalloc.c:2382
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:vmap_udmabuf
```
**Symbols:**

```
ffffffff81443150-ffffffff8144323c: vm_map_ram (STB_GLOBAL)
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
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff800010310bd0)
Location: mm/vmalloc.c:1777
Inline: False
```
**Symbols:**

```
ffff800010310bd0-ffff8000103110a4: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052ca70)
Location: mm/vmalloc.c:1777
Inline: False
```
**Symbols:**

```
c052ca70-c052ce88: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e1960)
Location: mm/vmalloc.c:1777
Inline: False
```
**Symbols:**

```
c0000000003e1960-c0000000003e1f38: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe0002188fe)
Location: mm/vmalloc.c:1777
Inline: False
```
**Symbols:**

```
ffffffe0002188fe-ffffffe000218d4c: vm_map_ram (STB_GLOBAL)
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
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81272020)
Location: mm/vmalloc.c:1777
Inline: False
```
**Symbols:**

```
ffffffff81272020-ffffffff8127242a: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81263f90)
Location: mm/vmalloc.c:1777
Inline: False
```
**Symbols:**

```
ffffffff81263f90-ffffffff8126439a: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126fdc0)
Location: mm/vmalloc.c:1777
Inline: False
```
**Symbols:**

```
ffffffff8126fdc0-ffffffff812701ca: vm_map_ram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *vm_map_ram(struct page **pages, unsigned int count, int node, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127f7b0)
Location: mm/vmalloc.c:1777
Inline: False
```
**Symbols:**

```
ffffffff8127f7b0-ffffffff8127fbfe: vm_map_ram (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pgprot_t prot</code>
</li>
</ul>
</details>
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
