# Function: <code>mvebu_gpioreg_edge_cause</code>

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
void mvebu_gpioreg_edge_cause(struct mvebu_gpio_chip *mvchip, struct regmap **map, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mvebu.c (ffff8000106d0de8)
Location: drivers/gpio/gpio-mvebu.c:137
Inline: True
Direct callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_ack
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_edge_cause
```
**Symbols:**

```
ffff8000106d0de8-ffff8000106d0e88: mvebu_gpioreg_edge_cause (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mvebu_gpioreg_edge_cause(struct mvebu_gpio_chip *mvchip, struct regmap **map, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mvebu.c (c086ad70)
Location: drivers/gpio/gpio-mvebu.c:137
Inline: True
Direct callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_ack
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_edge_cause
```
**Symbols:**

```
c086ad70-c086ade8: mvebu_gpioreg_edge_cause (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
