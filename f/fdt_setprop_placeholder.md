# Function: <code>fdt_setprop_placeholder</code>

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
int fdt_setprop_placeholder(void *fdt, int nodeoffset, const char *name, int len, void **prop_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffff80001143fbc0)
Location: scripts/dtc/libfdt/fdt_rw.c:243
Inline: True
Direct callers:
  - lib/fdt_rw.c:fdt_setprop
  - lib/fdt_rw.c:fdt_setprop
```
**Symbols:**

```
ffff800010d87600-ffff800010d87714: fdt_setprop_placeholder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fdt_setprop_placeholder(void *fdt, int nodeoffset, const char *name, int len, void **prop_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c0e824b0)
Location: scripts/dtc/libfdt/fdt_rw.c:243
Inline: True
Direct callers:
  - lib/fdt_rw.c:fdt_setprop
```
**Symbols:**

```
c0e824b0-c0e825c4: fdt_setprop_placeholder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fdt_setprop_placeholder(void *fdt, int nodeoffset, const char *name, int len, void **prop_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c000000000ec7660)
Location: scripts/dtc/libfdt/fdt_rw.c:243
Inline: True
Direct callers:
  - lib/fdt_rw.c:fdt_setprop
```
**Symbols:**

```
c000000000ec7660-c000000000ec7804: fdt_setprop_placeholder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fdt_setprop_placeholder(void *fdt, int nodeoffset, const char *name, int len, void **prop_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffffffe0008b17ce)
Location: scripts/dtc/libfdt/fdt_rw.c:243
Inline: True
Direct callers:
  - lib/fdt_rw.c:fdt_setprop
```
**Symbols:**

```
ffffffe0008b17ce-ffffffe0008b18b0: fdt_setprop_placeholder (STB_GLOBAL)
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
