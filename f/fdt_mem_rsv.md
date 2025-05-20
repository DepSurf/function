# Function: <code>fdt_mem_rsv</code>

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
const struct fdt_reserve_entry *fdt_mem_rsv(const void *fdt, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143dda8)
Location: scripts/dtc/libfdt/fdt_ro.c:148
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_num_mem_rsv
  - lib/fdt_ro.c:fdt_get_mem_rsv
  - lib/fdt_ro.c:fdt_num_mem_rsv
  - lib/fdt_ro.c:fdt_get_mem_rsv
```
**Symbols:**

```
ffff800010d85700-ffff800010d8573c: fdt_mem_rsv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct fdt_reserve_entry *fdt_mem_rsv(const void *fdt, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e80740)
Location: scripts/dtc/libfdt/fdt_ro.c:148
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_num_mem_rsv
  - lib/fdt_ro.c:fdt_get_mem_rsv
```
**Symbols:**

```
c0e80740-c0e80784: fdt_mem_rsv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct fdt_reserve_entry *fdt_mem_rsv(const void *fdt, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec4a50)
Location: scripts/dtc/libfdt/fdt_ro.c:148
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_num_mem_rsv
  - lib/fdt_ro.c:fdt_get_mem_rsv
```
**Symbols:**

```
c000000000ec4a50-c000000000ec4aa8: fdt_mem_rsv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct fdt_reserve_entry *fdt_mem_rsv(const void *fdt, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008af7c0)
Location: scripts/dtc/libfdt/fdt_ro.c:148
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_num_mem_rsv
  - lib/fdt_ro.c:fdt_get_mem_rsv
```
**Symbols:**

```
ffffffe0008af7c0-ffffffe0008af83e: fdt_mem_rsv (STB_LOCAL)
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
