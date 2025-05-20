# Function: <code>sec_irq_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/sec-irq.c (ffffffff81595fb0)
Location: drivers/mfd/sec-irq.c:440
Inline: False
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff81595fb0-ffffffff81596093: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/sec-irq.c (ffffffff815eada0)
Location: drivers/mfd/sec-irq.c:445
Inline: False
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff815eada0-ffffffff815eae88: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/sec-irq.c (ffffffff81617bb0)
Location: drivers/mfd/sec-irq.c:445
Inline: False
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff81617bb0-ffffffff81617c98: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/sec-irq.c (ffffffff8162bab0)
Location: drivers/mfd/sec-irq.c:445
Inline: False
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff8162bab0-ffffffff8162bb8e: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/sec-irq.c (ffffffff81694400)
Location: drivers/mfd/sec-irq.c:445
Inline: False
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff81694400-ffffffff816944e4: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/sec-irq.c (ffffffff816d04d0)
Location: drivers/mfd/sec-irq.c:445
Inline: False
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff816d04d0-ffffffff816d05b4: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/sec-irq.c (ffffffff816f1af0)
Location: drivers/mfd/sec-irq.c:438
Inline: False
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff816f1af0-ffffffff816f1bec: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/sec-irq.c (ffffffff8172b1c1)
Location: drivers/mfd/sec-irq.c:438
Inline: True
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff8172b1c1-ffffffff8172b214: sec_irq_init.cold (STB_LOCAL)
ffffffff8172b160-ffffffff8172b1c1: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/sec-irq.c (ffffffff8174f3c1)
Location: drivers/mfd/sec-irq.c:438
Inline: True
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff8174f3c1-ffffffff8174f414: sec_irq_init.cold (STB_LOCAL)
ffffffff8174f360-ffffffff8174f3c1: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/sec-irq.c (0)
Location: drivers/mfd/sec-irq.c:438
Inline: False
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff8180dad1-ffffffff8180db24: sec_irq_init.cold (STB_LOCAL)
ffffffff8180da70-ffffffff8180dad1: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/sec-irq.c (0)
Location: drivers/mfd/sec-irq.c:438
Inline: False
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff81c1581e-ffffffff81c15871: sec_irq_init.cold (STB_LOCAL)
ffffffff8181c7d0-ffffffff8181c831: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/sec-irq.c (0)
Location: drivers/mfd/sec-irq.c:438
Inline: False
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff81c07579-ffffffff81c075cc: sec_irq_init.cold (STB_LOCAL)
ffffffff817ffba0-ffffffff817ffc01: sec_irq_init (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/sec-irq.c (ffff80001094e4c8)
Location: drivers/mfd/sec-irq.c:438
Inline: True
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffff80001094e4c8-ffff80001094e578: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/sec-irq.c (c0a3850c)
Location: drivers/mfd/sec-irq.c:438
Inline: True
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
c0a3850c-c0a385d8: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/sec-irq.c (c0000000009fad70)
Location: drivers/mfd/sec-irq.c:438
Inline: True
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
c0000000009fad70-c0000000009fae58: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/sec-irq.c (ffffffe0005bf34c)
Location: drivers/mfd/sec-irq.c:438
Inline: True
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffe0005bf34c-ffffffe0005bf3fc: sec_irq_init (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/sec-irq.c (ffffffff81742881)
Location: drivers/mfd/sec-irq.c:438
Inline: True
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff81742881-ffffffff817428d4: sec_irq_init.cold (STB_LOCAL)
ffffffff81742820-ffffffff81742881: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sec_irq_init(struct sec_pmic_dev *sec_pmic);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/sec-irq.c (ffffffff8175dcc1)
Location: drivers/mfd/sec-irq.c:438
Inline: True
Direct callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff8175dcc1-ffffffff8175dd14: sec_irq_init.cold (STB_LOCAL)
ffffffff8175dc60-ffffffff8175dcc1: sec_irq_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
