# Function: <code>fdt_check_prop_offset_</code>

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
int fdt_check_prop_offset_(const void *fdt, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffff80001143daa8)
Location: scripts/dtc/libfdt/fdt.c:188
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_property_by_offset_
  - lib/fdt_ro.c:fdt_next_property_offset
  - lib/fdt_ro.c:fdt_get_property_by_offset_
  - lib/fdt_ro.c:fdt_next_property_offset
```
**Symbols:**

```
ffff800010d85400-ffff800010d85440: fdt_check_prop_offset_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_check_prop_offset_(const void *fdt, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c0e80440)
Location: scripts/dtc/libfdt/fdt.c:188
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_property_by_offset_
  - lib/fdt_ro.c:fdt_next_property_offset
```
**Symbols:**

```
c0e80440-c0e80488: fdt_check_prop_offset_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_check_prop_offset_(const void *fdt, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c000000000ec4600)
Location: scripts/dtc/libfdt/fdt.c:188
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_property_by_offset_
  - lib/fdt_ro.c:fdt_next_property_offset
```
**Symbols:**

```
c000000000ec4600-c000000000ec4660: fdt_check_prop_offset_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_check_prop_offset_(const void *fdt, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffffffe0008af564)
Location: scripts/dtc/libfdt/fdt.c:188
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_property_by_offset_
  - lib/fdt_ro.c:fdt_next_property_offset
```
**Symbols:**

```
ffffffe0008af564-ffffffe0008af59e: fdt_check_prop_offset_ (STB_GLOBAL)
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
