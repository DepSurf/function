# Function: <code>gnttab_free_grant_reference_seq</code>

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
void gnttab_free_grant_reference_seq(grant_ref_t head, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c7250)
Location: drivers/xen/grant-table.c:619
Inline: False
```
**Symbols:**

```
ffffffff818c7250-ffffffff818c72c5: gnttab_free_grant_reference_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gnttab_free_grant_reference_seq(grant_ref_t head, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a17e00)
Location: drivers/xen/grant-table.c:619
Inline: False
Direct callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_unmap_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_free
```
**Symbols:**

```
ffffffff81a17e00-ffffffff81a17e75: gnttab_free_grant_reference_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gnttab_free_grant_reference_seq(grant_ref_t head, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a60e90)
Location: drivers/xen/grant-table.c:637
Inline: False
Direct callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_unmap_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_free
```
**Symbols:**

```
ffffffff81a60e90-ffffffff81a60f05: gnttab_free_grant_reference_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gnttab_free_grant_reference_seq(grant_ref_t head, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab36c0)
Location: drivers/xen/grant-table.c:635
Inline: False
Direct callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_unmap_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_free
```
**Symbols:**

```
ffffffff81ab36c0-ffffffff81ab3735: gnttab_free_grant_reference_seq (STB_GLOBAL)
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
