# Function: <code>vme_alloc_consistent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff816f0cb0)
Location: drivers/vme/vme.c:84
Inline: False
```
**Symbols:**

```
ffffffff816f0cb0-ffffffff816f0d3f: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81755cf0)
Location: drivers/vme/vme.c:84
Inline: False
```
**Symbols:**

```
ffffffff81755cf0-ffffffff81755d7f: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817822b0)
Location: drivers/vme/vme.c:83
Inline: False
```
**Symbols:**

```
ffffffff817822b0-ffffffff8178233f: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817a1010)
Location: drivers/vme/vme.c:90
Inline: False
```
**Symbols:**

```
ffffffff817a1010-ffffffff817a109f: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81818110)
Location: drivers/vme/vme.c:90
Inline: False
```
**Symbols:**

```
ffffffff81818110-ffffffff818181a2: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:90
Inline: False
```
**Symbols:**

```
ffffffff81862b8a-ffffffff81862bdc: vme_alloc_consistent.cold.26 (STB_LOCAL)
ffffffff81861b90-ffffffff81861bec: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:90
Inline: False
```
**Symbols:**

```
ffffffff8188231c-ffffffff8188236f: vme_alloc_consistent.cold.26 (STB_LOCAL)
ffffffff81881370-ffffffff818813d9: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:86
Inline: False
```
**Symbols:**

```
ffffffff818cc950-ffffffff818cc9a3: vme_alloc_consistent.cold (STB_LOCAL)
ffffffff818cb950-ffffffff818cb9bb: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:86
Inline: False
```
**Symbols:**

```
ffffffff818fed40-ffffffff818fed93: vme_alloc_consistent.cold (STB_LOCAL)
ffffffff818fdd40-ffffffff818fddab: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:86
Inline: False
```
**Symbols:**

```
ffffffff819d5668-ffffffff819d56bb: vme_alloc_consistent.cold (STB_LOCAL)
ffffffff819d3b50-ffffffff819d3bb5: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:81
Inline: False
```
**Symbols:**

```
ffffffff81c2f652-ffffffff81c2f6a5: vme_alloc_consistent.cold (STB_LOCAL)
ffffffff819d36d0-ffffffff819d3735: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:81
Inline: False
```
**Symbols:**

```
ffffffff81c21917-ffffffff81c2196a: vme_alloc_consistent.cold (STB_LOCAL)
ffffffff819b8980-ffffffff819b89e5: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:81
Inline: False
```
**Symbols:**

```
ffffffff81d3367a-ffffffff81d336cd: vme_alloc_consistent.cold (STB_LOCAL)
ffffffff81a678b0-ffffffff81a67915: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:81
Inline: False
```
**Symbols:**

```
ffffffff81effb07-ffffffff81effb4a: vme_alloc_consistent.cold (STB_LOCAL)
ffffffff81bd8fa0-ffffffff81bd9002: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81d6a450)
Location: drivers/staging/vme_user/vme.c:81
Inline: False
```
**Symbols:**

```
ffffffff81d6a450-ffffffff81d6a4e8: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81dd7730)
Location: drivers/staging/vme_user/vme.c:81
Inline: False
```
**Symbols:**

```
ffffffff81dd7730-ffffffff81dd77c8: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81e918e0)
Location: drivers/staging/vme_user/vme.c:80
Inline: False
```
**Symbols:**

```
ffffffff81e918e0-ffffffff81e91945: vme_alloc_consistent (STB_GLOBAL)
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
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffff800010b8d918)
Location: drivers/vme/vme.c:86
Inline: False
```
**Symbols:**

```
ffff800010b8d918-ffff800010b8d9d8: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c0c76784)
Location: drivers/vme/vme.c:86
Inline: False
```
**Symbols:**

```
c0c76784-c0c7683c: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c000000000c6b900)
Location: drivers/vme/vme.c:86
Inline: False
```
**Symbols:**

```
c000000000c6b900-c000000000c6ba08: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffe00073387a)
Location: drivers/vme/vme.c:86
Inline: False
```
**Symbols:**

```
ffffffe00073387a-ffffffe000733922: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:86
Inline: False
```
**Symbols:**

```
ffffffff818a0070-ffffffff818a00c3: vme_alloc_consistent.cold (STB_LOCAL)
ffffffff8189f070-ffffffff8189f0db: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:86
Inline: False
```
**Symbols:**

```
ffffffff8185b7e0-ffffffff8185b833: vme_alloc_consistent.cold (STB_LOCAL)
ffffffff8185a7e0-ffffffff8185a84b: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:86
Inline: False
```
**Symbols:**

```
ffffffff818ef760-ffffffff818ef7b3: vme_alloc_consistent.cold (STB_LOCAL)
ffffffff818ee760-ffffffff818ee7cb: vme_alloc_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *vme_alloc_consistent(struct vme_resource *resource, size_t size, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:86
Inline: False
```
**Symbols:**

```
ffffffff81910838-ffffffff8191088b: vme_alloc_consistent.cold (STB_LOCAL)
ffffffff8190f950-ffffffff8190f9bb: vme_alloc_consistent (STB_GLOBAL)
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
