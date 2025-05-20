# Function: <code>of_fdt_is_compatible</code>

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
int of_fdt_is_compatible(const void *blob, long unsigned int node, const char *compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff800010b72354)
Location: drivers/of/fdt.c:726
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_flat_dt_match_machine
  - drivers/of/fdt.c:of_flat_dt_is_compatible
```
**Symbols:**

```
ffff800010b72354-ffff800010b7242c: of_fdt_is_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_fdt_is_compatible(const void *blob, long unsigned int node, const char *compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0c548dc)
Location: drivers/of/fdt.c:726
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_flat_dt_match_machine
  - drivers/of/fdt.c:of_flat_dt_is_compatible
```
**Symbols:**

```
c0c548dc-c0c54994: of_fdt_is_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_fdt_is_compatible(const void *blob, long unsigned int node, const char *compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c000000000c4e85c)
Location: drivers/of/fdt.c:726
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_flat_dt_match_machine
  - drivers/of/fdt.c:of_flat_dt_is_compatible
```
**Symbols:**

```
c000000000c4e85c-c000000000c4e948: of_fdt_is_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_fdt_is_compatible(const void *blob, long unsigned int node, const char *compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe000726042)
Location: drivers/of/fdt.c:726
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_flat_dt_match_machine
  - drivers/of/fdt.c:of_flat_dt_is_compatible
```
**Symbols:**

```
ffffffe000726042-ffffffe0007260ca: of_fdt_is_compatible (STB_LOCAL)
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
