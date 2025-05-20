# Function: <code>hsu_dma_do_irq</code>

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
int hsu_dma_do_irq(struct hsu_dma_chip *chip, short unsigned int nr, u32 status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/hsu/hsu.c (ffffffff81a07760)
Location: drivers/dma/hsu/hsu.c:210
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:tng_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:tng_handle_irq
```
**Symbols:**

```
ffffffff81a07760-ffffffff81a07919: hsu_dma_do_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hsu_dma_do_irq(struct hsu_dma_chip *chip, short unsigned int nr, u32 status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/hsu/hsu.c (ffffffff81a505f0)
Location: drivers/dma/hsu/hsu.c:210
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:tng_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:tng_handle_irq
```
**Symbols:**

```
ffffffff81a505f0-ffffffff81a507a9: hsu_dma_do_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hsu_dma_do_irq(struct hsu_dma_chip *chip, short unsigned int nr, u32 status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/hsu/hsu.c (ffffffff81a9c2c0)
Location: drivers/dma/hsu/hsu.c:210
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:tng_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:tng_handle_irq
```
**Symbols:**

```
ffffffff81a9c2c0-ffffffff81a9c479: hsu_dma_do_irq (STB_GLOBAL)
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
