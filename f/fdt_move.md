# Function: <code>fdt_move</code>

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
int fdt_move(const void *fdt, void *buf, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffff80001143dcd8)
Location: scripts/dtc/libfdt/fdt.c:277
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
ffff800010d856a8-ffff800010d85700: fdt_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_move(const void *fdt, void *buf, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c0e806f4)
Location: scripts/dtc/libfdt/fdt.c:277
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
c0e806f4-c0e80740: fdt_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_move(const void *fdt, void *buf, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c000000000ec49c0)
Location: scripts/dtc/libfdt/fdt.c:277
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
c000000000ec49c0-c000000000ec4a4c: fdt_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_move(const void *fdt, void *buf, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffffffe0008af74e)
Location: scripts/dtc/libfdt/fdt.c:277
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
ffffffe0008af74e-ffffffe0008af7c0: fdt_move (STB_GLOBAL)
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
