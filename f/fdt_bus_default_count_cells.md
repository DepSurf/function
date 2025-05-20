# Function: <code>fdt_bus_default_count_cells</code>

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
void fdt_bus_default_count_cells(const void *blob, int parentoffset, int *addrc, int *sizec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (ffff8000114ab8f4)
Location: drivers/of/fdt_address.c:48
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
```
**Symbols:**

```
ffff8000114ab8f4-ffff8000114ab9a4: fdt_bus_default_count_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fdt_bus_default_count_cells(const void *blob, int parentoffset, int *addrc, int *sizec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (c15b0010)
Location: drivers/of/fdt_address.c:48
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
```
**Symbols:**

```
c15b0010-c15b00a4: fdt_bus_default_count_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fdt_bus_default_count_cells(const void *blob, int parentoffset, int *addrc, int *sizec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (c0000000013bbb30)
Location: drivers/of/fdt_address.c:48
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
```
**Symbols:**

```
c0000000013bbb30-c0000000013bbc10: fdt_bus_default_count_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fdt_bus_default_count_cells(const void *blob, int parentoffset, int *addrc, int *sizec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (ffffffe00003bc04)
Location: drivers/of/fdt_address.c:48
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
```
**Symbols:**

```
ffffffe00003bc04-ffffffe00003bcd8: fdt_bus_default_count_cells (STB_LOCAL)
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
