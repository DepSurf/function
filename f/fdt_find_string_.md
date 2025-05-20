# Function: <code>fdt_find_string_</code>

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
const char *fdt_find_string_(const char *strtab, int tabsize, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffff80001143dc50)
Location: scripts/dtc/libfdt/fdt.c:265
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_add_property_
```
**Symbols:**

```
ffff800010d85620-ffff800010d856a4: fdt_find_string_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *fdt_find_string_(const char *strtab, int tabsize, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c0e8068c)
Location: scripts/dtc/libfdt/fdt.c:265
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_add_property_
```
**Symbols:**

```
c0e8068c-c0e806f4: fdt_find_string_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *fdt_find_string_(const char *strtab, int tabsize, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c000000000ec48e0)
Location: scripts/dtc/libfdt/fdt.c:265
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_add_property_
```
**Symbols:**

```
c000000000ec48e0-c000000000ec49b4: fdt_find_string_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *fdt_find_string_(const char *strtab, int tabsize, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffffffe0008af6e4)
Location: scripts/dtc/libfdt/fdt.c:265
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_add_property_
```
**Symbols:**

```
ffffffe0008af6e4-ffffffe0008af74e: fdt_find_string_ (STB_GLOBAL)
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
