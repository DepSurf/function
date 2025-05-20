# Function: <code>fdt_path_offset_namelen</code>

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
int fdt_path_offset_namelen(const void *fdt, const char *path, int namelen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e8a0)
Location: scripts/dtc/libfdt/fdt_ro.c:235
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_path_offset
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - lib/fdt_ro.c:fdt_path_offset
```
**Symbols:**

```
ffff800010d86278-ffff800010d8638c: fdt_path_offset_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_path_offset_namelen(const void *fdt, const char *path, int namelen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e81268)
Location: scripts/dtc/libfdt/fdt_ro.c:235
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - lib/fdt_ro.c:fdt_path_offset
```
**Symbols:**

```
c0e81268-c0e81354: fdt_path_offset_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_path_offset_namelen(const void *fdt, const char *path, int namelen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec5a50)
Location: scripts/dtc/libfdt/fdt_ro.c:235
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - lib/fdt_ro.c:fdt_path_offset
```
**Symbols:**

```
c000000000ec5a50-c000000000ec5bd0: fdt_path_offset_namelen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_path_offset_namelen(const void *fdt, const char *path, int namelen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008b03c2)
Location: scripts/dtc/libfdt/fdt_ro.c:235
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - lib/fdt_ro.c:fdt_path_offset
```
**Symbols:**

```
ffffffe0008b03c2-ffffffe0008b04a2: fdt_path_offset_namelen (STB_GLOBAL)
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
