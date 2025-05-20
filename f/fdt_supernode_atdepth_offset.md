# Function: <code>fdt_supernode_atdepth_offset</code>

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
int fdt_supernode_atdepth_offset(const void *fdt, int nodeoffset, int supernodedepth, int *nodedepth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143ebe8)
Location: scripts/dtc/libfdt/fdt_ro.c:572
Inline: True
Direct callers:
  - lib/fdt_ro.c:fdt_parent_offset
  - lib/fdt_ro.c:fdt_parent_offset
  - lib/fdt_ro.c:fdt_parent_offset
  - lib/fdt_ro.c:fdt_parent_offset
```
**Symbols:**

```
ffff800010d865c0-ffff800010d866b0: fdt_supernode_atdepth_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fdt_supernode_atdepth_offset(const void *fdt, int nodeoffset, int supernodedepth, int *nodedepth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e8155c)
Location: scripts/dtc/libfdt/fdt_ro.c:572
Inline: True
Direct callers:
  - lib/fdt_ro.c:fdt_parent_offset
  - lib/fdt_ro.c:fdt_parent_offset
```
**Symbols:**

```
c0e8155c-c0e8164c: fdt_supernode_atdepth_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fdt_supernode_atdepth_offset(const void *fdt, int nodeoffset, int supernodedepth, int *nodedepth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec5ee0)
Location: scripts/dtc/libfdt/fdt_ro.c:572
Inline: True
Direct callers:
  - lib/fdt_ro.c:fdt_parent_offset
  - lib/fdt_ro.c:fdt_parent_offset
```
**Symbols:**

```
c000000000ec5ee0-c000000000ec6030: fdt_supernode_atdepth_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fdt_supernode_atdepth_offset(const void *fdt, int nodeoffset, int supernodedepth, int *nodedepth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008b063e)
Location: scripts/dtc/libfdt/fdt_ro.c:572
Inline: True
Direct callers:
  - lib/fdt_ro.c:fdt_parent_offset
  - lib/fdt_ro.c:fdt_parent_offset
```
**Symbols:**

```
ffffffe0008b063e-ffffffe0008b06d2: fdt_supernode_atdepth_offset (STB_GLOBAL)
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
