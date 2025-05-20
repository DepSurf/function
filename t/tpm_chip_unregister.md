# Function: <code>tpm_chip_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81525830)
Location: drivers/char/tpm/tpm-chip.c:270
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
```
**Symbols:**

```
ffffffff81525830-ffffffff815258da: tpm_chip_unregister.part.2 (STB_LOCAL)
ffffffff815258e0-ffffffff815258fa: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81578930)
Location: drivers/char/tpm/tpm-chip.c:403
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
```
**Symbols:**

```
ffffffff81578930-ffffffff81578a05: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff815a4bf0)
Location: drivers/char/tpm/tpm-chip.c:383
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
```
**Symbols:**

```
ffffffff815a4bf0-ffffffff815a4c8f: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff815b8b60)
Location: drivers/char/tpm/tpm-chip.c:458
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
```
**Symbols:**

```
ffffffff815b8b60-ffffffff815b8c1f: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff8161f680)
Location: drivers/char/tpm/tpm-chip.c:451
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
```
**Symbols:**

```
ffffffff8161f680-ffffffff8161f73f: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81659430)
Location: drivers/char/tpm/tpm-chip.c:486
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff81659430-ffffffff816594fa: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81675400)
Location: drivers/char/tpm/tpm-chip.c:505
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff81675400-ffffffff816754ca: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816ab0a0)
Location: drivers/char/tpm/tpm-chip.c:647
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff816ab0a0-ffffffff816ab17e: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816cdde0)
Location: drivers/char/tpm/tpm-chip.c:644
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff816cdde0-ffffffff816cdebe: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81782fe0)
Location: drivers/char/tpm/tpm-chip.c:637
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff81782fe0-ffffffff81783107: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff8179a630)
Location: drivers/char/tpm/tpm-chip.c:637
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff8179a630-ffffffff8179a757: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff8177d110)
Location: drivers/char/tpm/tpm-chip.c:637
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff8177d110-ffffffff8177d237: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff818032e0)
Location: drivers/char/tpm/tpm-chip.c:645
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff818032e0-ffffffff81803411: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81942b50)
Location: drivers/char/tpm/tpm-chip.c:620
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff81942b50-ffffffff81942c4b: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81aa5360)
Location: drivers/char/tpm/tpm-chip.c:683
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff81aa5360-ffffffff81aa545b: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81af0cb0)
Location: drivers/char/tpm/tpm-chip.c:664
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff81af0cb0-ffffffff81af0da5: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81b44290)
Location: drivers/char/tpm/tpm-chip.c:669
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff81b44290-ffffffff81b44385: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffff8000108b82b8)
Location: drivers/char/tpm/tpm-chip.c:644
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffff8000108b82b8-ffff8000108b83b4: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (c09b1b00)
Location: drivers/char/tpm/tpm-chip.c:644
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
```
**Symbols:**

```
c09b1b00-c09b1be4: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (c0000000009589f0)
Location: drivers/char/tpm/tpm-chip.c:644
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_remove
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_remove
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_remove
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
```
**Symbols:**

```
c0000000009589f0-c000000000958b58: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffe00056888a)
Location: drivers/char/tpm/tpm-chip.c:644
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
```
**Symbols:**

```
ffffffe00056888a-ffffffe00056897c: tpm_chip_unregister (STB_GLOBAL)
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
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81693830)
Location: drivers/char/tpm/tpm-chip.c:644
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff81693830-ffffffff8169390e: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81671220)
Location: drivers/char/tpm/tpm-chip.c:644
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff81671220-ffffffff816712fe: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816c1aa0)
Location: drivers/char/tpm/tpm-chip.c:644
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff816c1aa0-ffffffff816c1b7e: tpm_chip_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tpm_chip_unregister(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816dc070)
Location: drivers/char/tpm/tpm-chip.c:644
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_remove
  - drivers/char/tpm/tpm_crb.c:crb_acpi_remove
```
**Symbols:**

```
ffffffff816dc070-ffffffff816dc14e: tpm_chip_unregister (STB_GLOBAL)
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
