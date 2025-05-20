# Function: <code>__i2c_transfer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816798d0)
Location: drivers/i2c/i2c-core.c:2170
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_transfer
```
**Symbols:**

```
ffffffff816798d0-ffffffff81679cf0: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816db090)
Location: drivers/i2c/i2c-core.c:2375
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_transfer
```
**Symbols:**

```
ffffffff816db090-ffffffff816db477: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170b3d0)
Location: drivers/i2c/i2c-core.c:2661
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_transfer
```
**Symbols:**

```
ffffffff8170b3d0-ffffffff8170b7b7: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81720420)
Location: drivers/i2c/i2c-core-base.c:1847
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
**Symbols:**

```
ffffffff81720420-ffffffff81720812: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81791750)
Location: drivers/i2c/i2c-core-base.c:1871
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
**Symbols:**

```
ffffffff81791750-ffffffff81791b50: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d4160)
Location: drivers/i2c/i2c-core-base.c:1850
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
```
**Symbols:**

```
ffffffff817d4160-ffffffff817d4561: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fb2a0)
Location: drivers/i2c/i2c-core-base.c:1861
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff817fb2a0-ffffffff817fb6e6: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183bfc0)
Location: drivers/i2c/i2c-core-base.c:1951
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff8183bfc0-ffffffff8183c42f: __i2c_transfer.part.0 (STB_LOCAL)
ffffffff8183da41-ffffffff8183da59: __i2c_transfer.cold (STB_LOCAL)
ffffffff8183c430-ffffffff8183c4a5: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186d960)
Location: drivers/i2c/i2c-core-base.c:1956
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff8186d960-ffffffff8186dbec: __i2c_transfer.part.0 (STB_LOCAL)
ffffffff8186dbf0-ffffffff8186dea5: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81941c30)
Location: drivers/i2c/i2c-core-base.c:1886
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff81941c30-ffffffff81941eda: __i2c_transfer.part.0 (STB_LOCAL)
ffffffff81941ee0-ffffffff81941f57: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81947fe0)
Location: drivers/i2c/i2c-core-base.c:2016
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff81947fe0-ffffffff81948226: __i2c_transfer.part.0 (STB_LOCAL)
ffffffff81948230-ffffffff819482a7: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192b940)
Location: drivers/i2c/i2c-core-base.c:2076
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff8192b940-ffffffff8192bb86: __i2c_transfer.part.0 (STB_LOCAL)
ffffffff8192bb90-ffffffff8192bc07: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819ceb20)
Location: drivers/i2c/i2c-core-base.c:2077
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff819ceb20-ffffffff819ced45: __i2c_transfer.part.0 (STB_LOCAL)
ffffffff819ced50-ffffffff819cedc7: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b30810)
Location: drivers/i2c/i2c-core-base.c:2080
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff81b30810-ffffffff81b30ab6: __i2c_transfer.part.0 (STB_LOCAL)
ffffffff81b30ac0-ffffffff81b30b45: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc5140)
Location: drivers/i2c/i2c-core-base.c:2074
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff81cc5140-ffffffff81cc53d0: __i2c_transfer.part.0 (STB_LOCAL)
ffffffff81cc53e0-ffffffff81cc5465: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2cde0)
Location: drivers/i2c/i2c-core-base.c:2187
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff81d2cde0-ffffffff81d2d05f: __i2c_transfer.part.0 (STB_LOCAL)
ffffffff81d2d070-ffffffff81d2d0f5: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de2cb0)
Location: drivers/i2c/i2c-core-base.c:2205
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff81de2cb0-ffffffff81de2f40: __i2c_transfer.part.0 (STB_LOCAL)
ffffffff81de2f50-ffffffff81de2fd5: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab11a0)
Location: drivers/i2c/i2c-core-base.c:1956
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffff800010ab11a0-ffff800010ab14d4: __i2c_transfer.part.0 (STB_LOCAL)
ffff800010ab14d8-ffff800010ab17ac: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b921a0)
Location: drivers/i2c/i2c-core-base.c:1956
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
c0b921a0-c0b92548: __i2c_transfer.part.0 (STB_LOCAL)
c0b92548-c0b92824: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b93f80)
Location: drivers/i2c/i2c-core-base.c:1956
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_write_generic
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
c000000000b93f80-c000000000b94598: __i2c_transfer.part.0 (STB_LOCAL)
c000000000b945a0-c000000000b94680: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b8d9c)
Location: drivers/i2c/i2c-core-base.c:1956
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffe0006b8d9c-ffffffe0006b9016: __i2c_transfer.part.0 (STB_LOCAL)
ffffffe0006b9016-ffffffe0006b9246: __i2c_transfer (STB_GLOBAL)
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
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81861af0)
Location: drivers/i2c/i2c-core-base.c:1956
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff81861af0-ffffffff81861d7c: __i2c_transfer.part.0 (STB_LOCAL)
ffffffff81861d80-ffffffff81862035: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187cd00)
Location: drivers/i2c/i2c-core-base.c:1956
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
```
**Symbols:**

```
ffffffff8187cd00-ffffffff8187cfdb: __i2c_transfer.part.0 (STB_LOCAL)
ffffffff8187cfe0-ffffffff8187d295: __i2c_transfer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
