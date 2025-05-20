# Function: <code>fdt_get_property_by_offset_</code>

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
const struct fdt_property *fdt_get_property_by_offset_(const void *fdt, int offset, int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143de70)
Location: scripts/dtc/libfdt/fdt_ro.c:341
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_get_property_namelen_
  - lib/fdt_ro.c:fdt_get_property_by_offset
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_get_property_namelen_
  - lib/fdt_ro.c:fdt_get_property_by_offset
```
**Symbols:**

```
ffff800010d857e0-ffff800010d85844: fdt_get_property_by_offset_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct fdt_property *fdt_get_property_by_offset_(const void *fdt, int offset, int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e8081c)
Location: scripts/dtc/libfdt/fdt_ro.c:341
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_get_property_namelen_
  - lib/fdt_ro.c:fdt_get_property_by_offset
```
**Symbols:**

```
c0e8081c-c0e80874: fdt_get_property_by_offset_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct fdt_property *fdt_get_property_by_offset_(const void *fdt, int offset, int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec4b80)
Location: scripts/dtc/libfdt/fdt_ro.c:341
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_get_property_namelen_
  - lib/fdt_ro.c:fdt_get_property_by_offset
```
**Symbols:**

```
c000000000ec4b80-c000000000ec4c18: fdt_get_property_by_offset_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct fdt_property *fdt_get_property_by_offset_(const void *fdt, int offset, int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008af8a4)
Location: scripts/dtc/libfdt/fdt_ro.c:341
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_get_property_namelen_
  - lib/fdt_ro.c:fdt_get_property_by_offset
```
**Symbols:**

```
ffffffe0008af8a4-ffffffe0008af934: fdt_get_property_by_offset_ (STB_LOCAL)
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
