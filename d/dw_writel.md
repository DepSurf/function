# Function: <code>dw_writel</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dw_writel(struct dw_i2c_dev *dev, u32 b, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81726125)
Location: drivers/i2c/busses/i2c-designware-common.c:83
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81725c80-ffffffff81725cbb: dw_writel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dw_writel(struct dw_i2c_dev *dev, u32 b, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81797775)
Location: drivers/i2c/busses/i2c-designware-common.c:83
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff817972d0-ffffffff8179730b: dw_writel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dw_writel(struct dw_i2c_dev *dev, u32 b, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817da375)
Location: drivers/i2c/busses/i2c-designware-common.c:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff817d9ef0-ffffffff817d9f2b: dw_writel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dw_writel(struct dw_i2c_dev *dev, u32 b, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81801795)
Location: drivers/i2c/busses/i2c-designware-common.c:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81801100-ffffffff8180113b: dw_writel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dw_writel(struct dw_i2c_dev *dev, u32 b, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81842a45)
Location: drivers/i2c/busses/i2c-designware-common.c:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81842490-ffffffff818424cd: dw_writel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dw_writel(struct dw_i2c_dev *dev, u32 b, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818743c5)
Location: drivers/i2c/busses/i2c-designware-common.c:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81873e10-ffffffff81873e4d: dw_writel (STB_GLOBAL)
```
</details>
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
void dw_writel(struct dw_i2c_dev *dev, u32 b, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab9350)
Location: drivers/i2c/busses/i2c-designware-common.c:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffff800010ab8b70-ffff800010ab8bec: dw_writel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dw_writel(struct dw_i2c_dev *dev, u32 b, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c0b98984)
Location: drivers/i2c/busses/i2c-designware-common.c:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c0b981fc-c0b98250: dw_writel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dw_writel(struct dw_i2c_dev *dev, u32 b, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9bb10)
Location: drivers/i2c/busses/i2c-designware-common.c:72
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c000000000b9bb10-c000000000b9bb94: dw_writel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dw_writel(struct dw_i2c_dev *dev, u32 b, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006be166)
Location: drivers/i2c/busses/i2c-designware-common.c:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffe0006bda98-ffffffe0006bdb20: dw_writel (STB_GLOBAL)
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
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dw_writel(struct dw_i2c_dev *dev, u32 b, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81869875)
Location: drivers/i2c/busses/i2c-designware-common.c:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff818692c0-ffffffff818692fd: dw_writel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dw_writel(struct dw_i2c_dev *dev, u32 b, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81883805)
Location: drivers/i2c/busses/i2c-designware-common.c:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81883250-ffffffff8188328d: dw_writel (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
