# Function: <code>i2c_dw_release_lock</code>

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
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81725eb0)
Location: drivers/i2c/busses/i2c-designware-common.c:204
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81725eb0-ffffffff81725ecb: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81797500)
Location: drivers/i2c/busses/i2c-designware-common.c:204
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81797500-ffffffff8179751e: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817da0d0)
Location: drivers/i2c/busses/i2c-designware-common.c:216
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff817da0d0-ffffffff817da0ed: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8180143b)
Location: drivers/i2c/busses/i2c-designware-common.c:281
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff818014f0-ffffffff8180150d: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8184279b)
Location: drivers/i2c/busses/i2c-designware-common.c:295
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81842840-ffffffff8184285d: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8187411b)
Location: drivers/i2c/busses/i2c-designware-common.c:295
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff818741c0-ffffffff818741dd: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819485a3)
Location: drivers/i2c/busses/i2c-designware-common.c:516
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81948750-ffffffff8194876d: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194e3a3)
Location: drivers/i2c/busses/i2c-designware-common.c:516
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff8194e550-ffffffff8194e56d: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81931f13)
Location: drivers/i2c/busses/i2c-designware-common.c:519
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff819320c0-ffffffff819320dd: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d5230)
Location: drivers/i2c/busses/i2c-designware-common.c:519
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff819d53e0-ffffffff819d53fd: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b3824a)
Location: drivers/i2c/busses/i2c-designware-common.c:516
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81b37df0-ffffffff81b37e1d: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccd8e6)
Location: drivers/i2c/busses/i2c-designware-common.c:519
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81ccd420-ffffffff81ccd44d: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d35696)
Location: drivers/i2c/busses/i2c-designware-common.c:519
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81d35190-ffffffff81d351bd: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb826)
Location: drivers/i2c/busses/i2c-designware-common.c:536
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
```
**Symbols:**

```
ffffffff81deb320-ffffffff81deb34d: i2c_dw_release_lock (STB_GLOBAL)
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
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab8fc4)
Location: drivers/i2c/busses/i2c-designware-common.c:295
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffff800010ab9040-ffff800010ab9070: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c0b985d4)
Location: drivers/i2c/busses/i2c-designware-common.c:295
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c0b98674-c0b9869c: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9bfec)
Location: drivers/i2c/busses/i2c-designware-common.c:295
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c000000000b9c0a0-c000000000b9c0e8: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bde3e)
Location: drivers/i2c/busses/i2c-designware-common.c:295
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffe0006bdec2-ffffffe0006bdeea: i2c_dw_release_lock (STB_GLOBAL)
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
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818695cb)
Location: drivers/i2c/busses/i2c-designware-common.c:295
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81869670-ffffffff8186968d: i2c_dw_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8188355b)
Location: drivers/i2c/busses/i2c-designware-common.c:295
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81883600-ffffffff8188361d: i2c_dw_release_lock (STB_GLOBAL)
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
