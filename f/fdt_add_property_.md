# Function: <code>fdt_add_property_</code>

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
int fdt_add_property_(void *fdt, int nodeoffset, const char *name, int len, struct fdt_property **prop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffff80001143f800)
Location: scripts/dtc/libfdt/fdt_rw.c:188
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_appendprop
```
**Symbols:**

```
ffff800010d87250-ffff800010d87408: fdt_add_property_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_add_property_(void *fdt, int nodeoffset, const char *name, int len, struct fdt_property **prop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c0e820f4)
Location: scripts/dtc/libfdt/fdt_rw.c:188
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_appendprop
```
**Symbols:**

```
c0e820f4-c0e82274: fdt_add_property_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_add_property_(void *fdt, int nodeoffset, const char *name, int len, struct fdt_property **prop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c000000000ec7020)
Location: scripts/dtc/libfdt/fdt_rw.c:188
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_appendprop
```
**Symbols:**

```
c000000000ec7020-c000000000ec7280: fdt_add_property_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_add_property_(void *fdt, int nodeoffset, const char *name, int len, struct fdt_property **prop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffffffe0008b12a4)
Location: scripts/dtc/libfdt/fdt_rw.c:188
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_appendprop
```
**Symbols:**

```
ffffffe0008b12a4-ffffffe0008b1564: fdt_add_property_ (STB_LOCAL)
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
