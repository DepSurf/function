# Function: <code>get_affine_portal</code>

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
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/soc/fsl/qbman/bman.c (ffff800010811a40)
Location: drivers/soc/fsl/qbman/bman.c:230
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_acquire
  - drivers/soc/fsl/qbman/bman.c:bman_release
  - drivers/soc/fsl/qbman/bman.c:bman_release
  - drivers/soc/fsl/qbman/bman.c:bm_shutdown_pool
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816e90)
Location: drivers/soc/fsl/qbman/qman.c:1011
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_delete_cgr
  - drivers/soc/fsl/qbman/qman.c:qman_create_cgr
  - drivers/soc/fsl/qbman/qman.c:qman_enqueue
  - drivers/soc/fsl/qbman/qman.c:set_vdqcr
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq_np
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq
  - drivers/soc/fsl/qbman/qman.c:qman_oos_fq
  - drivers/soc/fsl/qbman/qman.c:qman_retire_fq
  - drivers/soc/fsl/qbman/qman.c:qman_schedule_fq
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
  - drivers/soc/fsl/qbman/qman.c:qman_affine_channel
  - drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal
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
