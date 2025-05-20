# Function: <code>i2c_dw_probe_master</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i2c_dw_probe_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:741
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81949f8d-ffffffff8194a01f: i2c_dw_probe_master.cold (STB_LOCAL)
ffffffff819497c0-ffffffff819499ce: i2c_dw_probe_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i2c_dw_probe_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:741
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81c25046-ffffffff81c250d8: i2c_dw_probe_master.cold (STB_LOCAL)
ffffffff8194f380-ffffffff8194f58e: i2c_dw_probe_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i2c_dw_probe_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:860
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81c1711a-ffffffff81c171c2: i2c_dw_probe_master.cold (STB_LOCAL)
ffffffff819337f0-ffffffff81933a67: i2c_dw_probe_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i2c_dw_probe_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:860
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81d25dd9-ffffffff81d25e81: i2c_dw_probe_master.cold (STB_LOCAL)
ffffffff819d6bc0-ffffffff819d6e37: i2c_dw_probe_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i2c_dw_probe_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:858
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81ef1b32-ffffffff81ef1bda: i2c_dw_probe_master.cold (STB_LOCAL)
ffffffff81b39700-ffffffff81b3999f: i2c_dw_probe_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_dw_probe_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81cced90)
Location: drivers/i2c/busses/i2c-designware-master.c:864
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81cced90-ffffffff81ccf0c3: i2c_dw_probe_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_dw_probe_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d36e30)
Location: drivers/i2c/busses/i2c-designware-master.c:956
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81d36e30-ffffffff81d371d4: i2c_dw_probe_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_dw_probe_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded040)
Location: drivers/i2c/busses/i2c-designware-master.c:981
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81ded040-ffffffff81ded45d: i2c_dw_probe_master (STB_GLOBAL)
```
</details>
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
