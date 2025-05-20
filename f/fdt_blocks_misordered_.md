# Function: <code>fdt_blocks_misordered_</code>

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
int fdt_blocks_misordered_(const void *fdt, int mem_rsv_size, int struct_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffff80001143f518)
Location: scripts/dtc/libfdt/fdt_rw.c:13
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
ffff800010d86f68-ffff800010d86fd4: fdt_blocks_misordered_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_blocks_misordered_(const void *fdt, int mem_rsv_size, int struct_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c0e81ea0)
Location: scripts/dtc/libfdt/fdt_rw.c:13
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
c0e81ea0-c0e81f10: fdt_blocks_misordered_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_blocks_misordered_(const void *fdt, int mem_rsv_size, int struct_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c000000000ec6c90)
Location: scripts/dtc/libfdt/fdt_rw.c:13
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
c000000000ec6c90-c000000000ec6d08: fdt_blocks_misordered_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_blocks_misordered_(const void *fdt, int mem_rsv_size, int struct_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffffffe0008b0cc8)
Location: scripts/dtc/libfdt/fdt_rw.c:13
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
ffffffe0008b0cc8-ffffffe0008b0dc4: fdt_blocks_misordered_ (STB_LOCAL)
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
