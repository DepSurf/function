# Function: <code>fdt_check_node_offset_</code>

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
int fdt_check_node_offset_(const void *fdt, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffff80001143da68)
Location: scripts/dtc/libfdt/fdt.c:179
Inline: False
Direct callers:
  - lib/fdt.c:fdt_next_node
  - lib/fdt_ro.c:fdt_first_property_offset
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt.c:fdt_next_node
  - lib/fdt_ro.c:fdt_first_property_offset
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_rw.c:fdt_add_property_
```
**Symbols:**

```
ffff800010d853c0-ffff800010d85400: fdt_check_node_offset_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_check_node_offset_(const void *fdt, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c0e803f8)
Location: scripts/dtc/libfdt/fdt.c:179
Inline: False
Direct callers:
  - lib/fdt.c:fdt_next_node
  - lib/fdt_ro.c:fdt_first_property_offset
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_rw.c:fdt_add_property_
```
**Symbols:**

```
c0e803f8-c0e80440: fdt_check_node_offset_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_check_node_offset_(const void *fdt, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c000000000ec45a0)
Location: scripts/dtc/libfdt/fdt.c:179
Inline: False
Direct callers:
  - lib/fdt.c:fdt_next_node
  - lib/fdt_ro.c:fdt_first_property_offset
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_rw.c:fdt_add_property_
```
**Symbols:**

```
c000000000ec45a0-c000000000ec4600: fdt_check_node_offset_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_check_node_offset_(const void *fdt, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffffffe0008af52a)
Location: scripts/dtc/libfdt/fdt.c:179
Inline: False
Direct callers:
  - lib/fdt.c:fdt_next_node
  - lib/fdt_ro.c:fdt_first_property_offset
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_rw.c:fdt_add_property_
```
**Symbols:**

```
ffffffe0008af52a-ffffffe0008af564: fdt_check_node_offset_ (STB_GLOBAL)
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
