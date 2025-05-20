# Function: <code>of_modalias_node</code>

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
int of_modalias_node(struct device_node *node, char *modalias, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b69070)
Location: drivers/of/base.c:1201
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_register
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/i2c/i2c-core-of.c:of_i2c_get_board_info
```
**Symbols:**

```
ffff800010b69070-ffff800010b69130: of_modalias_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_modalias_node(struct device_node *node, char *modalias, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4cb6c)
Location: drivers/of/base.c:1201
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_register
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/i2c/i2c-core-of.c:of_i2c_get_board_info
```
**Symbols:**

```
c0c4cb6c-c0c4cc2c: of_modalias_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_modalias_node(struct device_node *node, char *modalias, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c41f00)
Location: drivers/of/base.c:1201
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_register
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/i2c/i2c-core-of.c:of_i2c_get_board_info
```
**Symbols:**

```
c000000000c41f00-c000000000c42008: of_modalias_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_modalias_node(struct device_node *node, char *modalias, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071ee7c)
Location: drivers/of/base.c:1201
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_register
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/i2c/i2c-core-of.c:of_i2c_get_board_info
```
**Symbols:**

```
ffffffe00071ee7c-ffffffe00071ef0a: of_modalias_node (STB_GLOBAL)
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
