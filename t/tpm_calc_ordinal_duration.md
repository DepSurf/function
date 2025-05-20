# Function: <code>tpm_calc_ordinal_duration</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81523570)
Location: drivers/char/tpm/tpm-interface.c:308
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
```
**Symbols:**

```
ffffffff81523570-ffffffff815235a5: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81576d5c)
Location: drivers/char/tpm/tpm-interface.c:308
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff815764b0-ffffffff815764e5: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a3df9)
Location: drivers/char/tpm/tpm-interface.c:309
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff815a2b40-ffffffff815a2b75: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b7f59)
Location: drivers/char/tpm/tpm-interface.c:309
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff815b66d0-ffffffff815b6707: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161ea69)
Location: drivers/char/tpm/tpm-interface.c:309
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff8161d3e0-ffffffff8161d417: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816587cd)
Location: drivers/char/tpm/tpm-interface.c:308
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81657080-ffffffff816570b7: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81676160)
Location: drivers/char/tpm/tpm-interface.c:56
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81676160-ffffffff81676180: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816abf70)
Location: drivers/char/tpm/tpm-interface.c:51
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff816abf70-ffffffff816abf90: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816cecf0)
Location: drivers/char/tpm/tpm-interface.c:51
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff816cecf0-ffffffff816ced10: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81783f97)
Location: drivers/char/tpm/tpm-interface.c:52
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81783bf0-ffffffff81783c10: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8179b4e7)
Location: drivers/char/tpm/tpm-interface.c:52
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff8179b140-ffffffff8179b160: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8177e025)
Location: drivers/char/tpm/tpm-interface.c:52
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff8177dc80-ffffffff8177dca0: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81804215)
Location: drivers/char/tpm/tpm-interface.c:52
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81803e70-ffffffff81803e90: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81943b53)
Location: drivers/char/tpm/tpm-interface.c:52
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81943750-ffffffff81943780: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81aa6678)
Location: drivers/char/tpm/tpm-interface.c:52
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81aa6200-ffffffff81aa6230: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81af1ec8)
Location: drivers/char/tpm/tpm-interface.c:52
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81af1a20-ffffffff81af1a50: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81b45458)
Location: drivers/char/tpm/tpm-interface.c:52
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81b44fb0-ffffffff81b44fe0: tpm_calc_ordinal_duration (STB_GLOBAL)
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
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffff8000108b9238)
Location: drivers/char/tpm/tpm-interface.c:51
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffff8000108b9238-ffff8000108b9288: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c09b2704)
Location: drivers/char/tpm/tpm-interface.c:51
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
c09b2704-c09b2734: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c000000000959fb0)
Location: drivers/char/tpm/tpm-interface.c:51
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_send
```
**Symbols:**

```
c000000000959fb0-c00000000095a008: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffe000569688)
Location: drivers/char/tpm/tpm-interface.c:51
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffe000569688-ffffffe0005696d6: tpm_calc_ordinal_duration (STB_GLOBAL)
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
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81694740)
Location: drivers/char/tpm/tpm-interface.c:51
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81694740-ffffffff81694760: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81672130)
Location: drivers/char/tpm/tpm-interface.c:51
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81672130-ffffffff81672150: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816c29b0)
Location: drivers/char/tpm/tpm-interface.c:51
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff816c29b0-ffffffff816c29d0: tpm_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int tpm_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816dcf80)
Location: drivers/char/tpm/tpm-interface.c:51
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff816dcf80-ffffffff816dcfa0: tpm_calc_ordinal_duration (STB_GLOBAL)
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
