# Function: <code>fdt_packblocks_</code>

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
void fdt_packblocks_(const char *old, char *new, int mem_rsv_size, int struct_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffff80001143f6f0)
Location: scripts/dtc/libfdt/fdt_rw.c:378
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
ffff800010d871a0-ffff800010d87250: fdt_packblocks_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fdt_packblocks_(const char *old, char *new, int mem_rsv_size, int struct_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c0e82060)
Location: scripts/dtc/libfdt/fdt_rw.c:378
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
c0e82060-c0e820f4: fdt_packblocks_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fdt_packblocks_(const char *old, char *new, int mem_rsv_size, int struct_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c000000000ec6f10)
Location: scripts/dtc/libfdt/fdt_rw.c:378
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
c000000000ec6f10-c000000000ec701c: fdt_packblocks_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fdt_packblocks_(const char *old, char *new, int mem_rsv_size, int struct_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffffffe0008b100c)
Location: scripts/dtc/libfdt/fdt_rw.c:378
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
ffffffe0008b100c-ffffffe0008b11d4: fdt_packblocks_ (STB_LOCAL)
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
