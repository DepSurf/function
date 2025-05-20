# Function: <code>fdt_header_size_</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
size_t fdt_header_size_(uint32_t version);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffff80001143d7d4)
Location: scripts/dtc/libfdt/fdt.c:54
Inline: True
Inline callers:
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
```
**Symbols:**

```
ffff800010d850d8-ffff800010d85108: fdt_header_size_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t fdt_header_size_(uint32_t version);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c0e80150)
Location: scripts/dtc/libfdt/fdt.c:54
Inline: True
Inline callers:
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
```
**Symbols:**

```
c0e800ec-c0e80128: fdt_header_size_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t fdt_header_size_(uint32_t version);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c000000000ec41a4)
Location: scripts/dtc/libfdt/fdt.c:54
Inline: True
Inline callers:
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
```
**Symbols:**

```
c000000000ec4140-c000000000ec4178: fdt_header_size_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
size_t fdt_header_size_(uint32_t version);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffffffe0008af14c)
Location: scripts/dtc/libfdt/fdt.c:54
Inline: True
Inline callers:
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
```
**Symbols:**

```
ffffffe0008af0b8-ffffffe0008af0f2: fdt_header_size_ (STB_GLOBAL)
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
