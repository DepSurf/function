# Function: <code>release_locality</code>

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
In drivers/char/tpm/tpm_tis.c (ffffffff81528b60)
Location: drivers/char/tpm/tpm_tis.c:149
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_remove
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
```
**Symbols:**

```
ffffffff81528b60-ffffffff81528ba3: release_locality.isra.3.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void release_locality(struct tpm_chip *chip, int l, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157b3b0)
Location: drivers/char/tpm/tpm_tis_core.c:76
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff8157b3b0-ffffffff8157b444: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void release_locality(struct tpm_chip *chip, int l, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a77e0)
Location: drivers/char/tpm/tpm_tis_core.c:76
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff815a77e0-ffffffff815a7874: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815be8cf)
Location: drivers/char/tpm/tpm_tis_core.c:78
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff815bd470-ffffffff815bd4c0: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816250af)
Location: drivers/char/tpm/tpm_tis_core.c:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81623900-ffffffff81623956: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165dac0)
Location: drivers/char/tpm/tpm_tis_core.c:158
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff8165dac0-ffffffff8165dcd2: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167bf80)
Location: drivers/char/tpm/tpm_tis_core.c:158
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff8167bf80-ffffffff8167c192: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b3be0)
Location: drivers/char/tpm/tpm_tis_core.c:154
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff816b3be0-ffffffff816b3df9: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d68c0)
Location: drivers/char/tpm/tpm_tis_core.c:154
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff816d68c0-ffffffff816d6ad9: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178a7c0)
Location: drivers/char/tpm/tpm_tis_core.c:154
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
```
**Symbols:**

```
ffffffff8178a7c0-ffffffff8178a9d5: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a0930)
Location: drivers/char/tpm/tpm_tis_core.c:138
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
```
**Symbols:**

```
ffffffff817a0930-ffffffff817a0985: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81784484)
Location: drivers/char/tpm/tpm_tis_core.c:138
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff81783640-ffffffff81783695: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180aed4)
Location: drivers/char/tpm/tpm_tis_core.c:139
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff8180a060-ffffffff8180a0b5: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194b277)
Location: drivers/char/tpm/tpm_tis_core.c:139
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff8194a790-ffffffff8194a7f7: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aaed57)
Location: drivers/char/tpm/tpm_tis_core.c:139
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff81aaddf0-ffffffff81aade57: release_locality (STB_LOCAL)
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
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c1068)
Location: drivers/char/tpm/tpm_tis_core.c:154
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffff8000108c1068-ffff8000108c12e0: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c09b9240)
Location: drivers/char/tpm/tpm_tis_core.c:154
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
c09b9240-c09b94ac: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c000000000962860)
Location: drivers/char/tpm/tpm_tis_core.c:154
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_i2c_infineon.c (c000000000966400)
Location: drivers/char/tpm/tpm_i2c_infineon.c:331
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_remove
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_probe
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_probe
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_send
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_recv
```
**Symbols:**

```
c000000000962860-c000000000962c04: release_locality (STB_LOCAL)
c000000000966400-c0000000009664d0: release_locality.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffe000572232)
Location: drivers/char/tpm/tpm_tis_core.c:154
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffe000572232-ffffffe000572402: release_locality (STB_LOCAL)
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
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169c310)
Location: drivers/char/tpm/tpm_tis_core.c:154
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff8169c310-ffffffff8169c529: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81679d00)
Location: drivers/char/tpm/tpm_tis_core.c:154
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81679d00-ffffffff81679f19: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816ca580)
Location: drivers/char/tpm/tpm_tis_core.c:154
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff816ca580-ffffffff816ca799: release_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int release_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e4a50)
Location: drivers/char/tpm/tpm_tis_core.c:154
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff816e4a50-ffffffff816e4c64: release_locality (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int force</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
