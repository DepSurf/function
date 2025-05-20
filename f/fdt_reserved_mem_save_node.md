# Function: <code>fdt_reserved_mem_save_node</code>

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
void fdt_reserved_mem_save_node(long unsigned int node, const char *uname, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (ffff8000114ac404)
Location: drivers/of/of_reserved_mem.c:51
Inline: False
Direct callers:
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
```
**Symbols:**

```
ffff8000114ac404-ffff8000114ac488: fdt_reserved_mem_save_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fdt_reserved_mem_save_node(long unsigned int node, const char *uname, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (c15b0afc)
Location: drivers/of/of_reserved_mem.c:51
Inline: False
Direct callers:
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
```
**Symbols:**

```
c15b0afc-c15b0b54: fdt_reserved_mem_save_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fdt_reserved_mem_save_node(long unsigned int node, const char *uname, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (c0000000013bc864)
Location: drivers/of/of_reserved_mem.c:51
Inline: False
Direct callers:
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
```
**Symbols:**

```
c0000000013bc864-c0000000013bc8e0: fdt_reserved_mem_save_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fdt_reserved_mem_save_node(long unsigned int node, const char *uname, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (ffffffe00003c576)
Location: drivers/of/of_reserved_mem.c:51
Inline: False
Direct callers:
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
```
**Symbols:**

```
ffffffe00003c576-ffffffe00003c5f0: fdt_reserved_mem_save_node (STB_GLOBAL)
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
