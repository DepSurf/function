# Function: <code>dequeue_addr_from_hash_entry</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/freescale/fman/fman_dtsec.c (ffff8000109f446c)
Location: drivers/net/ethernet/freescale/fman/fman_mac.h:213
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:free_init_resources
```
```
In drivers/net/ethernet/freescale/fman/fman_memac.c (ffff8000109f66ec)
Location: drivers/net/ethernet/freescale/fman/fman_mac.h:213
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_memac.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_memac.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_memac.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_memac.c:free_init_resources
```
```
In drivers/net/ethernet/freescale/fman/fman_tgec.c (ffff8000109f7b2c)
Location: drivers/net/ethernet/freescale/fman/fman_mac.h:213
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:free_init_resources
```
</details>
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
