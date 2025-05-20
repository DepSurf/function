# Function: <code>free_init_resources</code>

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
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
void free_init_resources(struct fman *fman);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/freescale/fman/fman.c (ffff8000109ee730)
Location: drivers/net/ethernet/freescale/fman/fman.c:1215
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
```
```
In drivers/net/ethernet/freescale/fman/fman_dtsec.c (ffff8000109f43b8)
Location: drivers/net/ethernet/freescale/fman/fman_dtsec.c:832
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_free
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
```
```
In drivers/net/ethernet/freescale/fman/fman_memac.c (ffff8000109f6638)
Location: drivers/net/ethernet/freescale/fman/fman_memac.c:689
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_free
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
```
```
In drivers/net/ethernet/freescale/fman/fman_tgec.c (ffff8000109f7a88)
Location: drivers/net/ethernet/freescale/fman/fman_tgec.c:403
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_free
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
```
**Symbols:**

```
ffff8000109ee730-ffff8000109ee790: free_init_resources (STB_LOCAL)
ffff8000109f43b8-ffff8000109f45dc: free_init_resources (STB_LOCAL)
ffff8000109f6638-ffff8000109f685c: free_init_resources (STB_LOCAL)
ffff8000109f7a88-ffff8000109f7c9c: free_init_resources (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
