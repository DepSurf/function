# Function: <code>dma_resv_get_fences_rcu</code>

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
int dma_resv_get_fences_rcu(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81767d20)
Location: drivers/dma-buf/dma-resv.c:399
Inline: False
```
**Symbols:**

```
ffffffff81767d20-ffffffff8176804b: dma_resv_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dma_resv_get_fences_rcu(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81828b20)
Location: drivers/dma-buf/dma-resv.c:432
Inline: False
```
**Symbols:**

```
ffffffff81828b20-ffffffff81828ee6: dma_resv_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dma_resv_get_fences_rcu(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81839800)
Location: drivers/dma-buf/dma-resv.c:432
Inline: False
```
**Symbols:**

```
ffffffff81839800-ffffffff81839c26: dma_resv_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_resv_get_fences_rcu(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8181ca70)
Location: drivers/dma-buf/dma-resv.c:432
Inline: False
```
**Symbols:**

```
ffffffff8181ca70-ffffffff8181ce7f: dma_resv_get_fences_rcu (STB_GLOBAL)
```
</details>
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
int dma_resv_get_fences_rcu(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffff800010969208)
Location: drivers/dma-buf/dma-resv.c:399
Inline: False
```
**Symbols:**

```
ffff800010969208-ffff80001096948c: dma_resv_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_resv_get_fences_rcu(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (c0a3f3dc)
Location: drivers/dma-buf/dma-resv.c:399
Inline: False
```
**Symbols:**

```
c0a3f3dc-c0a3f6c0: dma_resv_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_resv_get_fences_rcu(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (c000000000a215a0)
Location: drivers/dma-buf/dma-resv.c:399
Inline: False
```
**Symbols:**

```
c000000000a215a0-c000000000a21960: dma_resv_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_resv_get_fences_rcu(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffe0005d4a12)
Location: drivers/dma-buf/dma-resv.c:399
Inline: False
```
**Symbols:**

```
ffffffe0005d4a12-ffffffe0005d4c46: dma_resv_get_fences_rcu (STB_GLOBAL)
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
int dma_resv_get_fences_rcu(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8171c410)
Location: drivers/dma-buf/dma-resv.c:399
Inline: False
```
**Symbols:**

```
ffffffff8171c410-ffffffff8171c73b: dma_resv_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dma_resv_get_fences_rcu(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff816f5870)
Location: drivers/dma-buf/dma-resv.c:399
Inline: False
```
**Symbols:**

```
ffffffff816f5870-ffffffff816f5b9b: dma_resv_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dma_resv_get_fences_rcu(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8175b1e0)
Location: drivers/dma-buf/dma-resv.c:399
Inline: False
```
**Symbols:**

```
ffffffff8175b1e0-ffffffff8175b50b: dma_resv_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dma_resv_get_fences_rcu(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81776dd0)
Location: drivers/dma-buf/dma-resv.c:399
Inline: False
```
**Symbols:**

```
ffffffff81776dd0-ffffffff8177714f: dma_resv_get_fences_rcu (STB_GLOBAL)
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
