# Function: <code>spi_map_buf_attrs</code>

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
int spi_map_buf_attrs(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd03b0)
Location: drivers/spi/spi.c:1025
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_buf
```
**Symbols:**

```
ffffffff81bd03b0-ffffffff81bd0629: spi_map_buf_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int spi_map_buf_attrs(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c28030)
Location: drivers/spi/spi.c:1025
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_buf
```
**Symbols:**

```
ffffffff81c28030-ffffffff81c282a9: spi_map_buf_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int spi_map_buf_attrs(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cda780)
Location: drivers/spi/spi.c:1095
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_buf
```
**Symbols:**

```
ffffffff81cda780-ffffffff81cda9f9: spi_map_buf_attrs (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
