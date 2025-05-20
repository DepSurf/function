# Function: <code>fdt_splice_mem_rsv_</code>

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
int fdt_splice_mem_rsv_(void *fdt, struct fdt_reserve_entry *p, int oldn, int newn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffff80001143f618)
Location: scripts/dtc/libfdt/fdt_rw.c:67
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
ffff800010d87138-ffff800010d8719c: fdt_splice_mem_rsv_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_splice_mem_rsv_(void *fdt, struct fdt_reserve_entry *p, int oldn, int newn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c0e81fac)
Location: scripts/dtc/libfdt/fdt_rw.c:67
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
c0e81fac-c0e8200c: fdt_splice_mem_rsv_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_splice_mem_rsv_(void *fdt, struct fdt_reserve_entry *p, int oldn, int newn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c000000000ec6dd0)
Location: scripts/dtc/libfdt/fdt_rw.c:67
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
c000000000ec6dd0-c000000000ec6e74: fdt_splice_mem_rsv_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_splice_mem_rsv_(void *fdt, struct fdt_reserve_entry *p, int oldn, int newn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffffffe0008b0e96)
Location: scripts/dtc/libfdt/fdt_rw.c:67
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
ffffffe0008b0e96-ffffffe0008b0f72: fdt_splice_mem_rsv_ (STB_LOCAL)
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
