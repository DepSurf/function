# Function: <code>hmm_range_dma_map</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int hmm_range_dma_map(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812c35d0)
Location: mm/hmm.c:1146
Inline: False
```
**Symbols:**

```
ffffffff812c35d0-ffffffff812c3805: hmm_range_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int hmm_range_dma_map(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812d5600)
Location: mm/hmm.c:964
Inline: False
```
**Symbols:**

```
ffffffff812d5600-ffffffff812d5834: hmm_range_dma_map (STB_GLOBAL)
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
long int hmm_range_dma_map(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffff80001037a980)
Location: mm/hmm.c:964
Inline: False
```
**Symbols:**

```
ffff80001037a980-ffff80001037abd4: hmm_range_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int hmm_range_dma_map(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c0565f30)
Location: mm/hmm.c:964
Inline: False
```
**Symbols:**

```
c0565f30-c05662a4: hmm_range_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int hmm_range_dma_map(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c00000000046f510)
Location: mm/hmm.c:964
Inline: False
```
**Symbols:**

```
c00000000046f510-c00000000046f81c: hmm_range_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int hmm_range_dma_map(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffe000251baa)
Location: mm/hmm.c:964
Inline: False
```
**Symbols:**

```
ffffffe000251baa-ffffffe000251d4e: hmm_range_dma_map (STB_GLOBAL)
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
long int hmm_range_dma_map(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cdbe0)
Location: mm/hmm.c:964
Inline: False
```
**Symbols:**

```
ffffffff812cdbe0-ffffffff812cde14: hmm_range_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int hmm_range_dma_map(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812bea50)
Location: mm/hmm.c:964
Inline: False
```
**Symbols:**

```
ffffffff812bea50-ffffffff812bec84: hmm_range_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int hmm_range_dma_map(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cb9f0)
Location: mm/hmm.c:964
Inline: False
```
**Symbols:**

```
ffffffff812cb9f0-ffffffff812cbc24: hmm_range_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int hmm_range_dma_map(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812dc750)
Location: mm/hmm.c:964
Inline: False
```
**Symbols:**

```
ffffffff812dc750-ffffffff812dc984: hmm_range_dma_map (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool block</code>
</li>
</ul>
</details>
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
