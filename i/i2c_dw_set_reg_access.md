# Function: <code>i2c_dw_set_reg_access</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int i2c_dw_set_reg_access(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818012e0)
Location: drivers/i2c/busses/i2c-designware-common.c:92
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
**Symbols:**

```
ffffffff818012e0-ffffffff818013ac: i2c_dw_set_reg_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i2c_dw_set_reg_access(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:92
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
**Symbols:**

```
ffffffff81842a98-ffffffff81842ab5: i2c_dw_set_reg_access.cold (STB_LOCAL)
ffffffff81842650-ffffffff81842704: i2c_dw_set_reg_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i2c_dw_set_reg_access(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:92
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
**Symbols:**

```
ffffffff81874418-ffffffff81874435: i2c_dw_set_reg_access.cold (STB_LOCAL)
ffffffff81873fd0-ffffffff81874084: i2c_dw_set_reg_access (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int i2c_dw_set_reg_access(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab8e48)
Location: drivers/i2c/busses/i2c-designware-common.c:92
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
**Symbols:**

```
ffff800010ab8e48-ffff800010ab8f3c: i2c_dw_set_reg_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int i2c_dw_set_reg_access(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c0b98448)
Location: drivers/i2c/busses/i2c-designware-common.c:92
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
**Symbols:**

```
c0b98448-c0b98528: i2c_dw_set_reg_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2c_dw_set_reg_access(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9bdf0)
Location: drivers/i2c/busses/i2c-designware-common.c:92
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
**Symbols:**

```
c000000000b9bdf0-c000000000b9bf30: i2c_dw_set_reg_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int i2c_dw_set_reg_access(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bdd0c)
Location: drivers/i2c/busses/i2c-designware-common.c:92
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
**Symbols:**

```
ffffffe0006bdd0c-ffffffe0006bddce: i2c_dw_set_reg_access (STB_GLOBAL)
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
int i2c_dw_set_reg_access(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:92
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
**Symbols:**

```
ffffffff818698c8-ffffffff818698e5: i2c_dw_set_reg_access.cold (STB_LOCAL)
ffffffff81869480-ffffffff81869534: i2c_dw_set_reg_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i2c_dw_set_reg_access(struct dw_i2c_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: drivers/i2c/busses/i2c-designware-common.c:92
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
**Symbols:**

```
ffffffff81883858-ffffffff81883875: i2c_dw_set_reg_access.cold (STB_LOCAL)
ffffffff81883410-ffffffff818834c4: i2c_dw_set_reg_access (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
