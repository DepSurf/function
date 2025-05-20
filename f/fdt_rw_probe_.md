# Function: <code>fdt_rw_probe_</code>

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
int fdt_rw_probe_(void *fdt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffff80001143f680)
Location: scripts/dtc/libfdt/fdt_rw.c:25
Inline: True
Direct callers:
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_add_subnode_namelen
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_setprop_placeholder
  - lib/fdt_rw.c:fdt_set_name
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_add_subnode_namelen
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_setprop_placeholder
  - lib/fdt_rw.c:fdt_set_name
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
ffff800010d87068-ffff800010d870d4: fdt_rw_probe_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fdt_rw_probe_(void *fdt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c0e82274)
Location: scripts/dtc/libfdt/fdt_rw.c:25
Inline: True
Direct callers:
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_add_subnode_namelen
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_setprop_placeholder
  - lib/fdt_rw.c:fdt_set_name
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
c0e82274-c0e822dc: fdt_rw_probe_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fdt_rw_probe_(void *fdt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c000000000ec7280)
Location: scripts/dtc/libfdt/fdt_rw.c:25
Inline: True
Direct callers:
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_add_subnode_namelen
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_setprop_placeholder
  - lib/fdt_rw.c:fdt_set_name
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
c000000000ec7280-c000000000ec7348: fdt_rw_probe_ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fdt_rw_probe_(void *fdt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffffffe0008b0f72)
Location: scripts/dtc/libfdt/fdt_rw.c:25
Inline: True
Direct callers:
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_add_subnode_namelen
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_setprop_placeholder
  - lib/fdt_rw.c:fdt_set_name
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
ffffffe0008b0f72-ffffffe0008b100c: fdt_rw_probe_ (STB_LOCAL)
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
