# Function: <code>l2c_wait_mask</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/cache-l2x0.c (c032445c)
Location: arch/arm/mm/cache-l2x0.c:54
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0.c:l2c220_sync
  - arch/arm/mm/cache-l2x0.c:l2c220_flush_range
  - arch/arm/mm/cache-l2x0.c:l2c220_flush_range
  - arch/arm/mm/cache-l2x0.c:l2c220_clean_range
  - arch/arm/mm/cache-l2x0.c:l2c220_clean_range
  - arch/arm/mm/cache-l2x0.c:l2c220_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c220_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c220_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c220_op_pa_range
  - arch/arm/mm/cache-l2x0.c:l2c220_op_way
  - arch/arm/mm/cache-l2x0.c:l2c_enable
  - arch/arm/mm/cache-l2x0.c:__l2c_op_way
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
