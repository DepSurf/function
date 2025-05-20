# Function: <code>i2c_dw_acquire_lock</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81725e60)
Location: drivers/i2c/busses/i2c-designware-common.c:188
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81725e60-ffffffff81725ea2: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817974b0)
Location: drivers/i2c/busses/i2c-designware-common.c:188
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff817974b0-ffffffff817974f5: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817da080)
Location: drivers/i2c/busses/i2c-designware-common.c:200
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff817da080-ffffffff817da0cc: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81801290)
Location: drivers/i2c/busses/i2c-designware-common.c:265
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81801290-ffffffff818012dc: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:279
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81842a7e-ffffffff81842a98: i2c_dw_acquire_lock.cold (STB_LOCAL)
ffffffff81842610-ffffffff81842644: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:279
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff818743fe-ffffffff81874418: i2c_dw_acquire_lock.cold (STB_LOCAL)
ffffffff81873f90-ffffffff81873fc4: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819483e5)
Location: drivers/i2c/busses/i2c-designware-common.c:500
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81948b6b-ffffffff81948b85: i2c_dw_acquire_lock.cold (STB_LOCAL)
ffffffff81948710-ffffffff81948743: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194e1e5)
Location: drivers/i2c/busses/i2c-designware-common.c:500
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81c24f8e-ffffffff81c24fa8: i2c_dw_acquire_lock.cold (STB_LOCAL)
ffffffff8194e510-ffffffff8194e543: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81931d35)
Location: drivers/i2c/busses/i2c-designware-common.c:503
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81c16fef-ffffffff81c17009: i2c_dw_acquire_lock.cold (STB_LOCAL)
ffffffff81932080-ffffffff819320b3: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d5045)
Location: drivers/i2c/busses/i2c-designware-common.c:503
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81d25ce9-ffffffff81d25d03: i2c_dw_acquire_lock.cold (STB_LOCAL)
ffffffff819d53a0-ffffffff819d53d3: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b3820e)
Location: drivers/i2c/busses/i2c-designware-common.c:500
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81ef1a41-ffffffff81ef1a5b: i2c_dw_acquire_lock.cold (STB_LOCAL)
ffffffff81b37da0-ffffffff81b37de5: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccd8ae)
Location: drivers/i2c/busses/i2c-designware-common.c:503
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81ccd3b0-ffffffff81ccd406: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d3565e)
Location: drivers/i2c/busses/i2c-designware-common.c:503
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81d35110-ffffffff81d35175: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb7ee)
Location: drivers/i2c/busses/i2c-designware-common.c:520
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81deb2a0-ffffffff81deb305: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab8df0)
Location: drivers/i2c/busses/i2c-designware-common.c:279
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffff800010ab8df0-ffff800010ab8e44: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c0b983ec)
Location: drivers/i2c/busses/i2c-designware-common.c:279
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c0b983ec-c0b98448: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9bd60)
Location: drivers/i2c/busses/i2c-designware-common.c:279
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c000000000b9bd60-c000000000b9bdf0: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bdcc2)
Location: drivers/i2c/busses/i2c-designware-common.c:279
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffe0006bdcc2-ffffffe0006bdd0c: i2c_dw_acquire_lock (STB_GLOBAL)
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
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:279
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff818698ae-ffffffff818698c8: i2c_dw_acquire_lock.cold (STB_LOCAL)
ffffffff81869440-ffffffff81869474: i2c_dw_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:279
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff8188383e-ffffffff81883858: i2c_dw_acquire_lock.cold (STB_LOCAL)
ffffffff818833d0-ffffffff81883404: i2c_dw_acquire_lock (STB_GLOBAL)
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
