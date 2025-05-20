# Function: <code>mvebu_gpioreg_level_mask</code>

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
void mvebu_gpioreg_level_mask(struct mvebu_gpio_chip *mvchip, struct regmap **map, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mvebu.c (ffff8000106d1510)
Location: drivers/gpio/gpio-mvebu.c:233
Inline: True
Direct callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_level_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_level_mask
```
**Symbols:**

```
ffff8000106d1510-ffff8000106d15f4: mvebu_gpioreg_level_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mvebu_gpioreg_level_mask(struct mvebu_gpio_chip *mvchip, struct regmap **map, unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mvebu.c (c086ab38)
Location: drivers/gpio/gpio-mvebu.c:233
Inline: True
Direct callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_level_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_level_mask
```
**Symbols:**

```
c086ab38-c086abe0: mvebu_gpioreg_level_mask (STB_LOCAL)
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
