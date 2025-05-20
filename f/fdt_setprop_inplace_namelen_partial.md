# Function: <code>fdt_setprop_inplace_namelen_partial</code>

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
int fdt_setprop_inplace_namelen_partial(void *fdt, int nodeoffset, const char *name, int namelen, uint32_t idx, const void *val, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_wip.c (ffff800011440ab0)
Location: scripts/dtc/libfdt/fdt_wip.c:13
Inline: False
Direct callers:
  - lib/fdt_wip.c:fdt_setprop_inplace
  - lib/fdt_wip.c:fdt_setprop_inplace
```
**Symbols:**

```
ffff800010d87d98-ffff800010d87e2c: fdt_setprop_inplace_namelen_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_setprop_inplace_namelen_partial(void *fdt, int nodeoffset, const char *name, int namelen, uint32_t idx, const void *val, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_wip.c (c0e82c04)
Location: scripts/dtc/libfdt/fdt_wip.c:13
Inline: False
Direct callers:
  - lib/fdt_wip.c:fdt_setprop_inplace
```
**Symbols:**

```
c0e82c04-c0e82c98: fdt_setprop_inplace_namelen_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_setprop_inplace_namelen_partial(void *fdt, int nodeoffset, const char *name, int namelen, uint32_t idx, const void *val, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_wip.c (c000000000ec81b0)
Location: scripts/dtc/libfdt/fdt_wip.c:13
Inline: False
Direct callers:
  - lib/fdt_wip.c:fdt_setprop_inplace
```
**Symbols:**

```
c000000000ec81b0-c000000000ec8278: fdt_setprop_inplace_namelen_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_setprop_inplace_namelen_partial(void *fdt, int nodeoffset, const char *name, int namelen, uint32_t idx, const void *val, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_wip.c (ffffffe0008b1fb0)
Location: scripts/dtc/libfdt/fdt_wip.c:13
Inline: False
Direct callers:
  - lib/fdt_wip.c:fdt_setprop_inplace
```
**Symbols:**

```
ffffffe0008b1fb0-ffffffe0008b2016: fdt_setprop_inplace_namelen_partial (STB_GLOBAL)
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
