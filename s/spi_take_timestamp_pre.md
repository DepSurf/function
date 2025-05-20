# Function: <code>spi_take_timestamp_pre</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void spi_take_timestamp_pre(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81878730)
Location: drivers/spi/spi.c:1524
Inline: True
```
**Symbols:**

```
ffffffff81878730-ffffffff81878785: spi_take_timestamp_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void spi_take_timestamp_pre(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81886fe0)
Location: drivers/spi/spi.c:1569
Inline: True
```
**Symbols:**

```
ffffffff81886fe0-ffffffff81887035: spi_take_timestamp_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void spi_take_timestamp_pre(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81869840)
Location: drivers/spi/spi.c:1581
Inline: True
```
**Symbols:**

```
ffffffff81869840-ffffffff81869895: spi_take_timestamp_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_take_timestamp_pre(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff818f939c)
Location: drivers/spi/spi.c:1660
Inline: True
```
**Symbols:**

```
ffffffff81d0f8d6-ffffffff81d0f8f9: spi_take_timestamp_pre.cold (STB_LOCAL)
ffffffff818f9360-ffffffff818f93d7: spi_take_timestamp_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_take_timestamp_pre(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a4a980)
Location: drivers/spi/spi.c:1702
Inline: True
```
**Symbols:**

```
ffffffff81a4a980-ffffffff81a4a9cb: spi_take_timestamp_pre.part.0 (STB_LOCAL)
ffffffff81eda5c4-ffffffff81eda5e7: spi_take_timestamp_pre.cold (STB_LOCAL)
ffffffff81a4a9d0-ffffffff81a4aa42: spi_take_timestamp_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_take_timestamp_pre(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd1740)
Location: drivers/spi/spi.c:1864
Inline: True
```
**Symbols:**

```
ffffffff81bd1740-ffffffff81bd179a: spi_take_timestamp_pre.part.0 (STB_LOCAL)
ffffffff8209d00c-ffffffff8209d02f: spi_take_timestamp_pre.cold (STB_LOCAL)
ffffffff81bd17b0-ffffffff81bd1822: spi_take_timestamp_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_take_timestamp_pre(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c291b0)
Location: drivers/spi/spi.c:1871
Inline: True
```
**Symbols:**

```
ffffffff81c291b0-ffffffff81c2920a: spi_take_timestamp_pre.part.0 (STB_LOCAL)
ffffffff81c29220-ffffffff81c29265: spi_take_timestamp_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_take_timestamp_pre(struct spi_controller *ctlr, struct spi_transfer *xfer, size_t progress, bool irqs_off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cdbbf0)
Location: drivers/spi/spi.c:1948
Inline: True
```
**Symbols:**

```
ffffffff81cdbbf0-ffffffff81cdbc4a: spi_take_timestamp_pre.part.0 (STB_LOCAL)
ffffffff81cdbc60-ffffffff81cdbca5: spi_take_timestamp_pre (STB_GLOBAL)
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
