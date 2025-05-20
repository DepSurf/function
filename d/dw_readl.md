# Function: <code>dw_readl</code>

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
u32 dw_readl(struct dw_i2c_dev *dev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81725be5)
Location: drivers/i2c/busses/i2c-designware-common.c:67
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81725c30-ffffffff81725c7c: dw_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u32 dw_readl(struct dw_i2c_dev *dev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81797235)
Location: drivers/i2c/busses/i2c-designware-common.c:67
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81797280-ffffffff817972cc: dw_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u32 dw_readl(struct dw_i2c_dev *dev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817d9df5)
Location: drivers/i2c/busses/i2c-designware-common.c:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
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
ffffffff817d9ea0-ffffffff817d9eec: dw_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u32 dw_readl(struct dw_i2c_dev *dev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81801005)
Location: drivers/i2c/busses/i2c-designware-common.c:56
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
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
ffffffff818010b0-ffffffff818010fc: dw_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u32 dw_readl(struct dw_i2c_dev *dev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81842315)
Location: drivers/i2c/busses/i2c-designware-common.c:56
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81842440-ffffffff8184248c: dw_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u32 dw_readl(struct dw_i2c_dev *dev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81873c95)
Location: drivers/i2c/busses/i2c-designware-common.c:56
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81873dc0-ffffffff81873e0c: dw_readl (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
u32 dw_readl(struct dw_i2c_dev *dev, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab8ac0)
Location: drivers/i2c/busses/i2c-designware-common.c:56
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffff800010ab8ac0-ffff800010ab8b3c: dw_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 dw_readl(struct dw_i2c_dev *dev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c0b980b4)
Location: drivers/i2c/busses/i2c-designware-common.c:56
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c0b981a8-c0b981fc: dw_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 dw_readl(struct dw_i2c_dev *dev, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9b940)
Location: drivers/i2c/busses/i2c-designware-common.c:56
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c000000000b9b940-c000000000b9bae8: dw_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 dw_readl(struct dw_i2c_dev *dev, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bd9e8)
Location: drivers/i2c/busses/i2c-designware-common.c:56
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffe0006bd9e8-ffffffe0006bda68: dw_readl (STB_GLOBAL)
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
u32 dw_readl(struct dw_i2c_dev *dev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81869145)
Location: drivers/i2c/busses/i2c-designware-common.c:56
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81869270-ffffffff818692bc: dw_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u32 dw_readl(struct dw_i2c_dev *dev, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818830d5)
Location: drivers/i2c/busses/i2c-designware-common.c:56
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81883200-ffffffff8188324c: dw_readl (STB_GLOBAL)
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
