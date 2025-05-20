# Function: <code>gnttab_alloc_grant_reference_seq</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gnttab_alloc_grant_reference_seq(unsigned int count, grant_ref_t *first);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c8810)
Location: drivers/xen/grant-table.c:645
Inline: False
```
**Symbols:**

```
ffffffff818c8810-ffffffff818c884b: gnttab_alloc_grant_reference_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gnttab_alloc_grant_reference_seq(unsigned int count, grant_ref_t *first);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a19250)
Location: drivers/xen/grant-table.c:645
Inline: False
Direct callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
**Symbols:**

```
ffffffff81a19250-ffffffff81a1928b: gnttab_alloc_grant_reference_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gnttab_alloc_grant_reference_seq(unsigned int count, grant_ref_t *first);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a622d0)
Location: drivers/xen/grant-table.c:663
Inline: False
Direct callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
**Symbols:**

```
ffffffff81a622d0-ffffffff81a6230b: gnttab_alloc_grant_reference_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gnttab_alloc_grant_reference_seq(unsigned int count, grant_ref_t *first);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab4b00)
Location: drivers/xen/grant-table.c:661
Inline: False
Direct callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
**Symbols:**

```
ffffffff81ab4b00-ffffffff81ab4b3b: gnttab_alloc_grant_reference_seq (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
