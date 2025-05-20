# Function: <code>of_get_flat_dt_root</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int of_get_flat_dt_root();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114aa87c)
Location: drivers/of/fdt.c:699
Inline: True
```
**Symbols:**

```
ffff8000114aa87c-ffff8000114aa898: of_get_flat_dt_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int of_get_flat_dt_root();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15aed80)
Location: drivers/of/fdt.c:699
Inline: True
Direct callers:
  - arch/arm/kernel/devtree.c:setup_machine_fdt
```
**Symbols:**

```
c15aed80-c15aed9c: of_get_flat_dt_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int of_get_flat_dt_root();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013ba71c)
Location: drivers/of/fdt.c:699
Inline: True
Direct callers:
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_init
  - arch/powerpc/mm/init_64.c:mmu_early_init_devtree
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init
```
**Symbols:**

```
c0000000013ba71c-c0000000013ba72c: of_get_flat_dt_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int of_get_flat_dt_root();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003ac00)
Location: drivers/of/fdt.c:699
Inline: True
```
**Symbols:**

```
ffffffe00003ac00-ffffffe00003ac1c: of_get_flat_dt_root (STB_GLOBAL)
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
