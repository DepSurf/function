# Function: <code>fdt_get_string</code>

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
const char *fdt_get_string(const void *fdt, int stroffset, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143ded8)
Location: scripts/dtc/libfdt/fdt_ro.c:34
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_get_property_namelen_
  - lib/fdt_ro.c:fdt_string
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_get_property_namelen_
  - lib/fdt_ro.c:fdt_string
```
**Symbols:**

```
ffff800010d85848-ffff800010d85978: fdt_get_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *fdt_get_string(const void *fdt, int stroffset, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e80874)
Location: scripts/dtc/libfdt/fdt_ro.c:34
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_get_property_namelen_
  - lib/fdt_ro.c:fdt_string
```
**Symbols:**

```
c0e80874-c0e80994: fdt_get_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *fdt_get_string(const void *fdt, int stroffset, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec4c20)
Location: scripts/dtc/libfdt/fdt_ro.c:34
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_get_property_namelen_
  - lib/fdt_ro.c:fdt_string
```
**Symbols:**

```
c000000000ec4c20-c000000000ec4dc8: fdt_get_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *fdt_get_string(const void *fdt, int stroffset, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008af934)
Location: scripts/dtc/libfdt/fdt_ro.c:34
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_get_property_namelen_
  - lib/fdt_ro.c:fdt_string
```
**Symbols:**

```
ffffffe0008af934-ffffffe0008afafc: fdt_get_string (STB_GLOBAL)
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
