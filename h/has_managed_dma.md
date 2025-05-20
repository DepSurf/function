# Function: <code>has_managed_dma</code>

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
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool has_managed_dma();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81307374)
Location: mm/page_alloc.c:9456
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
Direct callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
**Symbols:**

```
ffffffff8130a420-ffffffff8130a45c: has_managed_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool has_managed_dma();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136f6ca)
Location: mm/page_alloc.c:9534
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
Direct callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
**Symbols:**

```
ffffffff81372eb0-ffffffff81372ef8: has_managed_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool has_managed_dma();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ebc84)
Location: mm/page_alloc.c:9699
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
Direct callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
**Symbols:**

```
ffffffff813f0640-ffffffff813f0688: has_managed_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool has_managed_dma();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81420c94)
Location: mm/page_alloc.c:6606
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
Direct callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
**Symbols:**

```
ffffffff814241d0-ffffffff81424218: has_managed_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool has_managed_dma();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144da54)
Location: mm/page_alloc.c:6745
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
Direct callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
**Symbols:**

```
ffffffff81450ff0-ffffffff81451038: has_managed_dma (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
