# Function: <code>fdt_get_property_namelen</code>

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
const struct fdt_property *fdt_get_property_namelen(const void *fdt, int offset, const char *name, int namelen, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e498)
Location: scripts/dtc/libfdt/fdt_ro.c:408
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_property
  - lib/fdt_ro.c:fdt_get_property
```
**Symbols:**

```
ffff800010d85e18-ffff800010d85e58: fdt_get_property_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct fdt_property *fdt_get_property_namelen(const void *fdt, int offset, const char *name, int namelen, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e80e00)
Location: scripts/dtc/libfdt/fdt_ro.c:408
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_property
```
**Symbols:**

```
c0e80e00-c0e80e5c: fdt_get_property_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct fdt_property *fdt_get_property_namelen(const void *fdt, int offset, const char *name, int namelen, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec54b0)
Location: scripts/dtc/libfdt/fdt_ro.c:408
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_property
```
**Symbols:**

```
c000000000ec54b0-c000000000ec54e8: fdt_get_property_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct fdt_property *fdt_get_property_namelen(const void *fdt, int offset, const char *name, int namelen, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008affc6)
Location: scripts/dtc/libfdt/fdt_ro.c:408
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_property
```
**Symbols:**

```
ffffffe0008affc6-ffffffe0008b001c: fdt_get_property_namelen (STB_GLOBAL)
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
