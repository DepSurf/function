# Function: <code>i2c_dw_plat_prepare_clk</code>

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
int i2c_dw_plat_prepare_clk(struct dw_i2c_dev *i_dev, bool prepare);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81727070)
Location: drivers/i2c/busses/i2c-designware-platdrv.c:217
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81727070-ffffffff817270d0: i2c_dw_plat_prepare_clk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_dw_plat_prepare_clk(struct dw_i2c_dev *i_dev, bool prepare);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817986c0)
Location: drivers/i2c/busses/i2c-designware-platdrv.c:217
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817986c0-ffffffff81798720: i2c_dw_plat_prepare_clk (STB_LOCAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
