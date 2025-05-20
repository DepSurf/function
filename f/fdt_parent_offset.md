# Function: <code>fdt_parent_offset</code>

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
int fdt_parent_offset(const void *fdt, int nodeoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143ece8)
Location: scripts/dtc/libfdt/fdt_ro.c:619
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
```
**Symbols:**

```
ffff800010d86710-ffff800010d867a0: fdt_parent_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_parent_offset(const void *fdt, int nodeoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e816b0)
Location: scripts/dtc/libfdt/fdt_ro.c:619
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
```
**Symbols:**

```
c0e816b0-c0e81744: fdt_parent_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_parent_offset(const void *fdt, int nodeoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec60b0)
Location: scripts/dtc/libfdt/fdt_ro.c:619
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
```
**Symbols:**

```
c000000000ec60b0-c000000000ec6168: fdt_parent_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_parent_offset(const void *fdt, int nodeoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008b0704)
Location: scripts/dtc/libfdt/fdt_ro.c:619
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
```
**Symbols:**

```
ffffffe0008b0704-ffffffe0008b075c: fdt_parent_offset (STB_GLOBAL)
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
