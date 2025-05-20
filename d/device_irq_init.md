# Function: <code>device_irq_init</code>

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
In drivers/mfd/88pm860x-core.c (ffffffff8157a6eb)
Location: drivers/mfd/88pm860x-core.c:570
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
In drivers/mfd/88pm860x-core.c (ffffffff815cf74b)
Location: drivers/mfd/88pm860x-core.c:570
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
In drivers/mfd/88pm860x-core.c (ffffffff815fc38b)
Location: drivers/mfd/88pm860x-core.c:570
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
In drivers/mfd/88pm860x-core.c (ffffffff8161014f)
Location: drivers/mfd/88pm860x-core.c:570
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
In drivers/mfd/88pm860x-core.c (ffffffff816789cf)
Location: drivers/mfd/88pm860x-core.c:570
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
In drivers/mfd/88pm860x-core.c (ffffffff816b4466)
Location: drivers/mfd/88pm860x-core.c:570
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
In drivers/mfd/88pm860x-core.c (ffffffff816d56e6)
Location: drivers/mfd/88pm860x-core.c:570
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
In drivers/mfd/88pm860x-core.c (ffffffff817111ca)
Location: drivers/mfd/88pm860x-core.c:567
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
In drivers/mfd/88pm860x-core.c (ffffffff817354ca)
Location: drivers/mfd/88pm860x-core.c:567
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
int device_irq_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff817f2cd8)
Location: drivers/mfd/88pm860x-core.c:567
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff817f2cd8-ffffffff817f2ed9: device_irq_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_irq_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81c10270)
Location: drivers/mfd/88pm860x-core.c:567
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81c10270-ffffffff81c10471: device_irq_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_irq_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81c0241e)
Location: drivers/mfd/88pm860x-core.c:567
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81c0241e-ffffffff81c0261e: device_irq_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_irq_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81d06221)
Location: drivers/mfd/88pm860x-core.c:567
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81d06221-ffffffff81d06421: device_irq_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_irq_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81eceb31)
Location: drivers/mfd/88pm860x-core.c:567
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81eceb31-ffffffff81eced42: device_irq_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_irq_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81b36200)
Location: drivers/mfd/88pm860x-core.c:567
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81b36200-ffffffff81b3643a: device_irq_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_irq_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81b896f0)
Location: drivers/mfd/88pm860x-core.c:567
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81b896f0-ffffffff81b8992a: device_irq_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_irq_init(struct pm860x_chip *chip, struct pm860x_platform_data *pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-core.c (ffffffff81bdd5f0)
Location: drivers/mfd/88pm860x-core.c:567
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
```
**Symbols:**

```
ffffffff81bdd5f0-ffffffff81bdd82a: device_irq_init (STB_LOCAL)
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
In drivers/mfd/88pm860x-core.c (ffff80001092cb24)
Location: drivers/mfd/88pm860x-core.c:567
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
In drivers/mfd/88pm860x-core.c (c0a0b4fc)
Location: drivers/mfd/88pm860x-core.c:567
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
In drivers/mfd/88pm860x-core.c (c0000000009cbe30)
Location: drivers/mfd/88pm860x-core.c:567
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
In drivers/mfd/88pm860x-core.c (ffffffe0005a3bca)
Location: drivers/mfd/88pm860x-core.c:567
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
In drivers/mfd/88pm860x-core.c (ffffffff8172898a)
Location: drivers/mfd/88pm860x-core.c:567
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
In drivers/mfd/88pm860x-core.c (ffffffff81743dca)
Location: drivers/mfd/88pm860x-core.c:567
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
