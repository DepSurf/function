# Function: <code>mpc8xxx_spi_probe</code>

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
void mpc8xxx_spi_probe(struct device *dev, struct resource *mem, unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-lib.c (ffff8000109cb670)
Location: drivers/spi/spi-fsl-lib.c:80
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
**Symbols:**

```
ffff8000109cb670-ffff8000109cb70c: mpc8xxx_spi_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mpc8xxx_spi_probe(struct device *dev, struct resource *mem, unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-lib.c (c0ab4920)
Location: drivers/spi/spi-fsl-lib.c:80
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
**Symbols:**

```
c0ab4920-c0ab49c4: mpc8xxx_spi_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mpc8xxx_spi_probe(struct device *dev, struct resource *mem, unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-lib.c (c000000000a8d430)
Location: drivers/spi/spi-fsl-lib.c:80
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
**Symbols:**

```
c000000000a8d430-c000000000a8d4f0: mpc8xxx_spi_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mpc8xxx_spi_probe(struct device *dev, struct resource *mem, unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-fsl-lib.c (ffffffe00061ad7a)
Location: drivers/spi/spi-fsl-lib.c:80
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
**Symbols:**

```
ffffffe00061ad7a-ffffffe00061ae0e: mpc8xxx_spi_probe (STB_GLOBAL)
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
