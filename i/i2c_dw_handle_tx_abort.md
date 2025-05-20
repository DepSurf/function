# Function: <code>i2c_dw_handle_tx_abort</code>

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
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81725f60)
Location: drivers/i2c/busses/i2c-designware-common.c:229
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81725f60-ffffffff817260a2: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817975b0)
Location: drivers/i2c/busses/i2c-designware-common.c:229
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff817975b0-ffffffff817976f2: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817da1c0)
Location: drivers/i2c/busses/i2c-designware-common.c:245
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff817da1c0-ffffffff817da2f7: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818015e0)
Location: drivers/i2c/busses/i2c-designware-common.c:310
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff818015e0-ffffffff81801717: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:324
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81842b30-ffffffff81842b74: i2c_dw_handle_tx_abort.cold (STB_LOCAL)
ffffffff818428e0-ffffffff818429c8: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:324
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff818744b0-ffffffff818744f4: i2c_dw_handle_tx_abort.cold (STB_LOCAL)
ffffffff81874260-ffffffff81874348: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:546
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81948b85-ffffffff81948bc9: i2c_dw_handle_tx_abort.cold (STB_LOCAL)
ffffffff81948870-ffffffff81948958: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:546
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81c24fa8-ffffffff81c24fec: i2c_dw_handle_tx_abort.cold (STB_LOCAL)
ffffffff8194e670-ffffffff8194e758: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:549
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81c17009-ffffffff81c1706e: i2c_dw_handle_tx_abort.cold (STB_LOCAL)
ffffffff819321e0-ffffffff819322c2: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d5500)
Location: drivers/i2c/busses/i2c-designware-common.c:549
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff819d5500-ffffffff819d5677: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b37f30)
Location: drivers/i2c/busses/i2c-designware-common.c:546
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81b37f30-ffffffff81b380bb: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccd580)
Location: drivers/i2c/busses/i2c-designware-common.c:549
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81ccd580-ffffffff81ccd71b: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d352f0)
Location: drivers/i2c/busses/i2c-designware-common.c:549
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81d352f0-ffffffff81d354b1: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb480)
Location: drivers/i2c/busses/i2c-designware-common.c:566
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81deb480-ffffffff81deb641: i2c_dw_handle_tx_abort (STB_GLOBAL)
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
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab90f8)
Location: drivers/i2c/busses/i2c-designware-common.c:324
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffff800010ab90f8-ffff800010ab928c: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c0b98780)
Location: drivers/i2c/busses/i2c-designware-common.c:324
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c0b98780-c0b988ec: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9c1b0)
Location: drivers/i2c/busses/i2c-designware-common.c:324
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c000000000b9c1b0-c000000000b9c3d0: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bdf76)
Location: drivers/i2c/busses/i2c-designware-common.c:324
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffe0006bdf76-ffffffe0006be0ca: i2c_dw_handle_tx_abort (STB_GLOBAL)
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
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:324
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81869960-ffffffff818699a4: i2c_dw_handle_tx_abort.cold (STB_LOCAL)
ffffffff81869710-ffffffff818697f8: i2c_dw_handle_tx_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i2c_dw_handle_tx_abort(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:324
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff818838f0-ffffffff81883934: i2c_dw_handle_tx_abort.cold (STB_LOCAL)
ffffffff818836a0-ffffffff81883788: i2c_dw_handle_tx_abort (STB_GLOBAL)
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
