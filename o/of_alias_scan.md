# Function: <code>of_alias_scan</code>

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
void of_alias_scan(void * (*dt_alloc)(u64, u64));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6bfb0)
Location: drivers/of/base.c:1994
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_device_tree
```
**Symbols:**

```
ffff800010b6bfb0-ffff800010b6c238: of_alias_scan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void of_alias_scan(void * (*dt_alloc)(u64, u64));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4f1a4)
Location: drivers/of/base.c:1994
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_device_tree
```
**Symbols:**

```
c0c4f1a4-c0c4f484: of_alias_scan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void of_alias_scan(void * (*dt_alloc)(u64, u64));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c460c0)
Location: drivers/of/base.c:1994
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_device_tree
```
**Symbols:**

```
c000000000c460c0-c000000000c46844: of_alias_scan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void of_alias_scan(void * (*dt_alloc)(u64, u64));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe000721218)
Location: drivers/of/base.c:1994
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_device_tree
```
**Symbols:**

```
ffffffe000721218-ffffffe00072147a: of_alias_scan (STB_GLOBAL)
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
