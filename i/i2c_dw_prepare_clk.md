# Function: <code>i2c_dw_prepare_clk</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817d9e40)
Location: drivers/i2c/busses/i2c-designware-common.c:187
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817d9e40-ffffffff817d9ea0: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81801050)
Location: drivers/i2c/busses/i2c-designware-common.c:252
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81801050-ffffffff818010b0: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81842360)
Location: drivers/i2c/busses/i2c-designware-common.c:252
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81842360-ffffffff81842432: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81873ce0)
Location: drivers/i2c/busses/i2c-designware-common.c:252
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81873ce0-ffffffff81873db2: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81948260)
Location: drivers/i2c/busses/i2c-designware-common.c:473
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81948260-ffffffff81948332: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194e060)
Location: drivers/i2c/busses/i2c-designware-common.c:473
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8194e060-ffffffff8194e132: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81931bb0)
Location: drivers/i2c/busses/i2c-designware-common.c:476
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81931bb0-ffffffff81931c82: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d4ec0)
Location: drivers/i2c/busses/i2c-designware-common.c:476
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff819d4ec0-ffffffff819d4f92: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b37840)
Location: drivers/i2c/busses/i2c-designware-common.c:476
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_runtime_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81b37840-ffffffff81b3791e: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81cccd40)
Location: drivers/i2c/busses/i2c-designware-common.c:479
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_runtime_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81cccd40-ffffffff81ccce1e: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d34aa0)
Location: drivers/i2c/busses/i2c-designware-common.c:479
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_runtime_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81d34aa0-ffffffff81d34b7e: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deab50)
Location: drivers/i2c/busses/i2c-designware-common.c:496
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_runtime_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81deab50-ffffffff81deac2e: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab89c8)
Location: drivers/i2c/busses/i2c-designware-common.c:252
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffff800010ab89c8-ffff800010ab8abc: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c0b980f0)
Location: drivers/i2c/busses/i2c-designware-common.c:252
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
c0b980f0-c0b981a8: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9b8e0)
Location: drivers/i2c/busses/i2c-designware-common.c:252
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
c000000000b9b8e0-c000000000b9b938: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bd8fc)
Location: drivers/i2c/busses/i2c-designware-common.c:252
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffe0006bd8fc-ffffffe0006bd9e8: i2c_dw_prepare_clk (STB_GLOBAL)
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
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81869190)
Location: drivers/i2c/busses/i2c-designware-common.c:252
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81869190-ffffffff81869262: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev *dev, bool prepare);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81883120)
Location: drivers/i2c/busses/i2c-designware-common.c:252
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81883120-ffffffff818831f2: i2c_dw_prepare_clk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
