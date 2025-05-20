# Function: <code>spi_take_timestamp_post</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void spi_take_timestamp_post(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81877e70)
Location: drivers/spi/spi.c:1561
Inline: False
```
**Symbols:**

```
ffffffff81877e70-ffffffff81877edb: spi_take_timestamp_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void spi_take_timestamp_post(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81886780)
Location: drivers/spi/spi.c:1606
Inline: False
```
**Symbols:**

```
ffffffff81886780-ffffffff818867eb: spi_take_timestamp_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void spi_take_timestamp_post(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81868fd0)
Location: drivers/spi/spi.c:1618
Inline: False
```
**Symbols:**

```
ffffffff81868fd0-ffffffff8186903e: spi_take_timestamp_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_take_timestamp_post(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff818f9422)
Location: drivers/spi/spi.c:1697
Inline: True
```
**Symbols:**

```
ffffffff81d0f8f9-ffffffff81d0f90e: spi_take_timestamp_post.cold (STB_LOCAL)
ffffffff818f93e0-ffffffff818f9460: spi_take_timestamp_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_take_timestamp_post(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a4aa96)
Location: drivers/spi/spi.c:1739
Inline: True
```
**Symbols:**

```
ffffffff81eda5e7-ffffffff81eda5fc: spi_take_timestamp_post.cold (STB_LOCAL)
ffffffff81a4aa50-ffffffff81a4aafd: spi_take_timestamp_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_take_timestamp_post(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd1886)
Location: drivers/spi/spi.c:1901
Inline: True
```
**Symbols:**

```
ffffffff8209d02f-ffffffff8209d044: spi_take_timestamp_post.cold (STB_LOCAL)
ffffffff81bd1840-ffffffff81bd18ed: spi_take_timestamp_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void spi_take_timestamp_post(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c28320)
Location: drivers/spi/spi.c:1908
Inline: False
```
**Symbols:**

```
ffffffff81c28320-ffffffff81c283b7: spi_take_timestamp_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void spi_take_timestamp_post(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cdaa70)
Location: drivers/spi/spi.c:1985
Inline: False
```
**Symbols:**

```
ffffffff81cdaa70-ffffffff81cdab07: spi_take_timestamp_post (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
