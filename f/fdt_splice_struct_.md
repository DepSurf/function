# Function: <code>fdt_splice_struct_</code>

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
int fdt_splice_struct_(void *fdt, void *p, int oldlen, int newlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffff80001143f7a0)
Location: scripts/dtc/libfdt/fdt_rw.c:80
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_set_name
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_set_name
  - lib/fdt_rw.c:fdt_add_property_
```
**Symbols:**

```
ffff800010d870d8-ffff800010d87138: fdt_splice_struct_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_splice_struct_(void *fdt, void *p, int oldlen, int newlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c0e8200c)
Location: scripts/dtc/libfdt/fdt_rw.c:80
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_set_name
  - lib/fdt_rw.c:fdt_add_property_
```
**Symbols:**

```
c0e8200c-c0e82060: fdt_splice_struct_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_splice_struct_(void *fdt, void *p, int oldlen, int newlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c000000000ec6e80)
Location: scripts/dtc/libfdt/fdt_rw.c:80
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_set_name
  - lib/fdt_rw.c:fdt_add_property_
```
**Symbols:**

```
c000000000ec6e80-c000000000ec6f10: fdt_splice_struct_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_splice_struct_(void *fdt, void *p, int oldlen, int newlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffffffe0008b11d4)
Location: scripts/dtc/libfdt/fdt_rw.c:80
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_set_name
  - lib/fdt_rw.c:fdt_add_property_
```
**Symbols:**

```
ffffffe0008b11d4-ffffffe0008b12a4: fdt_splice_struct_ (STB_LOCAL)
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
