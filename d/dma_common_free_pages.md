# Function: <code>dma_common_free_pages</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_common_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff81139c80)
Location: kernel/dma/ops_helpers.c:76
Inline: False
```
**Symbols:**

```
ffffffff81139c80-ffffffff81139ce2: dma_common_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_common_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff8113ada0)
Location: kernel/dma/ops_helpers.c:84
Inline: False
```
**Symbols:**

```
ffffffff8113ada0-ffffffff8113ae02: dma_common_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dma_common_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff8115dcd0)
Location: kernel/dma/ops_helpers.c:84
Inline: False
```
**Symbols:**

```
ffffffff8115dcd0-ffffffff8115dd32: dma_common_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dma_common_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff81187ca0)
Location: kernel/dma/ops_helpers.c:84
Inline: False
```
**Symbols:**

```
ffffffff81187ca0-ffffffff81187d13: dma_common_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_common_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811c39a0)
Location: kernel/dma/ops_helpers.c:84
Inline: False
```
**Symbols:**

```
ffffffff811c39a0-ffffffff811c3a13: dma_common_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_common_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811d64f0)
Location: kernel/dma/ops_helpers.c:84
Inline: False
```
**Symbols:**

```
ffffffff811d64f0-ffffffff811d6563: dma_common_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dma_common_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811eb520)
Location: kernel/dma/ops_helpers.c:84
Inline: False
```
**Symbols:**

```
ffffffff811eb520-ffffffff811eb593: dma_common_free_pages (STB_GLOBAL)
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
