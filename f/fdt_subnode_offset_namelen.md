# Function: <code>fdt_subnode_offset_namelen</code>

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
int fdt_subnode_offset_namelen(const void *fdt, int offset, const char *name, int namelen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e190)
Location: scripts/dtc/libfdt/fdt_ro.c:210
Inline: True
Direct callers:
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_subnode_offset
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_subnode_offset
```
**Symbols:**

```
ffff800010d85af8-ffff800010d85c14: fdt_subnode_offset_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fdt_subnode_offset_namelen(const void *fdt, int offset, const char *name, int namelen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e80b2c)
Location: scripts/dtc/libfdt/fdt_ro.c:210
Inline: True
Direct callers:
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_subnode_offset
```
**Symbols:**

```
c0e80b2c-c0e80c38: fdt_subnode_offset_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fdt_subnode_offset_namelen(const void *fdt, int offset, const char *name, int namelen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec5060)
Location: scripts/dtc/libfdt/fdt_ro.c:210
Inline: True
Direct callers:
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_subnode_offset
```
**Symbols:**

```
c000000000ec5060-c000000000ec51cc: fdt_subnode_offset_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fdt_subnode_offset_namelen(const void *fdt, int offset, const char *name, int namelen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008afd4e)
Location: scripts/dtc/libfdt/fdt_ro.c:210
Inline: True
Direct callers:
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_subnode_offset
```
**Symbols:**

```
ffffffe0008afd4e-ffffffe0008afe10: fdt_subnode_offset_namelen (STB_GLOBAL)
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
