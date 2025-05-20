# Function: <code>fdt_getprop_by_offset</code>

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
const void *fdt_getprop_by_offset(const void *fdt, int offset, const char **namep, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e590)
Location: scripts/dtc/libfdt/fdt_ro.c:452
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_check_full
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/fdt_ro.c:fdt_check_full
```
**Symbols:**

```
ffff800010d85f38-ffff800010d86018: fdt_getprop_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const void *fdt_getprop_by_offset(const void *fdt, int offset, const char **namep, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e80f48)
Location: scripts/dtc/libfdt/fdt_ro.c:452
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/fdt_ro.c:fdt_check_full
```
**Symbols:**

```
c0e80f48-c0e81028: fdt_getprop_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const void *fdt_getprop_by_offset(const void *fdt, int offset, const char **namep, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec5600)
Location: scripts/dtc/libfdt/fdt_ro.c:452
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/fdt_ro.c:fdt_check_full
```
**Symbols:**

```
c000000000ec5600-c000000000ec5720: fdt_getprop_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const void *fdt_getprop_by_offset(const void *fdt, int offset, const char **namep, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008b00ea)
Location: scripts/dtc/libfdt/fdt_ro.c:452
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/fdt_ro.c:fdt_check_full
```
**Symbols:**

```
ffffffe0008b00ea-ffffffe0008b01d6: fdt_getprop_by_offset (STB_GLOBAL)
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
