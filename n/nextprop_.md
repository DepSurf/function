# Function: <code>nextprop_</code>

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
int nextprop_(const void *fdt, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143dde8)
Location: scripts/dtc/libfdt/fdt_ro.c:186
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_next_property_offset
  - lib/fdt_ro.c:fdt_first_property_offset
  - lib/fdt_ro.c:fdt_next_property_offset
  - lib/fdt_ro.c:fdt_first_property_offset
```
**Symbols:**

```
ffff800010d85740-ffff800010d857dc: nextprop_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nextprop_(const void *fdt, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e80784)
Location: scripts/dtc/libfdt/fdt_ro.c:186
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_next_property_offset
  - lib/fdt_ro.c:fdt_first_property_offset
```
**Symbols:**

```
c0e80784-c0e8081c: nextprop_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nextprop_(const void *fdt, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec4ab0)
Location: scripts/dtc/libfdt/fdt_ro.c:186
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_next_property_offset
  - lib/fdt_ro.c:fdt_first_property_offset
```
**Symbols:**

```
c000000000ec4ab0-c000000000ec4b74: nextprop_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nextprop_(const void *fdt, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008af83e)
Location: scripts/dtc/libfdt/fdt_ro.c:186
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_next_property_offset
  - lib/fdt_ro.c:fdt_first_property_offset
```
**Symbols:**

```
ffffffe0008af83e-ffffffe0008af8a4: nextprop_ (STB_LOCAL)
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
