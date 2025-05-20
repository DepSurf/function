# Function: <code>dma_resv_reserve_shared</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81767b40)
Location: drivers/dma-buf/dma-resv.c:148
Inline: False
```
**Symbols:**

```
ffffffff81767b40-ffffffff81767cdb: dma_resv_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81828560)
Location: drivers/dma-buf/dma-resv.c:181
Inline: False
```
**Symbols:**

```
ffffffff81828560-ffffffff8182871a: dma_resv_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81838f90)
Location: drivers/dma-buf/dma-resv.c:187
Inline: False
```
**Symbols:**

```
ffffffff81838f90-ffffffff81839195: dma_resv_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8181c250)
Location: drivers/dma-buf/dma-resv.c:187
Inline: False
```
**Symbols:**

```
ffffffff8181c250-ffffffff8181c453: dma_resv_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-resv.c (0)
Location: drivers/dma-buf/dma-resv.c:145
Inline: False
```
**Symbols:**

```
ffffffff81d0bb68-ffffffff81d0bb86: dma_resv_reserve_shared.cold (STB_LOCAL)
ffffffff818a66e0-ffffffff818a68b7: dma_resv_reserve_shared (STB_GLOBAL)
```
</details>
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
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffff800010968dd8)
Location: drivers/dma-buf/dma-resv.c:148
Inline: False
```
**Symbols:**

```
ffff800010968dd8-ffff800010968f78: dma_resv_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (c0a3eed0)
Location: drivers/dma-buf/dma-resv.c:148
Inline: False
```
**Symbols:**

```
c0a3eed0-c0a3f06c: dma_resv_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (c000000000a20ba0)
Location: drivers/dma-buf/dma-resv.c:148
Inline: False
```
**Symbols:**

```
c000000000a20ba0-c000000000a20e30: dma_resv_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffe0005d4d12)
Location: drivers/dma-buf/dma-resv.c:148
Inline: False
```
**Symbols:**

```
ffffffe0005d4d12-ffffffe0005d4e84: dma_resv_reserve_shared (STB_GLOBAL)
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
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8171c230)
Location: drivers/dma-buf/dma-resv.c:148
Inline: False
```
**Symbols:**

```
ffffffff8171c230-ffffffff8171c3cb: dma_resv_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff816f5690)
Location: drivers/dma-buf/dma-resv.c:148
Inline: False
```
**Symbols:**

```
ffffffff816f5690-ffffffff816f582b: dma_resv_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8175b000)
Location: drivers/dma-buf/dma-resv.c:148
Inline: False
```
**Symbols:**

```
ffffffff8175b000-ffffffff8175b19b: dma_resv_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dma_resv_reserve_shared(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff817765e0)
Location: drivers/dma-buf/dma-resv.c:148
Inline: False
```
**Symbols:**

```
ffffffff817765e0-ffffffff8177677b: dma_resv_reserve_shared (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
