# Function: <code>dma_resv_test_signaled_rcu</code>

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
bool dma_resv_test_signaled_rcu(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81768050)
Location: drivers/dma-buf/dma-resv.c:601
Inline: False
```
**Symbols:**

```
ffffffff81768050-ffffffff8176828a: dma_resv_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool dma_resv_test_signaled_rcu(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81829580)
Location: drivers/dma-buf/dma-resv.c:634
Inline: False
```
**Symbols:**

```
ffffffff81829580-ffffffff8182987d: dma_resv_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool dma_resv_test_signaled_rcu(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81839260)
Location: drivers/dma-buf/dma-resv.c:634
Inline: False
```
**Symbols:**

```
ffffffff81839260-ffffffff81839546: dma_resv_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool dma_resv_test_signaled_rcu(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8181c520)
Location: drivers/dma-buf/dma-resv.c:634
Inline: False
```
**Symbols:**

```
ffffffff8181c520-ffffffff8181c7d9: dma_resv_test_signaled_rcu (STB_GLOBAL)
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
bool dma_resv_test_signaled_rcu(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffff800010969928)
Location: drivers/dma-buf/dma-resv.c:601
Inline: False
```
**Symbols:**

```
ffff800010969928-ffff800010969b24: dma_resv_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool dma_resv_test_signaled_rcu(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (c0a3f1a8)
Location: drivers/dma-buf/dma-resv.c:601
Inline: False
```
**Symbols:**

```
c0a3f1a8-c0a3f3dc: dma_resv_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool dma_resv_test_signaled_rcu(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (c000000000a21050)
Location: drivers/dma-buf/dma-resv.c:601
Inline: False
```
**Symbols:**

```
c000000000a21050-c000000000a213b4: dma_resv_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool dma_resv_test_signaled_rcu(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffe0005d53da)
Location: drivers/dma-buf/dma-resv.c:601
Inline: False
```
**Symbols:**

```
ffffffe0005d53da-ffffffe0005d5588: dma_resv_test_signaled_rcu (STB_GLOBAL)
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
bool dma_resv_test_signaled_rcu(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8171c740)
Location: drivers/dma-buf/dma-resv.c:601
Inline: False
```
**Symbols:**

```
ffffffff8171c740-ffffffff8171c97a: dma_resv_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool dma_resv_test_signaled_rcu(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff816f5ba0)
Location: drivers/dma-buf/dma-resv.c:601
Inline: False
```
**Symbols:**

```
ffffffff816f5ba0-ffffffff816f5dda: dma_resv_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool dma_resv_test_signaled_rcu(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8175b510)
Location: drivers/dma-buf/dma-resv.c:601
Inline: False
```
**Symbols:**

```
ffffffff8175b510-ffffffff8175b74a: dma_resv_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool dma_resv_test_signaled_rcu(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff817767c0)
Location: drivers/dma-buf/dma-resv.c:601
Inline: False
```
**Symbols:**

```
ffffffff817767c0-ffffffff81776a05: dma_resv_test_signaled_rcu (STB_GLOBAL)
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
