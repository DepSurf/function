# Function: <code>fdt_num_mem_rsv</code>

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
int fdt_num_mem_rsv(const void *fdt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e090)
Location: scripts/dtc/libfdt/fdt_ro.c:174
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_check_full
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
  - lib/fdt_ro.c:fdt_check_full
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
ffff800010d85a00-ffff800010d85a40: fdt_num_mem_rsv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_num_mem_rsv(const void *fdt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e80a28)
Location: scripts/dtc/libfdt/fdt_ro.c:174
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_check_full
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
c0e80a28-c0e80a7c: fdt_num_mem_rsv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_num_mem_rsv(const void *fdt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec4eb0)
Location: scripts/dtc/libfdt/fdt_ro.c:174
Inline: False
Direct callers:
  - arch/powerpc/kernel/machine_kexec_file_64.c:delete_fdt_mem_rsv
  - lib/fdt_ro.c:fdt_check_full
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
c000000000ec4eb0-c000000000ec4f2c: fdt_num_mem_rsv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_num_mem_rsv(const void *fdt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008afbf4)
Location: scripts/dtc/libfdt/fdt_ro.c:174
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_check_full
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
ffffffe0008afbf4-ffffffe0008afc6c: fdt_num_mem_rsv (STB_GLOBAL)
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
