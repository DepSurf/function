# Function: <code>of_flat_dt_is_compatible</code>

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
int of_flat_dt_is_compatible(long unsigned int node, const char *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114aac40)
Location: drivers/of/fdt.c:753
Inline: False
Direct callers:
  - arch/arm64/kernel/acpi.c:dt_scan_depth1_nodes
  - arch/arm/xen/enlighten.c:fdt_find_hyper_node
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
ffff8000114aac40-ffff8000114aac7c: of_flat_dt_is_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_flat_dt_is_compatible(long unsigned int node, const char *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15af1a8)
Location: drivers/of/fdt.c:753
Inline: False
Direct callers:
  - arch/arm/mach-exynos/exynos.c:exynos_fdt_map_chipid
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
c15af1a8-c15af1d8: of_flat_dt_is_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_flat_dt_is_compatible(long unsigned int node, const char *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013babac)
Location: drivers/of/fdt.c:753
Inline: False
Direct callers:
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback
  - arch/powerpc/kernel/dt_cpu_ftrs.c:fdt_find_cpu_features
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal
  - arch/powerpc/platforms/powernv/ultravisor.c:early_init_dt_scan_ultravisor
  - arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_dt_scan
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
c0000000013babac-c0000000013babd4: of_flat_dt_is_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_flat_dt_is_compatible(long unsigned int node, const char *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003aff2)
Location: drivers/of/fdt.c:753
Inline: False
Direct callers:
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
ffffffe00003aff2-ffffffe00003b02c: of_flat_dt_is_compatible (STB_GLOBAL)
```
</details>
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
