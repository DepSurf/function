# Function: <code>tps65217_set_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tps65217_set_bits(struct tps65217 *tps, unsigned int reg, unsigned int mask, unsigned int val, unsigned int level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/tps65217.c (ffffffff815858f0)
Location: drivers/mfd/tps65217.c:138
Inline: True
Direct callers:
  - drivers/regulator/tps65217-regulator.c:tps65217_pmic_enable
  - drivers/regulator/tps65217-regulator.c:tps65217_pmic_set_voltage_sel
  - drivers/regulator/tps65217-regulator.c:tps65217_pmic_set_voltage_sel
```
**Symbols:**

```
ffffffff815858f0-ffffffff81585900: tps65217_set_bits (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tps65217_set_bits(struct tps65217 *tps, unsigned int reg, unsigned int mask, unsigned int val, unsigned int level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/tps65217.c (c0a23334)
Location: drivers/mfd/tps65217.c:281
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_probe
  - drivers/mfd/tps65217.c:tps65217_probe
  - drivers/mfd/tps65217.c:tps65217_irq_sync_unlock
Direct callers:
  - drivers/regulator/tps65217-regulator.c:tps65217_pmic_set_suspend_disable
  - drivers/regulator/tps65217-regulator.c:tps65217_pmic_set_voltage_sel
  - drivers/regulator/tps65217-regulator.c:tps65217_pmic_set_voltage_sel
  - drivers/regulator/tps65217-regulator.c:tps65217_pmic_enable
```
**Symbols:**

```
c0a23168-c0a23194: tps65217_set_bits (STB_GLOBAL)
```
</details>
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
</ul>
<b>Arch</b>
<ul>
</ul>
