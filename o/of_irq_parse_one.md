# Function: <code>of_irq_parse_one</code>

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
int of_irq_parse_one(struct device_node *device, int index, struct of_phandle_args *out_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffff800010b74de8)
Location: drivers/of/irq.c:286
Inline: False
Direct callers:
  - drivers/pci/of.c:of_irq_parse_and_map_pci
  - drivers/of/irq.c:of_irq_count
  - drivers/of/irq.c:of_irq_get
  - drivers/of/irq.c:irq_of_parse_and_map
```
**Symbols:**

```
ffff800010b74de8-ffff800010b74fd0: of_irq_parse_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_irq_parse_one(struct device_node *device, int index, struct of_phandle_args *out_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c0c57294)
Location: drivers/of/irq.c:286
Inline: False
Direct callers:
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
  - drivers/pci/of.c:of_irq_parse_and_map_pci
  - drivers/of/irq.c:of_irq_count
  - drivers/of/irq.c:of_irq_get
  - drivers/of/irq.c:irq_of_parse_and_map
```
**Symbols:**

```
c0c57294-c0c574a8: of_irq_parse_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_irq_parse_one(struct device_node *device, int index, struct of_phandle_args *out_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c000000000c52150)
Location: drivers/of/irq.c:286
Inline: False
Direct callers:
  - drivers/pci/of.c:of_irq_parse_and_map_pci
  - drivers/of/irq.c:of_irq_count
  - drivers/of/irq.c:of_irq_get
  - drivers/of/irq.c:irq_of_parse_and_map
```
**Symbols:**

```
c000000000c52150-c000000000c523f4: of_irq_parse_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_irq_parse_one(struct device_node *device, int index, struct of_phandle_args *out_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffffffe0007286f0)
Location: drivers/of/irq.c:286
Inline: False
Direct callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_init
  - drivers/pci/of.c:of_irq_parse_and_map_pci
  - drivers/of/irq.c:of_irq_count
  - drivers/of/irq.c:of_irq_get
  - drivers/of/irq.c:irq_of_parse_and_map
```
**Symbols:**

```
ffffffe0007286f0-ffffffe00072889c: of_irq_parse_one (STB_GLOBAL)
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
