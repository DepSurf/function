# Function: <code>fdt_first_property_offset</code>

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
int fdt_first_property_offset(const void *fdt, int nodeoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e2d8)
Location: scripts/dtc/libfdt/fdt_ro.c:323
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_property_namelen_
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/fdt_ro.c:fdt_get_property_namelen_
```
**Symbols:**

```
ffff800010d85c60-ffff800010d85c90: fdt_first_property_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_first_property_offset(const void *fdt, int nodeoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e80c70)
Location: scripts/dtc/libfdt/fdt_ro.c:323
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/fdt_ro.c:fdt_get_property_namelen_
```
**Symbols:**

```
c0e80c70-c0e80c9c: fdt_first_property_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_first_property_offset(const void *fdt, int nodeoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec5230)
Location: scripts/dtc/libfdt/fdt_ro.c:323
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/fdt_ro.c:fdt_get_property_namelen_
```
**Symbols:**

```
c000000000ec5230-c000000000ec5294: fdt_first_property_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_first_property_offset(const void *fdt, int nodeoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008afe4e)
Location: scripts/dtc/libfdt/fdt_ro.c:323
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/fdt_ro.c:fdt_get_property_namelen_
```
**Symbols:**

```
ffffffe0008afe4e-ffffffe0008afe7c: fdt_first_property_offset (STB_GLOBAL)
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
