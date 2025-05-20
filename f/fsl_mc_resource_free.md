# Function: <code>fsl_mc_resource_free</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
void fsl_mc_resource_free(struct fsl_mc_resource *resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/bus/fsl-mc/fsl-mc-allocator.c (ffff800010683e28)
Location: drivers/bus/fsl-mc/fsl-mc-allocator.c:227
Inline: False
Direct callers:
  - drivers/bus/fsl-mc/mc-io.c:fsl_mc_portal_free
  - drivers/bus/fsl-mc/mc-io.c:fsl_mc_portal_allocate
  - drivers/bus/fsl-mc/fsl-mc-allocator.c:fsl_mc_free_irqs
  - drivers/bus/fsl-mc/fsl-mc-allocator.c:fsl_mc_allocate_irqs
  - drivers/bus/fsl-mc/fsl-mc-allocator.c:fsl_mc_object_free
  - drivers/bus/fsl-mc/fsl-mc-allocator.c:fsl_mc_object_allocate
```
**Symbols:**

```
ffff800010683e28-ffff800010683ecc: fsl_mc_resource_free (STB_GLOBAL)
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
