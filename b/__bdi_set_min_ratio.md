# Function: <code>__bdi_set_min_ratio</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __bdi_set_min_ratio(struct backing_dev_info *bdi, unsigned int min_ratio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81369fa5)
Location: mm/page-writeback.c:688
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_min_ratio
  - mm/page-writeback.c:bdi_set_min_ratio_no_scale
Direct callers:
  - mm/page-writeback.c:bdi_set_min_bytes
```
**Symbols:**

```
ffffffff81366370-ffffffff813663fc: __bdi_set_min_ratio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __bdi_set_min_ratio(struct backing_dev_info *bdi, unsigned int min_ratio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8139c145)
Location: mm/page-writeback.c:688
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_min_ratio
  - mm/page-writeback.c:bdi_set_min_ratio_no_scale
Direct callers:
  - mm/page-writeback.c:bdi_set_min_bytes
```
**Symbols:**

```
ffffffff81398810-ffffffff8139889a: __bdi_set_min_ratio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __bdi_set_min_ratio(struct backing_dev_info *bdi, unsigned int min_ratio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c5e34)
Location: mm/page-writeback.c:688
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_min_ratio
  - mm/page-writeback.c:bdi_set_min_ratio_no_scale
Direct callers:
  - mm/page-writeback.c:bdi_set_min_bytes
```
**Symbols:**

```
ffffffff813c2610-ffffffff813c2696: __bdi_set_min_ratio (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
