# Function: <code>addr_in_gen_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81407650)
Location: lib/genalloc.c:414
Inline: False
```
**Symbols:**

```
ffffffff81407650-ffffffff8140768d: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8144f4b0)
Location: lib/genalloc.c:433
Inline: False
```
**Symbols:**

```
ffffffff8144f4b0-ffffffff8144f4ed: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8146de70)
Location: lib/genalloc.c:434
Inline: False
```
**Symbols:**

```
ffffffff8146de70-ffffffff8146dead: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81473540)
Location: lib/genalloc.c:434
Inline: False
```
**Symbols:**

```
ffffffff81473540-ffffffff8147357f: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814a08d0)
Location: lib/genalloc.c:434
Inline: False
```
**Symbols:**

```
ffffffff814a08d0-ffffffff814a090f: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814d5a60)
Location: lib/genalloc.c:434
Inline: False
```
**Symbols:**

```
ffffffff814d5a60-ffffffff814d5a99: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814ea4d0)
Location: lib/genalloc.c:435
Inline: False
```
**Symbols:**

```
ffffffff814ea4d0-ffffffff814ea509: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81517230)
Location: lib/genalloc.c:551
Inline: False
```
**Symbols:**

```
ffffffff81517230-ffffffff81517269: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81537c80)
Location: lib/genalloc.c:551
Inline: False
```
**Symbols:**

```
ffffffff81537c80-ffffffff81537cb9: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffff800010644a38)
Location: lib/genalloc.c:551
Inline: False
Direct callers:
  - kernel/dma/remap.c:dma_free_from_pool
```
**Symbols:**

```
ffff800010644a38-ffff800010644a8c: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c07eb178)
Location: lib/genalloc.c:551
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:__iommu_get_pages
  - arch/arm/mm/dma-mapping.c:__free_from_pool
  - drivers/misc/sram-exec.c:sram_exec_copy
```
**Symbols:**

```
c07eb178-c07eb1d4: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c0000000007f0890)
Location: lib/genalloc.c:551
Inline: False
```
**Symbols:**

```
c0000000007f0890-c0000000007f08f8: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffe000471132)
Location: lib/genalloc.c:551
Inline: False
```
**Symbols:**

```
ffffffe000471132-ffffffe00047116a: addr_in_gen_pool (STB_GLOBAL)
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
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81530260)
Location: lib/genalloc.c:551
Inline: False
```
**Symbols:**

```
ffffffff81530260-ffffffff81530299: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81520540)
Location: lib/genalloc.c:551
Inline: False
```
**Symbols:**

```
ffffffff81520540-ffffffff81520579: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152bfa0)
Location: lib/genalloc.c:551
Inline: False
```
**Symbols:**

```
ffffffff8152bfa0-ffffffff8152bfd9: addr_in_gen_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool addr_in_gen_pool(struct gen_pool *pool, long unsigned int start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81545da0)
Location: lib/genalloc.c:551
Inline: False
```
**Symbols:**

```
ffffffff81545da0-ffffffff81545e0d: addr_in_gen_pool (STB_GLOBAL)
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
