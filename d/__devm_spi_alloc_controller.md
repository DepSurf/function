# Function: <code>__devm_spi_alloc_controller</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct spi_controller *__devm_spi_alloc_controller(struct device *dev, unsigned int size, bool slave);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81889230)
Location: drivers/spi/spi.c:2478
Inline: False
```
**Symbols:**

```
ffffffff81889230-ffffffff818892b5: __devm_spi_alloc_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct spi_controller *__devm_spi_alloc_controller(struct device *dev, unsigned int size, bool slave);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8186b7c0)
Location: drivers/spi/spi.c:2497
Inline: False
```
**Symbols:**

```
ffffffff8186b7c0-ffffffff8186b850: __devm_spi_alloc_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct spi_controller *__devm_spi_alloc_controller(struct device *dev, unsigned int size, bool slave);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818fb470)
Location: drivers/spi/spi.c:2631
Inline: False
```
**Symbols:**

```
ffffffff818fb470-ffffffff818fb507: __devm_spi_alloc_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct spi_controller *__devm_spi_alloc_controller(struct device *dev, unsigned int size, bool slave);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a4cf20)
Location: drivers/spi/spi.c:2779
Inline: False
```
**Symbols:**

```
ffffffff81a4cf20-ffffffff81a4cfb4: __devm_spi_alloc_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct spi_controller *__devm_spi_alloc_controller(struct device *dev, unsigned int size, bool slave);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd51a0)
Location: drivers/spi/spi.c:2962
Inline: False
```
**Symbols:**

```
ffffffff81bd51a0-ffffffff81bd5234: __devm_spi_alloc_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct spi_controller *__devm_spi_alloc_controller(struct device *dev, unsigned int size, bool slave);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2c010)
Location: drivers/spi/spi.c:2969
Inline: False
```
**Symbols:**

```
ffffffff81c2c010-ffffffff81c2c0a4: __devm_spi_alloc_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct spi_controller *__devm_spi_alloc_controller(struct device *dev, unsigned int size, bool slave);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cde930)
Location: drivers/spi/spi.c:3122
Inline: False
```
**Symbols:**

```
ffffffff81cde930-ffffffff81cde9c4: __devm_spi_alloc_controller (STB_GLOBAL)
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
