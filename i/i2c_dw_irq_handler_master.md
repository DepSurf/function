# Function: <code>i2c_dw_irq_handler_master</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817261cd)
Location: drivers/i2c/busses/i2c-designware-master.c:558
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8179781d)
Location: drivers/i2c/busses/i2c-designware-master.c:558
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817da41c)
Location: drivers/i2c/busses/i2c-designware-master.c:564
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8180183b)
Location: drivers/i2c/busses/i2c-designware-master.c:572
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:577
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
**Symbols:**

```
ffffffff81842b80-ffffffff81843209: i2c_dw_irq_handler_master (STB_LOCAL)
ffffffff81843b61-ffffffff81843b8c: i2c_dw_irq_handler_master.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:577
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
**Symbols:**

```
ffffffff81874500-ffffffff81874b89: i2c_dw_irq_handler_master (STB_LOCAL)
ffffffff818754cd-ffffffff818754f8: i2c_dw_irq_handler_master.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81949d50)
Location: drivers/i2c/busses/i2c-designware-master.c:613
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
**Symbols:**

```
ffffffff81949d50-ffffffff81949e35: i2c_dw_irq_handler_master.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194fa10)
Location: drivers/i2c/busses/i2c-designware-master.c:613
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
**Symbols:**

```
ffffffff8194fa10-ffffffff8194faf5: i2c_dw_irq_handler_master.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81933735)
Location: drivers/i2c/busses/i2c-designware-master.c:718
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6b02)
Location: drivers/i2c/busses/i2c-designware-master.c:718
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b3961f)
Location: drivers/i2c/busses/i2c-designware-master.c:714
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
</details>
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
int i2c_dw_irq_handler_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010ab9388)
Location: drivers/i2c/busses/i2c-designware-master.c:577
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
**Symbols:**

```
ffff800010ab9388-ffff800010ab9910: i2c_dw_irq_handler_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (c0b989b4)
Location: drivers/i2c/busses/i2c-designware-master.c:577
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
**Symbols:**

```
c0b989b4-c0b98fbc: i2c_dw_irq_handler_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9c470)
Location: drivers/i2c/busses/i2c-designware-master.c:577
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
**Symbols:**

```
c000000000b9c470-c000000000b9cc7c: i2c_dw_irq_handler_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006be19a)
Location: drivers/i2c/busses/i2c-designware-master.c:577
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
**Symbols:**

```
ffffffe0006be19a-ffffffe0006be686: i2c_dw_irq_handler_master (STB_LOCAL)
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
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:577
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
**Symbols:**

```
ffffffff818699b0-ffffffff8186a039: i2c_dw_irq_handler_master (STB_LOCAL)
ffffffff8186a97d-ffffffff8186a9a8: i2c_dw_irq_handler_master.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:577
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
```
**Symbols:**

```
ffffffff81883940-ffffffff81883fc9: i2c_dw_irq_handler_master (STB_LOCAL)
ffffffff8188490d-ffffffff81884938: i2c_dw_irq_handler_master.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
