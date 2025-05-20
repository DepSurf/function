# Function: <code>tpm_chip_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81525900)
Location: drivers/char/tpm/tpm-chip.c:222
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
```
**Symbols:**

```
ffffffff81525900-ffffffff81525aef: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81578a10)
Location: drivers/char/tpm/tpm-chip.c:353
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81578a10-ffffffff81578c52: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff815a4c90)
Location: drivers/char/tpm/tpm-chip.c:333
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff815a4c90-ffffffff815a4e83: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff815b8c20)
Location: drivers/char/tpm/tpm-chip.c:408
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff815b8c20-ffffffff815b8e16: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff8161f740)
Location: drivers/char/tpm/tpm-chip.c:401
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff8161f740-ffffffff8161f936: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81659500)
Location: drivers/char/tpm/tpm-chip.c:426
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff81659500-ffffffff81659758: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816754d0)
Location: drivers/char/tpm/tpm-chip.c:450
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff816754d0-ffffffff81675708: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816ab215)
Location: drivers/char/tpm/tpm-chip.c:582
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff816ab720-ffffffff816ab7b1: tpm_chip_register.cold (STB_LOCAL)
ffffffff816ab180-ffffffff816ab396: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816cdf55)
Location: drivers/char/tpm/tpm-chip.c:579
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff816ce460-ffffffff816ce4f5: tpm_chip_register.cold (STB_LOCAL)
ffffffff816cdec0-ffffffff816ce0d6: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81783110)
Location: drivers/char/tpm/tpm-chip.c:574
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff81783110-ffffffff8178327e: tpm_chip_register.part.0 (STB_LOCAL)
ffffffff81783280-ffffffff8178330d: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff8179a760)
Location: drivers/char/tpm/tpm-chip.c:574
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff8179a760-ffffffff8179a8ce: tpm_chip_register.part.0 (STB_LOCAL)
ffffffff8179a8d0-ffffffff8179a95d: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff8177d420)
Location: drivers/char/tpm/tpm-chip.c:574
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff8177d240-ffffffff8177d41a: tpm_chip_register.part.0 (STB_LOCAL)
ffffffff81bfbd37-ffffffff81bfbdcf: tpm_chip_register.part.0.cold (STB_LOCAL)
ffffffff8177d420-ffffffff8177d4ad: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81803600)
Location: drivers/char/tpm/tpm-chip.c:582
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff81803420-ffffffff818035fa: tpm_chip_register.part.0 (STB_LOCAL)
ffffffff81cfc9c1-ffffffff81cfca59: tpm_chip_register.part.0.cold (STB_LOCAL)
ffffffff81803600-ffffffff8180368d: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81942e40)
Location: drivers/char/tpm/tpm-chip.c:557
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff81942c50-ffffffff81942e33: tpm_chip_register.part.0 (STB_LOCAL)
ffffffff81ec51fc-ffffffff81ec5236: tpm_chip_register.part.0.cold (STB_LOCAL)
ffffffff81942e40-ffffffff81942ef7: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81aa5470)
Location: drivers/char/tpm/tpm-chip.c:620
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff81aa5470-ffffffff81aa5798: tpm_chip_register.part.0 (STB_LOCAL)
ffffffff81aa57b0-ffffffff81aa5867: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81af0dc0)
Location: drivers/char/tpm/tpm-chip.c:611
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff81af0dc0-ffffffff81af0fe8: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81b443a0)
Location: drivers/char/tpm/tpm-chip.c:616
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff81b443a0-ffffffff81b445c8: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffff8000108b83b8)
Location: drivers/char/tpm/tpm-chip.c:579
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffff8000108b83b8-ffff8000108b8654: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (c09b1be4)
Location: drivers/char/tpm/tpm-chip.c:579
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
c09b1be4-c09b1e64: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (c000000000958b60)
Location: drivers/char/tpm/tpm-chip.c:579
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_probe
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_probe
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
```
**Symbols:**

```
c000000000958b60-c000000000958ec4: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffe00056897c)
Location: drivers/char/tpm/tpm-chip.c:579
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffe00056897c-ffffffe000568bc8: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816939a5)
Location: drivers/char/tpm/tpm-chip.c:579
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff81693eb0-ffffffff81693f45: tpm_chip_register.cold (STB_LOCAL)
ffffffff81693910-ffffffff81693b26: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81671395)
Location: drivers/char/tpm/tpm-chip.c:579
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff816718a0-ffffffff81671935: tpm_chip_register.cold (STB_LOCAL)
ffffffff81671300-ffffffff81671516: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816c1c15)
Location: drivers/char/tpm/tpm-chip.c:579
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff816c2120-ffffffff816c21b5: tpm_chip_register.cold (STB_LOCAL)
ffffffff816c1b80-ffffffff816c1d96: tpm_chip_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_chip_register(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816dc1e5)
Location: drivers/char/tpm/tpm-chip.c:579
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff816dc6f0-ffffffff816dc785: tpm_chip_register.cold (STB_LOCAL)
ffffffff816dc150-ffffffff816dc366: tpm_chip_register (STB_GLOBAL)
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
