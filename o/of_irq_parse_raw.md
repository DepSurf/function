# Function: <code>of_irq_parse_raw</code>

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
int of_irq_parse_raw(const __be32 *addr, struct of_phandle_args *out_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffff800010b74710)
Location: drivers/of/irq.c:93
Inline: False
Direct callers:
  - drivers/pci/of.c:of_irq_parse_and_map_pci
  - drivers/of/irq.c:of_irq_parse_one
  - drivers/of/irq.c:of_irq_parse_one
```
**Symbols:**

```
ffff800010b74710-ffff800010b74de8: of_irq_parse_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_irq_parse_raw(const __be32 *addr, struct of_phandle_args *out_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c0c56b30)
Location: drivers/of/irq.c:93
Inline: False
Direct callers:
  - drivers/pci/of.c:of_irq_parse_and_map_pci
  - drivers/of/irq.c:of_irq_parse_one
  - drivers/of/irq.c:of_irq_parse_one
```
**Symbols:**

```
c0c56b30-c0c57294: of_irq_parse_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_irq_parse_raw(const __be32 *addr, struct of_phandle_args *out_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c000000000c51820)
Location: drivers/of/irq.c:93
Inline: False
Direct callers:
  - drivers/pci/of.c:of_irq_parse_and_map_pci
  - drivers/of/irq.c:of_irq_parse_one
  - drivers/of/irq.c:of_irq_parse_one
```
**Symbols:**

```
c000000000c51820-c000000000c5214c: of_irq_parse_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_irq_parse_raw(const __be32 *addr, struct of_phandle_args *out_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffffffe00072801c)
Location: drivers/of/irq.c:93
Inline: False
Direct callers:
  - drivers/pci/of.c:of_irq_parse_and_map_pci
  - drivers/of/irq.c:of_irq_parse_one
  - drivers/of/irq.c:of_irq_parse_one
```
**Symbols:**

```
ffffffe00072801c-ffffffe0007286f0: of_irq_parse_raw (STB_GLOBAL)
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
