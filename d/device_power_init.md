# Function: <code>device_power_init</code>

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
In drivers/mfd/88pm860x-core.c (ffffffff8157ab38)
Location: drivers/mfd/88pm860x-core.c:909
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
In drivers/mfd/88pm860x-core.c (ffffffff815cfb91)
Location: drivers/mfd/88pm860x-core.c:911
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
In drivers/mfd/88pm860x-core.c (ffffffff815fc7b9)
Location: drivers/mfd/88pm860x-core.c:911
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
In drivers/mfd/88pm860x-core.c (ffffffff8161059c)
Location: drivers/mfd/88pm860x-core.c:911
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
In drivers/mfd/88pm860x-core.c (ffffffff81678e1c)
Location: drivers/mfd/88pm860x-core.c:911
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
In drivers/mfd/88pm860x-core.c (ffffffff816b4880)
Location: drivers/mfd/88pm860x-core.c:911
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
In drivers/mfd/88pm860x-core.c (ffffffff816d5b00)
Location: drivers/mfd/88pm860x-core.c:911
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
In drivers/mfd/88pm860x-core.c (ffffffff81711718)
Location: drivers/mfd/88pm860x-core.c:908
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
In drivers/mfd/88pm860x-core.c (ffffffff81735a18)
Location: drivers/mfd/88pm860x-core.c:908
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
void device_power_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff817f2b1f)
Location: drivers/mfd/88pm860x-core.c:908
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff817f2b1f-ffffffff817f2cc3: device_power_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_power_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81c100b7)
Location: drivers/mfd/88pm860x-core.c:908
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81c100b7-ffffffff81c1025b: device_power_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_power_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81c0225e)
Location: drivers/mfd/88pm860x-core.c:908
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81c0225e-ffffffff81c02402: device_power_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_power_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81d06068)
Location: drivers/mfd/88pm860x-core.c:908
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81d06068-ffffffff81d0620c: device_power_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_power_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81ece983)
Location: drivers/mfd/88pm860x-core.c:908
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81ece983-ffffffff81eceb31: device_power_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_power_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81b36020)
Location: drivers/mfd/88pm860x-core.c:908
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81b36020-ffffffff81b361eb: device_power_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_power_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81b89510)
Location: drivers/mfd/88pm860x-core.c:908
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81b89510-ffffffff81b896db: device_power_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_power_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81bdd410)
Location: drivers/mfd/88pm860x-core.c:908
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81bdd410-ffffffff81bdd5db: device_power_init (STB_LOCAL)
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
In drivers/mfd/88pm860x-core.c (ffff80001092cfa4)
Location: drivers/mfd/88pm860x-core.c:908
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
In drivers/mfd/88pm860x-core.c (c0a0b9d0)
Location: drivers/mfd/88pm860x-core.c:908
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
In drivers/mfd/88pm860x-core.c (c0000000009cc468)
Location: drivers/mfd/88pm860x-core.c:908
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
In drivers/mfd/88pm860x-core.c (ffffffe0005a40a6)
Location: drivers/mfd/88pm860x-core.c:908
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
In drivers/mfd/88pm860x-core.c (ffffffff81728ed8)
Location: drivers/mfd/88pm860x-core.c:908
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
In drivers/mfd/88pm860x-core.c (ffffffff81744318)
Location: drivers/mfd/88pm860x-core.c:908
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
