# Function: <code>vme_slave_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff816f0ec0)
Location: drivers/vme/vme.c:362
Inline: False
```
**Symbols:**

```
ffffffff816f0ec0-ffffffff816f0f58: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81755f00)
Location: drivers/vme/vme.c:362
Inline: False
```
**Symbols:**

```
ffffffff81755f00-ffffffff81755f98: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817824c0)
Location: drivers/vme/vme.c:365
Inline: False
```
**Symbols:**

```
ffffffff817824c0-ffffffff81782558: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817a1230)
Location: drivers/vme/vme.c:427
Inline: False
```
**Symbols:**

```
ffffffff817a1230-ffffffff817a12c4: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81818350)
Location: drivers/vme/vme.c:424
Inline: False
```
**Symbols:**

```
ffffffff81818350-ffffffff818183e7: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:424
Inline: False
```
**Symbols:**

```
ffffffff81862c68-ffffffff81862c94: vme_slave_get.cold.29 (STB_LOCAL)
ffffffff81861d30-ffffffff81861da9: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:424
Inline: False
```
**Symbols:**

```
ffffffff818823fb-ffffffff81882427: vme_slave_get.cold.29 (STB_LOCAL)
ffffffff81881520-ffffffff81881599: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:420
Inline: False
```
**Symbols:**

```
ffffffff818cca2f-ffffffff818cca5b: vme_slave_get.cold (STB_LOCAL)
ffffffff818cbb00-ffffffff818cbb79: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:420
Inline: False
```
**Symbols:**

```
ffffffff818fee1f-ffffffff818fee4b: vme_slave_get.cold (STB_LOCAL)
ffffffff818fdef0-ffffffff818fdf69: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:420
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_get_size
```
**Symbols:**

```
ffffffff819d575d-ffffffff819d5789: vme_slave_get.cold (STB_LOCAL)
ffffffff819d3da0-ffffffff819d3e13: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:411
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_get_size
```
**Symbols:**

```
ffffffff81c2f747-ffffffff81c2f773: vme_slave_get.cold (STB_LOCAL)
ffffffff819d3920-ffffffff819d3993: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:411
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_get_size
```
**Symbols:**

```
ffffffff81c21a0d-ffffffff81c21a39: vme_slave_get.cold (STB_LOCAL)
ffffffff819b8be0-ffffffff819b8c53: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:411
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_get_size
```
**Symbols:**

```
ffffffff81d33770-ffffffff81d3379c: vme_slave_get.cold (STB_LOCAL)
ffffffff81a67b10-ffffffff81a67b83: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:411
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_get_size
```
**Symbols:**

```
ffffffff81effbe4-ffffffff81effc08: vme_slave_get.cold (STB_LOCAL)
ffffffff81bd9240-ffffffff81bd92c5: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81d6a7f0)
Location: drivers/staging/vme_user/vme.c:411
Inline: False
Direct callers:
  - drivers/staging/vme_user/vme.c:vme_get_size
```
**Symbols:**

```
ffffffff81d6a7f0-ffffffff81d6a88e: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81dd7ad0)
Location: drivers/staging/vme_user/vme.c:411
Inline: False
Direct callers:
  - drivers/staging/vme_user/vme.c:vme_get_size
```
**Symbols:**

```
ffffffff81dd7ad0-ffffffff81dd7b6e: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81e91d20)
Location: drivers/staging/vme_user/vme.c:377
Inline: False
Direct callers:
  - drivers/staging/vme_user/vme.c:vme_get_size
```
**Symbols:**

```
ffffffff81e91d20-ffffffff81e91dc3: vme_slave_get (STB_GLOBAL)
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
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffff800010b8db98)
Location: drivers/vme/vme.c:420
Inline: False
```
**Symbols:**

```
ffff800010b8db98-ffff800010b8dc54: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c0c76b34)
Location: drivers/vme/vme.c:420
Inline: False
```
**Symbols:**

```
c0c76b34-c0c76bd0: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c000000000c6bca0)
Location: drivers/vme/vme.c:420
Inline: False
```
**Symbols:**

```
c000000000c6bca0-c000000000c6bd78: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffe000733ab0)
Location: drivers/vme/vme.c:420
Inline: False
```
**Symbols:**

```
ffffffe000733ab0-ffffffe000733b4e: vme_slave_get (STB_GLOBAL)
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
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:420
Inline: False
```
**Symbols:**

```
ffffffff818a014f-ffffffff818a017b: vme_slave_get.cold (STB_LOCAL)
ffffffff8189f220-ffffffff8189f299: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:420
Inline: False
```
**Symbols:**

```
ffffffff8185b8bf-ffffffff8185b8eb: vme_slave_get.cold (STB_LOCAL)
ffffffff8185a990-ffffffff8185aa09: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:420
Inline: False
```
**Symbols:**

```
ffffffff818ef83f-ffffffff818ef86b: vme_slave_get.cold (STB_LOCAL)
ffffffff818ee910-ffffffff818ee989: vme_slave_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vme_slave_get(struct vme_resource *resource, int *enabled, long long unsigned int *vme_base, long long unsigned int *size, dma_addr_t *buf_base, u32 *aspace, u32 *cycle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:420
Inline: False
```
**Symbols:**

```
ffffffff81910917-ffffffff81910943: vme_slave_get.cold (STB_LOCAL)
ffffffff8190fb00-ffffffff8190fb79: vme_slave_get (STB_GLOBAL)
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
