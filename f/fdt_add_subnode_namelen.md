# Function: <code>fdt_add_subnode_namelen</code>

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
int fdt_add_subnode_namelen(void *fdt, int parentoffset, const char *name, int namelen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffff80001143fed8)
Location: scripts/dtc/libfdt/fdt_rw.c:318
Inline: True
Direct callers:
  - lib/fdt_rw.c:fdt_add_subnode
  - lib/fdt_rw.c:fdt_add_subnode
```
**Symbols:**

```
ffff800010d87960-ffff800010d87ab0: fdt_add_subnode_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fdt_add_subnode_namelen(void *fdt, int parentoffset, const char *name, int namelen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c0e82810)
Location: scripts/dtc/libfdt/fdt_rw.c:318
Inline: True
Direct callers:
  - lib/fdt_rw.c:fdt_add_subnode
```
**Symbols:**

```
c0e82810-c0e82940: fdt_add_subnode_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fdt_add_subnode_namelen(void *fdt, int parentoffset, const char *name, int namelen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c000000000ec7b20)
Location: scripts/dtc/libfdt/fdt_rw.c:318
Inline: True
Direct callers:
  - lib/fdt_rw.c:fdt_add_subnode
```
**Symbols:**

```
c000000000ec7b20-c000000000ec7cdc: fdt_add_subnode_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fdt_add_subnode_namelen(void *fdt, int parentoffset, const char *name, int namelen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffffffe0008b1a76)
Location: scripts/dtc/libfdt/fdt_rw.c:318
Inline: True
Direct callers:
  - lib/fdt_rw.c:fdt_add_subnode
```
**Symbols:**

```
ffffffe0008b1a76-ffffffe0008b1b82: fdt_add_subnode_namelen (STB_GLOBAL)
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
