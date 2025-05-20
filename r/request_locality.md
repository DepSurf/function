# Function: <code>request_locality</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81528930)
Location: drivers/char/tpm/tpm_tis.c:158
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
```
**Symbols:**

```
ffffffff81528930-ffffffff81528b51: request_locality.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157bd60)
Location: drivers/char/tpm/tpm_tis_core.c:93
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
```
**Symbols:**

```
ffffffff8157bd60-ffffffff8157bf4b: request_locality.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a8200)
Location: drivers/char/tpm/tpm_tis_core.c:93
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
```
**Symbols:**

```
ffffffff815a8200-ffffffff815a83c4: request_locality.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815bd700)
Location: drivers/char/tpm/tpm_tis_core.c:85
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff815bd700-ffffffff815bd8b8: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81623bd0)
Location: drivers/char/tpm/tpm_tis_core.c:87
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81623bd0-ffffffff81623d8b: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165dce0)
Location: drivers/char/tpm/tpm_tis_core.c:195
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff8165dce0-ffffffff8165dea7: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167c1a0)
Location: drivers/char/tpm/tpm_tis_core.c:195
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff8167c1a0-ffffffff8167c367: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b30e0)
Location: drivers/char/tpm/tpm_tis_core.c:191
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff816b30e0-ffffffff816b32b8: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d5dc0)
Location: drivers/char/tpm/tpm_tis_core.c:191
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff816d5dc0-ffffffff816d5f98: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178a300)
Location: drivers/char/tpm/tpm_tis_core.c:191
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
```
**Symbols:**

```
ffffffff8178a300-ffffffff8178a4d8: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a1280)
Location: drivers/char/tpm/tpm_tis_core.c:147
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
```
**Symbols:**

```
ffffffff817a1280-ffffffff817a1458: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81783e10)
Location: drivers/char/tpm/tpm_tis_core.c:147
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff81783e10-ffffffff81783fe8: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180a840)
Location: drivers/char/tpm/tpm_tis_core.c:148
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff8180a840-ffffffff8180aa21: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194a2e0)
Location: drivers/char/tpm/tpm_tis_core.c:148
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff8194a2e0-ffffffff8194a4ff: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aad970)
Location: drivers/char/tpm/tpm_tis_core.c:148
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff81aad970-ffffffff81aadb84: request_locality (STB_LOCAL)
```
</details>
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
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c0e38)
Location: drivers/char/tpm/tpm_tis_core.c:191
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffff8000108c0e38-ffff8000108c1068: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c09b94ac)
Location: drivers/char/tpm/tpm_tis_core.c:191
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
c09b94ac-c09b96b8: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c000000000962c10)
Location: drivers/char/tpm/tpm_tis_core.c:191
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_i2c_infineon.c (c0000000009667a0)
Location: drivers/char/tpm/tpm_i2c_infineon.c:344
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_probe
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_send
```
**Symbols:**

```
c000000000962c10-c000000000962f54: request_locality (STB_LOCAL)
c0000000009667a0-c000000000966898: request_locality.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffe000572402)
Location: drivers/char/tpm/tpm_tis_core.c:191
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffe000572402-ffffffe000572598: request_locality (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169b810)
Location: drivers/char/tpm/tpm_tis_core.c:191
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff8169b810-ffffffff8169b9e8: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81679200)
Location: drivers/char/tpm/tpm_tis_core.c:191
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81679200-ffffffff816793d8: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816c9a80)
Location: drivers/char/tpm/tpm_tis_core.c:191
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff816c9a80-ffffffff816c9c58: request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e3f60)
Location: drivers/char/tpm/tpm_tis_core.c:191
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff816e3f60-ffffffff816e4133: request_locality (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
