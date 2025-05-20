# Function: <code>fdt_get_mem_rsv</code>

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
int fdt_get_mem_rsv(const void *fdt, int n, uint64_t *address, uint64_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e020)
Location: scripts/dtc/libfdt/fdt_ro.c:160
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_fdt_scan_reserved_mem
```
**Symbols:**

```
ffff800010d85990-ffff800010d85a00: fdt_get_mem_rsv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_get_mem_rsv(const void *fdt, int n, uint64_t *address, uint64_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e809ac)
Location: scripts/dtc/libfdt/fdt_ro.c:160
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_fdt_scan_reserved_mem
```
**Symbols:**

```
c0e809ac-c0e80a28: fdt_get_mem_rsv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_get_mem_rsv(const void *fdt, int n, uint64_t *address, uint64_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec4de0)
Location: scripts/dtc/libfdt/fdt_ro.c:160
Inline: False
Direct callers:
  - arch/powerpc/kernel/machine_kexec_file_64.c:delete_fdt_mem_rsv
  - drivers/of/fdt.c:early_init_fdt_scan_reserved_mem
```
**Symbols:**

```
c000000000ec4de0-c000000000ec4ea4: fdt_get_mem_rsv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_get_mem_rsv(const void *fdt, int n, uint64_t *address, uint64_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008afb16)
Location: scripts/dtc/libfdt/fdt_ro.c:160
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_fdt_scan_reserved_mem
```
**Symbols:**

```
ffffffe0008afb16-ffffffe0008afbf4: fdt_get_mem_rsv (STB_GLOBAL)
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
