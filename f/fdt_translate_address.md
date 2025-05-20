# Function: <code>fdt_translate_address</code>

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
u64 fdt_translate_address(const void *blob, int node_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (ffff8000114abcf4)
Location: drivers/of/fdt_address.c:163
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
```
**Symbols:**

```
ffff8000114abcf4-ffff8000114abf94: fdt_translate_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (c15b0494)
Location: drivers/of/fdt_address.c:163
Inline: True
Inline callers:
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 fdt_translate_address(const void *blob, int node_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (c0000000013bbe00)
Location: drivers/of/fdt_address.c:163
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
```
**Symbols:**

```
c0000000013bbe00-c0000000013bc334: fdt_translate_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 fdt_translate_address(const void *blob, int node_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (ffffffe00003be2e)
Location: drivers/of/fdt_address.c:163
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
```
**Symbols:**

```
ffffffe00003be2e-ffffffe00003c1d2: fdt_translate_address (STB_LOCAL)
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
