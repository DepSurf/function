# Function: <code>fdt_stringlist_contains</code>

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
int fdt_stringlist_contains(const char *strlist, int listlen, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143eed8)
Location: scripts/dtc/libfdt/fdt_ro.c:681
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_node_check_compatible
  - lib/fdt_ro.c:fdt_node_check_compatible
```
**Symbols:**

```
ffff800010d86930-ffff800010d869ec: fdt_stringlist_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_stringlist_contains(const char *strlist, int listlen, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e818a8)
Location: scripts/dtc/libfdt/fdt_ro.c:681
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_node_check_compatible
```
**Symbols:**

```
c0e818a8-c0e81938: fdt_stringlist_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_stringlist_contains(const char *strlist, int listlen, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec6370)
Location: scripts/dtc/libfdt/fdt_ro.c:681
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_node_check_compatible
```
**Symbols:**

```
c000000000ec6370-c000000000ec6480: fdt_stringlist_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_stringlist_contains(const char *strlist, int listlen, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008b087c)
Location: scripts/dtc/libfdt/fdt_ro.c:681
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_node_check_compatible
```
**Symbols:**

```
ffffffe0008b087c-ffffffe0008b08fa: fdt_stringlist_contains (STB_GLOBAL)
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
