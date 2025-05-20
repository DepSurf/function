# Function: <code>tpm_get_timeouts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815243b0)
Location: drivers/char/tpm/tpm-interface.c:498
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
```
**Symbols:**

```
ffffffff815243b0-ffffffff81524792: tpm_get_timeouts.part.3 (STB_LOCAL)
ffffffff815247a0-ffffffff81524809: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815779a1)
Location: drivers/char/tpm/tpm-interface.c:497
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_auto_startup
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81577320-ffffffff81577715: tpm_get_timeouts.part.2 (STB_LOCAL)
ffffffff81577720-ffffffff81577789: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a3910)
Location: drivers/char/tpm/tpm-interface.c:499
Inline: True
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff815a3910-ffffffff815a3c43: tpm_get_timeouts.part.2 (STB_LOCAL)
ffffffff815a3c50-ffffffff815a3cca: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b7a60)
Location: drivers/char/tpm/tpm-interface.c:630
Inline: True
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff815b7a60-ffffffff815b7dab: tpm_get_timeouts.part.6 (STB_LOCAL)
ffffffff815b7db0-ffffffff815b7e2b: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161e570)
Location: drivers/char/tpm/tpm-interface.c:648
Inline: True
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff8161e570-ffffffff8161e8be: tpm_get_timeouts.part.6 (STB_LOCAL)
ffffffff8161e8c0-ffffffff8161e93b: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81658280)
Location: drivers/char/tpm/tpm-interface.c:767
Inline: True
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81658280-ffffffff816585fe: tpm_get_timeouts.part.6 (STB_LOCAL)
ffffffff81658600-ffffffff81658685: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81676180)
Location: drivers/char/tpm/tpm-interface.c:422
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81676180-ffffffff816761aa: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816abf90)
Location: drivers/char/tpm/tpm-interface.c:238
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff816abf90-ffffffff816abfba: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816ced10)
Location: drivers/char/tpm/tpm-interface.c:238
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff816ced10-ffffffff816ced3a: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81783c10)
Location: drivers/char/tpm/tpm-interface.c:239
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81783c10-ffffffff81783c3a: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8179b160)
Location: drivers/char/tpm/tpm-interface.c:239
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff8179b160-ffffffff8179b18a: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8177dca0)
Location: drivers/char/tpm/tpm-interface.c:239
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff8177dca0-ffffffff8177dcca: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81803e90)
Location: drivers/char/tpm/tpm-interface.c:239
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81803e90-ffffffff81803eba: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81943780)
Location: drivers/char/tpm/tpm-interface.c:239
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81943780-ffffffff819437c2: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81aa6240)
Location: drivers/char/tpm/tpm-interface.c:239
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81aa6240-ffffffff81aa6282: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81af1a60)
Location: drivers/char/tpm/tpm-interface.c:239
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81af1a60-ffffffff81af1aa2: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81b44ff0)
Location: drivers/char/tpm/tpm-interface.c:239
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81b44ff0-ffffffff81b45032: tpm_get_timeouts (STB_GLOBAL)
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
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffff8000108b9288)
Location: drivers/char/tpm/tpm-interface.c:238
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffff8000108b9288-ffff8000108b92e4: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c09b2734)
Location: drivers/char/tpm/tpm-interface.c:238
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
c09b2734-c09b2774: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c00000000095a010)
Location: drivers/char/tpm/tpm-interface.c:238
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
c00000000095a010-c00000000095a088: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffe0005696d6)
Location: drivers/char/tpm/tpm-interface.c:238
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffe0005696d6-ffffffe000569722: tpm_get_timeouts (STB_GLOBAL)
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
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81694760)
Location: drivers/char/tpm/tpm-interface.c:238
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81694760-ffffffff8169478a: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81672150)
Location: drivers/char/tpm/tpm-interface.c:238
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81672150-ffffffff8167217a: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816c29d0)
Location: drivers/char/tpm/tpm-interface.c:238
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff816c29d0-ffffffff816c29fa: tpm_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816dcfa0)
Location: drivers/char/tpm/tpm-interface.c:238
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff816dcfa0-ffffffff816dcfca: tpm_get_timeouts (STB_GLOBAL)
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
