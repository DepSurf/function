# Function: <code>pl08x_get_bytes_for_lli</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/amba-pl08x.c (ffff800010800c28)
Location: drivers/dma/amba-pl08x.c:967
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_fill_llis_for_desc
  - drivers/dma/amba-pl08x.c:pl08x_fill_llis_for_desc
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_fill_llis_for_desc
```
**Symbols:**

```
ffff8000108000a0-ffff8000108000a4: pl08x_get_bytes_for_lli.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/amba-pl08x.c (c0922e4c)
Location: drivers/dma/amba-pl08x.c:967
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_fill_llis_for_desc
  - drivers/dma/amba-pl08x.c:pl08x_fill_llis_for_desc
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_fill_llis_for_desc
```
**Symbols:**

```
c0921020-c0921030: pl08x_get_bytes_for_lli.part.0 (STB_LOCAL)
```
</details>
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
