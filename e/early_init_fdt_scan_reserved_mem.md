# Function: <code>early_init_fdt_scan_reserved_mem</code>

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
void early_init_fdt_scan_reserved_mem();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114ab304)
Location: drivers/of/fdt.c:586
Inline: False
Direct callers:
  - arch/arm64/mm/init.c:arm64_memblock_init
```
**Symbols:**

```
ffff8000114ab304-ffff8000114ab3ac: early_init_fdt_scan_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void early_init_fdt_scan_reserved_mem();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15afa18)
Location: drivers/of/fdt.c:586
Inline: False
Direct callers:
  - arch/arm/mm/init.c:arm_memblock_init
```
**Symbols:**

```
c15afa18-c15afad0: early_init_fdt_scan_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void early_init_fdt_scan_reserved_mem();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013bb3f0)
Location: drivers/of/fdt.c:586
Inline: False
Direct callers:
  - arch/powerpc/kernel/prom.c:early_init_devtree
```
**Symbols:**

```
c0000000013bb3f0-c0000000013bb4bc: early_init_fdt_scan_reserved_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void early_init_fdt_scan_reserved_mem();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003b644)
Location: drivers/of/fdt.c:586
Inline: False
Direct callers:
  - arch/riscv/mm/init.c:setup_bootmem
```
**Symbols:**

```
ffffffe00003b644-ffffffe00003b6bc: early_init_fdt_scan_reserved_mem (STB_GLOBAL)
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
