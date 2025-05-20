# Function: <code>fdt_get_property_namelen_</code>

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
const struct fdt_property *fdt_get_property_namelen_(const void *fdt, int offset, const char *name, int namelen, int *lenp, int *poffset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e338)
Location: scripts/dtc/libfdt/fdt_ro.c:378
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_getprop_namelen
  - lib/fdt_ro.c:fdt_get_property_namelen
  - lib/fdt_ro.c:fdt_getprop_namelen
  - lib/fdt_ro.c:fdt_get_property_namelen
```
**Symbols:**

```
ffff800010d85cc0-ffff800010d85dd8: fdt_get_property_namelen_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct fdt_property *fdt_get_property_namelen_(const void *fdt, int offset, const char *name, int namelen, int *lenp, int *poffset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e80cc8)
Location: scripts/dtc/libfdt/fdt_ro.c:378
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_getprop_namelen
  - lib/fdt_ro.c:fdt_get_property_namelen
```
**Symbols:**

```
c0e80cc8-c0e80dbc: fdt_get_property_namelen_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct fdt_property *fdt_get_property_namelen_(const void *fdt, int offset, const char *name, int namelen, int *lenp, int *poffset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec5310)
Location: scripts/dtc/libfdt/fdt_ro.c:378
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_getprop_namelen
  - lib/fdt_ro.c:fdt_get_property_namelen
```
**Symbols:**

```
c000000000ec5310-c000000000ec5470: fdt_get_property_namelen_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct fdt_property *fdt_get_property_namelen_(const void *fdt, int offset, const char *name, int namelen, int *lenp, int *poffset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008afeaa)
Location: scripts/dtc/libfdt/fdt_ro.c:378
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_getprop_namelen
  - lib/fdt_ro.c:fdt_get_property_namelen
```
**Symbols:**

```
ffffffe0008afeaa-ffffffe0008aff76: fdt_get_property_namelen_ (STB_LOCAL)
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
