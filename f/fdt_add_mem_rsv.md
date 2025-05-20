# Function: <code>fdt_add_mem_rsv</code>

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
int fdt_add_mem_rsv(void *fdt, uint64_t address, uint64_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffff80001143f9b8)
Location: scripts/dtc/libfdt/fdt_rw.c:141
Inline: False
```
**Symbols:**

```
ffff800010d87408-ffff800010d874ac: fdt_add_mem_rsv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_add_mem_rsv(void *fdt, uint64_t address, uint64_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c0e822dc)
Location: scripts/dtc/libfdt/fdt_rw.c:141
Inline: False
```
**Symbols:**

```
c0e822dc-c0e8237c: fdt_add_mem_rsv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_add_mem_rsv(void *fdt, uint64_t address, uint64_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c000000000ec7350)
Location: scripts/dtc/libfdt/fdt_rw.c:141
Inline: False
Direct callers:
  - arch/powerpc/kernel/machine_kexec_file_64.c:setup_new_fdt
  - arch/powerpc/kernel/ima_kexec.c:setup_ima_buffer
```
**Symbols:**

```
c000000000ec7350-c000000000ec7474: fdt_add_mem_rsv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_add_mem_rsv(void *fdt, uint64_t address, uint64_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffffffe0008b1564)
Location: scripts/dtc/libfdt/fdt_rw.c:141
Inline: False
```
**Symbols:**

```
ffffffe0008b1564-ffffffe0008b16ae: fdt_add_mem_rsv (STB_GLOBAL)
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
