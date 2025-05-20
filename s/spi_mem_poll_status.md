# Function: <code>spi_mem_poll_status</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int spi_mem_poll_status(struct spi_mem *mem, const struct spi_mem_op *op, u16 mask, u16 match, long unsigned int initial_delay_us, long unsigned int polling_delay_us, u16 timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff818ff910)
Location: drivers/spi/spi-mem.c:782
Inline: False
```
**Symbols:**

```
ffffffff818ff910-ffffffff818ffb32: spi_mem_poll_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int spi_mem_poll_status(struct spi_mem *mem, const struct spi_mem_op *op, u16 mask, u16 match, long unsigned int initial_delay_us, long unsigned int polling_delay_us, u16 timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81a50eb0)
Location: drivers/spi/spi-mem.c:795
Inline: False
```
**Symbols:**

```
ffffffff81a50eb0-ffffffff81a5110d: spi_mem_poll_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int spi_mem_poll_status(struct spi_mem *mem, const struct spi_mem_op *op, u16 mask, u16 match, long unsigned int initial_delay_us, long unsigned int polling_delay_us, u16 timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81bda0b0)
Location: drivers/spi/spi-mem.c:795
Inline: False
```
**Symbols:**

```
ffffffff81bda0b0-ffffffff81bda30d: spi_mem_poll_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int spi_mem_poll_status(struct spi_mem *mem, const struct spi_mem_op *op, u16 mask, u16 match, long unsigned int initial_delay_us, long unsigned int polling_delay_us, u16 timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81c30b30)
Location: drivers/spi/spi-mem.c:795
Inline: False
```
**Symbols:**

```
ffffffff81c30b30-ffffffff81c30da2: spi_mem_poll_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int spi_mem_poll_status(struct spi_mem *mem, const struct spi_mem_op *op, u16 mask, u16 match, long unsigned int initial_delay_us, long unsigned int polling_delay_us, u16 timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81ce39c0)
Location: drivers/spi/spi-mem.c:795
Inline: False
```
**Symbols:**

```
ffffffff81ce39c0-ffffffff81ce3c32: spi_mem_poll_status (STB_GLOBAL)
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
