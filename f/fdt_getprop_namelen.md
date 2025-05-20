# Function: <code>fdt_getprop_namelen</code>

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
const void *fdt_getprop_namelen(const void *fdt, int nodeoffset, const char *name, int namelen, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e528)
Location: scripts/dtc/libfdt/fdt_ro.c:434
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_node_check_compatible
  - lib/fdt_ro.c:fdt_stringlist_get
  - lib/fdt_ro.c:fdt_stringlist_search
  - lib/fdt_ro.c:fdt_stringlist_count
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_get_alias_namelen
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_wip.c:fdt_setprop_inplace_namelen_partial
  - lib/fdt_ro.c:fdt_get_alias_namelen
  - lib/fdt_ro.c:fdt_getprop
  - lib/fdt_wip.c:fdt_setprop_inplace_namelen_partial
```
**Symbols:**

```
ffff800010d85ea8-ffff800010d85f34: fdt_getprop_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const void *fdt_getprop_namelen(const void *fdt, int nodeoffset, const char *name, int namelen, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e80ea4)
Location: scripts/dtc/libfdt/fdt_ro.c:434
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_alias_namelen
  - lib/fdt_ro.c:fdt_getprop
  - lib/fdt_wip.c:fdt_setprop_inplace_namelen_partial
```
**Symbols:**

```
c0e80ea4-c0e80f48: fdt_getprop_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const void *fdt_getprop_namelen(const void *fdt, int nodeoffset, const char *name, int namelen, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec5550)
Location: scripts/dtc/libfdt/fdt_ro.c:434
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_alias_namelen
  - lib/fdt_ro.c:fdt_getprop
  - lib/fdt_wip.c:fdt_setprop_inplace_namelen_partial
```
**Symbols:**

```
c000000000ec5550-c000000000ec5600: fdt_getprop_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const void *fdt_getprop_namelen(const void *fdt, int nodeoffset, const char *name, int namelen, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008b0062)
Location: scripts/dtc/libfdt/fdt_ro.c:434
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_node_check_compatible
  - lib/fdt_ro.c:fdt_stringlist_get
  - lib/fdt_ro.c:fdt_stringlist_search
  - lib/fdt_ro.c:fdt_stringlist_count
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_get_alias_namelen
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_wip.c:fdt_setprop_inplace_namelen_partial
```
**Symbols:**

```
ffffffe0008b0062-ffffffe0008b00ea: fdt_getprop_namelen (STB_GLOBAL)
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
