# Function: <code>__i2c_dw_enable</code>

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
void __i2c_dw_enable(struct dw_i2c_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81725da1)
Location: drivers/i2c/busses/i2c-designware-common.c:151
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81725d40-ffffffff81725d76: __i2c_dw_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __i2c_dw_enable(struct dw_i2c_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817973f1)
Location: drivers/i2c/busses/i2c-designware-common.c:151
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81797390-ffffffff817973c6: __i2c_dw_enable (STB_GLOBAL)
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
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817db06e)
Location: drivers/i2c/busses/i2c-designware-core.h:310
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
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
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818026ac)
Location: drivers/i2c/busses/i2c-designware-core.h:300
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81843569)
Location: drivers/i2c/busses/i2c-designware-core.h:304
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81874ee9)
Location: drivers/i2c/busses/i2c-designware-core.h:304
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819493ef)
Location: drivers/i2c/busses/i2c-designware-core.h:313
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f7cf)
Location: drivers/i2c/busses/i2c-designware-core.h:313
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
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
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819331a9)
Location: drivers/i2c/busses/i2c-designware-core.h:323
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
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
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6559)
Location: drivers/i2c/busses/i2c-designware-core.h:323
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
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
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39090)
Location: drivers/i2c/busses/i2c-designware-core.h:335
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccea28)
Location: drivers/i2c/busses/i2c-designware-core.h:333
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d367f8)
Location: drivers/i2c/busses/i2c-designware-core.h:339
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81dec5b8)
Location: drivers/i2c/busses/i2c-designware-core.h:342
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010ab9cbc)
Location: drivers/i2c/busses/i2c-designware-core.h:304
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (c0b992f4)
Location: drivers/i2c/busses/i2c-designware-core.h:304
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d7fc)
Location: drivers/i2c/busses/i2c-designware-core.h:304
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006bee30)
Location: drivers/i2c/busses/i2c-designware-core.h:304
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a399)
Location: drivers/i2c/busses/i2c-designware-core.h:304
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81884329)
Location: drivers/i2c/busses/i2c-designware-core.h:304
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
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
</ul>
