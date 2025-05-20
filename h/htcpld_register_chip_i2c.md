# Function: <code>htcpld_register_chip_i2c</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff8157badc)
Location: drivers/mfd/htc-i2cpld.c:338
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff815d0a02)
Location: drivers/mfd/htc-i2cpld.c:333
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff815fd756)
Location: drivers/mfd/htc-i2cpld.c:333
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff81611512)
Location: drivers/mfd/htc-i2cpld.c:333
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff81679da4)
Location: drivers/mfd/htc-i2cpld.c:333
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
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
In drivers/mfd/htc-i2cpld.c (ffffffff816b5866)
Location: drivers/mfd/htc-i2cpld.c:333
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
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
In drivers/mfd/htc-i2cpld.c (ffffffff816d6ac6)
Location: drivers/mfd/htc-i2cpld.c:333
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
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
In drivers/mfd/htc-i2cpld.c (ffffffff81712202)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
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
In drivers/mfd/htc-i2cpld.c (ffffffff81736502)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int htcpld_register_chip_i2c(struct platform_device *pdev, int chip_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (0)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff817f37c0-ffffffff817f390e: htcpld_register_chip_i2c (STB_LOCAL)
ffffffff817f4149-ffffffff817f41a0: htcpld_register_chip_i2c.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int htcpld_register_chip_i2c(struct platform_device *pdev, int chip_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (0)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff81807420-ffffffff81807570: htcpld_register_chip_i2c (STB_LOCAL)
ffffffff81c107e2-ffffffff81c1084b: htcpld_register_chip_i2c.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int htcpld_register_chip_i2c(struct platform_device *pdev, int chip_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (0)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff817ec040-ffffffff817ec190: htcpld_register_chip_i2c (STB_LOCAL)
ffffffff81c02990-ffffffff81c029f9: htcpld_register_chip_i2c.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int htcpld_register_chip_i2c(struct platform_device *pdev, int chip_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (0)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff81878c10-ffffffff81878d60: htcpld_register_chip_i2c (STB_LOCAL)
ffffffff81d067ca-ffffffff81d06833: htcpld_register_chip_i2c.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int htcpld_register_chip_i2c(struct platform_device *pdev, int chip_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (0)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff819c1100-ffffffff819c1273: htcpld_register_chip_i2c (STB_LOCAL)
ffffffff81ecf0bf-ffffffff81ecf133: htcpld_register_chip_i2c.cold (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffff80001092dea0)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
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
In drivers/mfd/htc-i2cpld.c (c0a0f8ec)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
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
In drivers/mfd/htc-i2cpld.c (c0000000009cd798)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
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
In drivers/mfd/htc-i2cpld.c (ffffffe0005a4cb0)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
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
In drivers/mfd/htc-i2cpld.c (ffffffff817299c2)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
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
In drivers/mfd/htc-i2cpld.c (ffffffff81744e02)
Location: drivers/mfd/htc-i2cpld.c:319
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
</details>
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
</ul>
