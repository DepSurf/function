# Function: <code>dw_i2c_plat_runtime_suspend</code>

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
int dw_i2c_plat_runtime_suspend(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8172714b)
Location: drivers/i2c/busses/i2c-designware-platdrv.c:440
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
```
**Symbols:**

```
ffffffff817270d0-ffffffff817270f9: dw_i2c_plat_runtime_suspend (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_i2c_plat_runtime_suspend(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b3a183)
Location: drivers/i2c/busses/i2c-designware-platdrv.c:440
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
```
**Symbols:**

```
ffffffff81b39b30-ffffffff81b39b80: dw_i2c_plat_runtime_suspend (STB_LOCAL)
ffffffff81ef1bef-ffffffff81ef1c04: dw_i2c_plat_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_i2c_plat_runtime_suspend(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccfb23)
Location: drivers/i2c/busses/i2c-designware-platdrv.c:425
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
```
**Symbols:**

```
ffffffff81ccf4d0-ffffffff81ccf520: dw_i2c_plat_runtime_suspend (STB_LOCAL)
ffffffff820a76e0-ffffffff820a76f5: dw_i2c_plat_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_i2c_plat_runtime_suspend(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37c33)
Location: drivers/i2c/busses/i2c-designware-platdrv.c:437
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
```
**Symbols:**

```
ffffffff81d375a0-ffffffff81d375f0: dw_i2c_plat_runtime_suspend (STB_LOCAL)
ffffffff82128b03-ffffffff82128b18: dw_i2c_plat_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_i2c_plat_runtime_suspend(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedeb3)
Location: drivers/i2c/busses/i2c-designware-platdrv.c:432
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
```
**Symbols:**

```
ffffffff81ded820-ffffffff81ded870: dw_i2c_plat_runtime_suspend (STB_LOCAL)
ffffffff8220a495-ffffffff8220a4aa: dw_i2c_plat_runtime_suspend.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
