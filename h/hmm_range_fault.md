# Function: <code>hmm_range_fault</code>

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
long int hmm_range_fault(struct hmm_range *range, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812c3110)
Location: mm/hmm.c:1051
Inline: False
Direct callers:
  - mm/hmm.c:hmm_range_dma_map
```
**Symbols:**

```
ffffffff812c3110-ffffffff812c334c: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int hmm_range_fault(struct hmm_range *range, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812d5170)
Location: mm/hmm.c:890
Inline: False
Direct callers:
  - mm/hmm.c:hmm_range_dma_map
```
**Symbols:**

```
ffffffff812d5170-ffffffff812d533d: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hmm_range_fault(struct hmm_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8130aaa0)
Location: mm/hmm.c:557
Inline: False
```
**Symbols:**

```
ffffffff8130aaa0-ffffffff8130ab26: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hmm_range_fault(struct hmm_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff81316970)
Location: mm/hmm.c:568
Inline: False
```
**Symbols:**

```
ffffffff81316970-ffffffff813169f6: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hmm_range_fault(struct hmm_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8131cbc0)
Location: mm/hmm.c:568
Inline: False
```
**Symbols:**

```
ffffffff8131cbc0-ffffffff8131cc46: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hmm_range_fault(struct hmm_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff81369f00)
Location: mm/hmm.c:576
Inline: False
```
**Symbols:**

```
ffffffff81369f00-ffffffff81369f86: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hmm_range_fault(struct hmm_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff813e7ce0)
Location: mm/hmm.c:572
Inline: False
```
**Symbols:**

```
ffffffff813e7ce0-ffffffff813e7d75: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hmm_range_fault(struct hmm_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8146fba0)
Location: mm/hmm.c:571
Inline: False
```
**Symbols:**

```
ffffffff8146fba0-ffffffff8146fc35: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hmm_range_fault(struct hmm_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff814a4380)
Location: mm/hmm.c:587
Inline: False
```
**Symbols:**

```
ffffffff814a4380-ffffffff814a4415: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hmm_range_fault(struct hmm_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff814d51c0)
Location: mm/hmm.c:587
Inline: False
```
**Symbols:**

```
ffffffff814d51c0-ffffffff814d5255: hmm_range_fault (STB_GLOBAL)
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
long int hmm_range_fault(struct hmm_range *range, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffff80001037a4a0)
Location: mm/hmm.c:890
Inline: False
Direct callers:
  - mm/hmm.c:hmm_range_dma_map
```
**Symbols:**

```
ffff80001037a4a0-ffff80001037a68c: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int hmm_range_fault(struct hmm_range *range, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c0565918)
Location: mm/hmm.c:890
Inline: False
Direct callers:
  - mm/hmm.c:hmm_range_dma_map
```
**Symbols:**

```
c0565918-c0565aec: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int hmm_range_fault(struct hmm_range *range, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c00000000046eda0)
Location: mm/hmm.c:890
Inline: False
Direct callers:
  - mm/hmm.c:hmm_range_dma_map
```
**Symbols:**

```
c00000000046eda0-c00000000046efe8: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int hmm_range_fault(struct hmm_range *range, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffe000251948)
Location: mm/hmm.c:890
Inline: False
Direct callers:
  - mm/hmm.c:hmm_range_dma_map
```
**Symbols:**

```
ffffffe000251948-ffffffe000251ab0: hmm_range_fault (STB_GLOBAL)
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
long int hmm_range_fault(struct hmm_range *range, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cd750)
Location: mm/hmm.c:890
Inline: False
Direct callers:
  - mm/hmm.c:hmm_range_dma_map
```
**Symbols:**

```
ffffffff812cd750-ffffffff812cd91d: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int hmm_range_fault(struct hmm_range *range, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812be5c0)
Location: mm/hmm.c:890
Inline: False
Direct callers:
  - mm/hmm.c:hmm_range_dma_map
```
**Symbols:**

```
ffffffff812be5c0-ffffffff812be78d: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int hmm_range_fault(struct hmm_range *range, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cb560)
Location: mm/hmm.c:890
Inline: False
Direct callers:
  - mm/hmm.c:hmm_range_dma_map
```
**Symbols:**

```
ffffffff812cb560-ffffffff812cb72d: hmm_range_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int hmm_range_fault(struct hmm_range *range, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812dc2c0)
Location: mm/hmm.c:890
Inline: False
Direct callers:
  - mm/hmm.c:hmm_range_dma_map
```
**Symbols:**

```
ffffffff812dc2c0-ffffffff812dc48d: hmm_range_fault (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>int</code>
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
