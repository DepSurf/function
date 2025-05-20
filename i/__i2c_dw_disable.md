# Function: <code>__i2c_dw_disable</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817d9fb0)
Location: drivers/i2c/busses/i2c-designware-common.c:152
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff817d9fb0-ffffffff817da054: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818011c0)
Location: drivers/i2c/busses/i2c-designware-common.c:217
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff818011c0-ffffffff81801264: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81842a69)
Location: drivers/i2c/busses/i2c-designware-common.c:217
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81842a69-ffffffff81842a7e: __i2c_dw_disable.cold (STB_LOCAL)
ffffffff81842550-ffffffff818425e1: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818743e9)
Location: drivers/i2c/busses/i2c-designware-common.c:217
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff818743e9-ffffffff818743fe: __i2c_dw_disable.cold (STB_LOCAL)
ffffffff81873ed0-ffffffff81873f61: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81948b56)
Location: drivers/i2c/busses/i2c-designware-common.c:436
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81948b56-ffffffff81948b6b: __i2c_dw_disable.cold (STB_LOCAL)
ffffffff81948660-ffffffff819486e8: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81c24f79)
Location: drivers/i2c/busses/i2c-designware-common.c:436
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81c24f79-ffffffff81c24f8e: __i2c_dw_disable.cold (STB_LOCAL)
ffffffff8194e460-ffffffff8194e4e8: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81c16fda)
Location: drivers/i2c/busses/i2c-designware-common.c:439
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81c16fda-ffffffff81c16fef: __i2c_dw_disable.cold (STB_LOCAL)
ffffffff81931fd0-ffffffff81932058: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:439
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81d25cd4-ffffffff81d25ce9: __i2c_dw_disable.cold (STB_LOCAL)
ffffffff819d52f0-ffffffff819d537d: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:439
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81ef1a2c-ffffffff81ef1a41: __i2c_dw_disable.cold (STB_LOCAL)
ffffffff81b37cd0-ffffffff81b37d70: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccd2a0)
Location: drivers/i2c/busses/i2c-designware-common.c:442
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81ccd2a0-ffffffff81ccd354: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d35000)
Location: drivers/i2c/busses/i2c-designware-common.c:442
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81d35000-ffffffff81d350b4: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb0b0)
Location: drivers/i2c/busses/i2c-designware-common.c:442
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81deb0b0-ffffffff81deb244: __i2c_dw_disable (STB_GLOBAL)
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
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab8cf8)
Location: drivers/i2c/busses/i2c-designware-common.c:217
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffff800010ab8cf8-ffff800010ab8d9c: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c0b982e0)
Location: drivers/i2c/busses/i2c-designware-common.c:217
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c0b982e0-c0b98380: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9bc50)
Location: drivers/i2c/busses/i2c-designware-common.c:217
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c000000000b9bc50-c000000000b9bcf4: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bdbf8)
Location: drivers/i2c/busses/i2c-designware-common.c:217
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffe0006bdbf8-ffffffe0006bdc88: __i2c_dw_disable (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81869899)
Location: drivers/i2c/busses/i2c-designware-common.c:217
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81869899-ffffffff818698ae: __i2c_dw_disable.cold (STB_LOCAL)
ffffffff81869380-ffffffff81869411: __i2c_dw_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __i2c_dw_disable(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81883829)
Location: drivers/i2c/busses/i2c-designware-common.c:217
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81883829-ffffffff8188383e: __i2c_dw_disable.cold (STB_LOCAL)
ffffffff81883310-ffffffff818833a1: __i2c_dw_disable (STB_GLOBAL)
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
