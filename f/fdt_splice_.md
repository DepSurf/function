# Function: <code>fdt_splice_</code>

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
int fdt_splice_(void *fdt, void *splicepoint, int oldlen, int newlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffff80001143f588)
Location: scripts/dtc/libfdt/fdt_rw.c:52
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_splice_struct_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_splice_struct_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
```
**Symbols:**

```
ffff800010d86fd8-ffff800010d87064: fdt_splice_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_splice_(void *fdt, void *splicepoint, int oldlen, int newlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c0e81f10)
Location: scripts/dtc/libfdt/fdt_rw.c:52
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_splice_struct_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
```
**Symbols:**

```
c0e81f10-c0e81fac: fdt_splice_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_splice_(void *fdt, void *splicepoint, int oldlen, int newlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c000000000ec6d10)
Location: scripts/dtc/libfdt/fdt_rw.c:52
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_splice_struct_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
```
**Symbols:**

```
c000000000ec6d10-c000000000ec6dd0: fdt_splice_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_splice_(void *fdt, void *splicepoint, int oldlen, int newlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffffffe0008b0dc4)
Location: scripts/dtc/libfdt/fdt_rw.c:52
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_splice_struct_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
```
**Symbols:**

```
ffffffe0008b0dc4-ffffffe0008b0e96: fdt_splice_ (STB_LOCAL)
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
