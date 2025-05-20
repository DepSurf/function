# Function: <code>fdt_open_into</code>

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
int fdt_open_into(const void *fdt, void *buf, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffff8000114400c0)
Location: scripts/dtc/libfdt/fdt_rw.c:400
Inline: False
Direct callers:
  - arch/arm64/kernel/machine_kexec_file.c:load_other_segments
  - lib/fdt_empty_tree.c:fdt_create_empty_tree
```
**Symbols:**

```
ffff800010d87b60-ffff800010d87d24: fdt_open_into (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_open_into(const void *fdt, void *buf, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c0e829d0)
Location: scripts/dtc/libfdt/fdt_rw.c:400
Inline: False
```
**Symbols:**

```
c0e829d0-c0e82ba0: fdt_open_into (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_open_into(const void *fdt, void *buf, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c000000000ec7de0)
Location: scripts/dtc/libfdt/fdt_rw.c:400
Inline: False
Direct callers:
  - arch/powerpc/kernel/kexec_elf_64.c:elf64_load
```
**Symbols:**

```
c000000000ec7de0-c000000000ec8084: fdt_open_into (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_open_into(const void *fdt, void *buf, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffffffe0008b1c3c)
Location: scripts/dtc/libfdt/fdt_rw.c:400
Inline: False
```
**Symbols:**

```
ffffffe0008b1c3c-ffffffe0008b1ed6: fdt_open_into (STB_GLOBAL)
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
