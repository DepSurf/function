# Function: <code>device_regulator_init</code>

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
In drivers/mfd/88pm860x-core.c (ffffffff8157a82b)
Location: drivers/mfd/88pm860x-core.c:792
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (ffffffff815cf890)
Location: drivers/mfd/88pm860x-core.c:794
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (ffffffff815fc4c1)
Location: drivers/mfd/88pm860x-core.c:794
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (ffffffff816102b5)
Location: drivers/mfd/88pm860x-core.c:794
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (ffffffff81678b35)
Location: drivers/mfd/88pm860x-core.c:794
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (ffffffff816b459a)
Location: drivers/mfd/88pm860x-core.c:794
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (ffffffff816d581a)
Location: drivers/mfd/88pm860x-core.c:794
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (ffffffff81711326)
Location: drivers/mfd/88pm860x-core.c:791
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (ffffffff81735626)
Location: drivers/mfd/88pm860x-core.c:791
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_regulator_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff817f2911)
Location: drivers/mfd/88pm860x-core.c:791
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff817f2911-ffffffff817f2b1f: device_regulator_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_regulator_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81c0fea9)
Location: drivers/mfd/88pm860x-core.c:791
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81c0fea9-ffffffff81c100b7: device_regulator_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_regulator_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81c0204d)
Location: drivers/mfd/88pm860x-core.c:791
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81c0204d-ffffffff81c0225e: device_regulator_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_regulator_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81d05e57)
Location: drivers/mfd/88pm860x-core.c:791
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81d05e57-ffffffff81d06068: device_regulator_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_regulator_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81ece768)
Location: drivers/mfd/88pm860x-core.c:791
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81ece768-ffffffff81ece983: device_regulator_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_regulator_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81b35dd0)
Location: drivers/mfd/88pm860x-core.c:791
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81b35dd0-ffffffff81b36005: device_regulator_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_regulator_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81b892c0)
Location: drivers/mfd/88pm860x-core.c:791
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81b892c0-ffffffff81b894f5: device_regulator_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_regulator_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81bdd1c0)
Location: drivers/mfd/88pm860x-core.c:791
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81bdd1c0-ffffffff81bdd3f5: device_regulator_init (STB_LOCAL)
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
In drivers/mfd/88pm860x-core.c (ffff80001092cc84)
Location: drivers/mfd/88pm860x-core.c:791
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (c0a0b670)
Location: drivers/mfd/88pm860x-core.c:791
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (c0000000009cbfdc)
Location: drivers/mfd/88pm860x-core.c:791
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (ffffffe0005a3cfe)
Location: drivers/mfd/88pm860x-core.c:791
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (ffffffff81728ae6)
Location: drivers/mfd/88pm860x-core.c:791
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
In drivers/mfd/88pm860x-core.c (ffffffff81743f26)
Location: drivers/mfd/88pm860x-core.c:791
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
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
