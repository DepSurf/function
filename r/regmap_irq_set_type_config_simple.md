# Function: <code>regmap_irq_set_type_config_simple</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regmap_irq_set_type_config_simple(unsigned int **buf, unsigned int type, const struct regmap_irq *irq_data, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81b26250)
Location: drivers/base/regmap/regmap-irq.c:663
Inline: False
```
**Symbols:**

```
ffffffff81b26250-ffffffff81b2630d: regmap_irq_set_type_config_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regmap_irq_set_type_config_simple(unsigned int **buf, unsigned int type, const struct regmap_irq *irq_data, int idx, void *irq_drv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81b76120)
Location: drivers/base/regmap/regmap-irq.c:567
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_set_type
```
**Symbols:**

```
ffffffff81b76120-ffffffff81b761de: regmap_irq_set_type_config_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regmap_irq_set_type_config_simple(unsigned int **buf, unsigned int type, const struct regmap_irq *irq_data, int idx, void *irq_drv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81bc9ef0)
Location: drivers/base/regmap/regmap-irq.c:567
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_set_type
```
**Symbols:**

```
ffffffff81bc9ef0-ffffffff81bc9fae: regmap_irq_set_type_config_simple (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *irq_drv_data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
