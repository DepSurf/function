# Function: <code>of_get_flat_dt_subnode_by_name</code>

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
int of_get_flat_dt_subnode_by_name(long unsigned int node, const char *uname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114aa840)
Location: drivers/of/fdt.c:691
Inline: False
Direct callers:
  - arch/arm/xen/enlighten.c:fdt_find_hyper_node
  - drivers/firmware/efi/efi.c:fdt_find_uefi_params
```
**Symbols:**

```
ffff8000114aa840-ffff8000114aa87c: of_get_flat_dt_subnode_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_get_flat_dt_subnode_by_name(long unsigned int node, const char *uname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15aed50)
Location: drivers/of/fdt.c:691
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:fdt_find_uefi_params
```
**Symbols:**

```
c15aed50-c15aed80: of_get_flat_dt_subnode_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_get_flat_dt_subnode_by_name(long unsigned int node, const char *uname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013ba6d4)
Location: drivers/of/fdt.c:691
Inline: False
Direct callers:
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_init
  - arch/powerpc/mm/init_64.c:mmu_early_init_devtree
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init
  - arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_dt_scan
```
**Symbols:**

```
c0000000013ba6d4-c0000000013ba71c: of_get_flat_dt_subnode_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_get_flat_dt_subnode_by_name(long unsigned int node, const char *uname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003abc4)
Location: drivers/of/fdt.c:691
Inline: False
```
**Symbols:**

```
ffffffe00003abc4-ffffffe00003ac00: of_get_flat_dt_subnode_by_name (STB_GLOBAL)
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
