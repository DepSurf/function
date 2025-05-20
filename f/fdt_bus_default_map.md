# Function: <code>fdt_bus_default_map</code>

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
u64 fdt_bus_default_map(__be32 *addr, const __be32 *range, int na, int ns, int pna);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (ffff8000114ab9a4)
Location: drivers/of/fdt_address.c:70
Inline: False
```
**Symbols:**

```
ffff8000114ab9a4-ffff8000114aba68: fdt_bus_default_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 fdt_bus_default_map(__be32 *addr, const __be32 *range, int na, int ns, int pna);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (c15b00a4)
Location: drivers/of/fdt_address.c:70
Inline: False
```
**Symbols:**

```
c15b00a4-c15b01b8: fdt_bus_default_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 fdt_bus_default_map(__be32 *addr, const __be32 *range, int na, int ns, int pna);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (c0000000013bbc10)
Location: drivers/of/fdt_address.c:70
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:fdt_translate_address
```
**Symbols:**

```
c0000000013bbc10-c0000000013bbd30: fdt_bus_default_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 fdt_bus_default_map(__be32 *addr, const __be32 *range, int na, int ns, int pna);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt_address.c (ffffffe00003bcd8)
Location: drivers/of/fdt_address.c:70
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:fdt_translate_address
```
**Symbols:**

```
ffffffe00003bcd8-ffffffe00003bd7a: fdt_bus_default_map (STB_LOCAL)
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
