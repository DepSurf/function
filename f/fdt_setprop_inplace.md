# Function: <code>fdt_setprop_inplace</code>

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
int fdt_setprop_inplace(void *fdt, int nodeoffset, const char *name, const void *val, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_wip.c (ffff800011440b28)
Location: scripts/dtc/libfdt/fdt_wip.c:33
Inline: False
Direct callers:
  - drivers/firmware/efi/libstub/fdt.c:exit_boot_func
  - drivers/firmware/efi/libstub/fdt.c:exit_boot_func
  - drivers/firmware/efi/libstub/fdt.c:exit_boot_func
  - drivers/firmware/efi/libstub/fdt.c:exit_boot_func
```
**Symbols:**

```
ffff800010d87e30-ffff800010d87eec: fdt_setprop_inplace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_setprop_inplace(void *fdt, int nodeoffset, const char *name, const void *val, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_wip.c (c0e82c98)
Location: scripts/dtc/libfdt/fdt_wip.c:33
Inline: False
```
**Symbols:**

```
c0e82c98-c0e82d48: fdt_setprop_inplace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_setprop_inplace(void *fdt, int nodeoffset, const char *name, const void *val, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_wip.c (c000000000ec8280)
Location: scripts/dtc/libfdt/fdt_wip.c:33
Inline: False
```
**Symbols:**

```
c000000000ec8280-c000000000ec8370: fdt_setprop_inplace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_setprop_inplace(void *fdt, int nodeoffset, const char *name, const void *val, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_wip.c (ffffffe0008b2016)
Location: scripts/dtc/libfdt/fdt_wip.c:33
Inline: False
```
**Symbols:**

```
ffffffe0008b2016-ffffffe0008b208a: fdt_setprop_inplace (STB_GLOBAL)
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
