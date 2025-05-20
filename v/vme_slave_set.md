# Function: <code>vme_slave_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff816f0de0)
Location: drivers/vme/vme.c:327
Inline: False
```
**Symbols:**

```
ffffffff816f0de0-ffffffff816f0ec0: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81755e20)
Location: drivers/vme/vme.c:327
Inline: False
```
**Symbols:**

```
ffffffff81755e20-ffffffff81755f00: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817823e0)
Location: drivers/vme/vme.c:330
Inline: False
```
**Symbols:**

```
ffffffff817823e0-ffffffff817824c0: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817a1140)
Location: drivers/vme/vme.c:377
Inline: False
```
**Symbols:**

```
ffffffff817a1140-ffffffff817a122c: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81818250)
Location: drivers/vme/vme.c:374
Inline: False
```
**Symbols:**

```
ffffffff81818250-ffffffff81818341: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:374
Inline: False
```
**Symbols:**

```
ffffffff81862c26-ffffffff81862c68: vme_slave_set.cold.28 (STB_LOCAL)
ffffffff81861c60-ffffffff81861d24: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:374
Inline: False
```
**Symbols:**

```
ffffffff818823b9-ffffffff818823fb: vme_slave_set.cold.28 (STB_LOCAL)
ffffffff81881450-ffffffff81881514: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:370
Inline: False
```
**Symbols:**

```
ffffffff818cc9ed-ffffffff818cca2f: vme_slave_set.cold (STB_LOCAL)
ffffffff818cba30-ffffffff818cbafb: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:370
Inline: False
```
**Symbols:**

```
ffffffff818feddd-ffffffff818fee1f: vme_slave_set.cold (STB_LOCAL)
ffffffff818fde20-ffffffff818fdeeb: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:370
Inline: False
```
**Symbols:**

```
ffffffff819d571b-ffffffff819d575d: vme_slave_set.cold (STB_LOCAL)
ffffffff819d3cd0-ffffffff819d3d96: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:361
Inline: False
```
**Symbols:**

```
ffffffff81c2f705-ffffffff81c2f747: vme_slave_set.cold (STB_LOCAL)
ffffffff819d3850-ffffffff819d3916: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:361
Inline: False
```
**Symbols:**

```
ffffffff81c219cb-ffffffff81c21a0d: vme_slave_set.cold (STB_LOCAL)
ffffffff819b8b10-ffffffff819b8bd6: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:361
Inline: False
```
**Symbols:**

```
ffffffff81d3372e-ffffffff81d33770: vme_slave_set.cold (STB_LOCAL)
ffffffff81a67a40-ffffffff81a67b06: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:361
Inline: False
```
**Symbols:**

```
ffffffff81effbaa-ffffffff81effbe4: vme_slave_set.cold (STB_LOCAL)
ffffffff81bd9160-ffffffff81bd9232: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81d6a6e0)
Location: drivers/staging/vme_user/vme.c:361
Inline: False
```
**Symbols:**

```
ffffffff81d6a6e0-ffffffff81d6a7de: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81dd79c0)
Location: drivers/staging/vme_user/vme.c:361
Inline: False
```
**Symbols:**

```
ffffffff81dd79c0-ffffffff81dd7abe: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81e92760)
Location: drivers/staging/vme_user/vme.c:327
Inline: False
```
**Symbols:**

```
ffffffff81e92760-ffffffff81e9288e: vme_slave_set (STB_GLOBAL)
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
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffff800010b8da88)
Location: drivers/vme/vme.c:370
Inline: False
```
**Symbols:**

```
ffff800010b8da88-ffff800010b8db98: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c0c76a2c)
Location: drivers/vme/vme.c:370
Inline: False
```
**Symbols:**

```
c0c76a2c-c0c76b34: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c000000000c6bb00)
Location: drivers/vme/vme.c:370
Inline: False
```
**Symbols:**

```
c000000000c6bb00-c000000000c6bca0: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffe0007339c6)
Location: drivers/vme/vme.c:370
Inline: False
```
**Symbols:**

```
ffffffe0007339c6-ffffffe000733ab0: vme_slave_set (STB_GLOBAL)
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
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:370
Inline: False
```
**Symbols:**

```
ffffffff818a010d-ffffffff818a014f: vme_slave_set.cold (STB_LOCAL)
ffffffff8189f150-ffffffff8189f21b: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:370
Inline: False
```
**Symbols:**

```
ffffffff8185b87d-ffffffff8185b8bf: vme_slave_set.cold (STB_LOCAL)
ffffffff8185a8c0-ffffffff8185a98b: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:370
Inline: False
```
**Symbols:**

```
ffffffff818ef7fd-ffffffff818ef83f: vme_slave_set.cold (STB_LOCAL)
ffffffff818ee840-ffffffff818ee90b: vme_slave_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vme_slave_set(struct vme_resource *resource, int enabled, long long unsigned int vme_base, long long unsigned int size, dma_addr_t buf_base, u32 aspace, u32 cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:370
Inline: False
```
**Symbols:**

```
ffffffff819108d5-ffffffff81910917: vme_slave_set.cold (STB_LOCAL)
ffffffff8190fa30-ffffffff8190fafb: vme_slave_set (STB_GLOBAL)
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
