# Function: <code>dma_resv_list_alloc</code>

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
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81767a90)
Location: drivers/dma-buf/dma-resv.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
ffffffff81767a90-ffffffff81767ad3: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81828490)
Location: drivers/dma-buf/dma-resv.c:67
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
ffffffff81828490-ffffffff818284d5: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81838ec0)
Location: drivers/dma-buf/dma-resv.c:62
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
ffffffff81838ec0-ffffffff81838f05: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8181c180)
Location: drivers/dma-buf/dma-resv.c:62
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
ffffffff8181c180-ffffffff8181c1c5: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff818a6610)
Location: drivers/dma-buf/dma-resv.c:63
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
ffffffff818a6610-ffffffff818a6655: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int max_fences);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff819f0620)
Location: drivers/dma-buf/dma-resv.c:98
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
**Symbols:**

```
ffffffff819f0620-ffffffff819f066a: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int max_fences);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81b6e170)
Location: drivers/dma-buf/dma-resv.c:98
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
**Symbols:**

```
ffffffff81b6e170-ffffffff81b6e1b7: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int max_fences);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81bc1980)
Location: drivers/dma-buf/dma-resv.c:98
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
**Symbols:**

```
ffffffff81bc1980-ffffffff81bc19c7: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int max_fences);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81c16110)
Location: drivers/dma-buf/dma-resv.c:98
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
**Symbols:**

```
ffffffff81c16110-ffffffff81c16157: dma_resv_list_alloc (STB_LOCAL)
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
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffff800010968d08)
Location: drivers/dma-buf/dma-resv.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
ffff800010968d08-ffff800010968d58: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (c0a3ee18)
Location: drivers/dma-buf/dma-resv.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
c0a3ee18-c0a3ee5c: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (c000000000a20a60)
Location: drivers/dma-buf/dma-resv.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
c000000000a20a60-c000000000a20ac8: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffe0005d49c6)
Location: drivers/dma-buf/dma-resv.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
ffffffe0005d49c6-ffffffe0005d4a12: dma_resv_list_alloc (STB_LOCAL)
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
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8171c180)
Location: drivers/dma-buf/dma-resv.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
ffffffff8171c180-ffffffff8171c1c3: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff816f55e0)
Location: drivers/dma-buf/dma-resv.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
ffffffff816f55e0-ffffffff816f5623: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8175af50)
Location: drivers/dma-buf/dma-resv.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
ffffffff8175af50-ffffffff8175af93: dma_resv_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dma_resv_list *dma_resv_list_alloc(unsigned int shared_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81776530)
Location: drivers/dma-buf/dma-resv.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
**Symbols:**

```
ffffffff81776530-ffffffff81776573: dma_resv_list_alloc (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int max_fences</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int shared_max</code>
</li>
</ul>
</details>
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
