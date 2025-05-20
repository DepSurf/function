# Function: <code>fdt_subnode_offset</code>

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
int fdt_subnode_offset(const void *fdt, int parentoffset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e290)
Location: scripts/dtc/libfdt/fdt_ro.c:229
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_get_flat_dt_subnode_by_name
```
**Symbols:**

```
ffff800010d85c18-ffff800010d85c60: fdt_subnode_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_subnode_offset(const void *fdt, int parentoffset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e80c38)
Location: scripts/dtc/libfdt/fdt_ro.c:229
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_get_flat_dt_subnode_by_name
```
**Symbols:**

```
c0e80c38-c0e80c70: fdt_subnode_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_subnode_offset(const void *fdt, int parentoffset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec51d0)
Location: scripts/dtc/libfdt/fdt_ro.c:229
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_get_flat_dt_subnode_by_name
```
**Symbols:**

```
c000000000ec51d0-c000000000ec5228: fdt_subnode_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_subnode_offset(const void *fdt, int parentoffset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008afe10)
Location: scripts/dtc/libfdt/fdt_ro.c:229
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_get_flat_dt_subnode_by_name
```
**Symbols:**

```
ffffffe0008afe10-ffffffe0008afe4e: fdt_subnode_offset (STB_GLOBAL)
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
