# Function: <code>fdt_get_name</code>

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
const char *fdt_get_name(const void *fdt, int nodeoffset, int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e0d0)
Location: scripts/dtc/libfdt/fdt_ro.c:285
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_rw.c:fdt_set_name
  - drivers/of/fdt.c:of_scan_flat_dt_subnodes
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/fdt.c:unflatten_dt_nodes
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_rw.c:fdt_set_name
```
**Symbols:**

```
ffff800010d85a40-ffff800010d85af8: fdt_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *fdt_get_name(const void *fdt, int nodeoffset, int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e80a7c)
Location: scripts/dtc/libfdt/fdt_ro.c:285
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_scan_flat_dt_subnodes
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/fdt.c:unflatten_dt_nodes
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_rw.c:fdt_set_name
```
**Symbols:**

```
c0e80a7c-c0e80b2c: fdt_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *fdt_get_name(const void *fdt, int nodeoffset, int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec4f30)
Location: scripts/dtc/libfdt/fdt_ro.c:285
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_scan_flat_dt_subnodes
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/fdt.c:unflatten_dt_nodes
  - drivers/of/fdt.c:unflatten_dt_nodes
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_rw.c:fdt_set_name
```
**Symbols:**

```
c000000000ec4f30-c000000000ec5058: fdt_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *fdt_get_name(const void *fdt, int nodeoffset, int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008afc6c)
Location: scripts/dtc/libfdt/fdt_ro.c:285
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_scan_flat_dt_subnodes
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/fdt.c:unflatten_dt_nodes
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_rw.c:fdt_set_name
```
**Symbols:**

```
ffffffe0008afc6c-ffffffe0008afd4e: fdt_get_name (STB_GLOBAL)
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
