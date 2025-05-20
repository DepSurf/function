# Function: <code>tpm2_calc_ordinal_duration</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81525b70)
Location: drivers/char/tpm/tpm2-cmd.c:787
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff81525b70-ffffffff81525ba6: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81578eca)
Location: drivers/char/tpm/tpm2-cmd.c:785
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81578d10-ffffffff81578d46: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a53ea)
Location: drivers/char/tpm/tpm2-cmd.c:815
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff815a5190-ffffffff815a51c6: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815b98a6)
Location: drivers/char/tpm/tpm2-cmd.c:808
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff815b91f0-ffffffff815b9228: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8161feec)
Location: drivers/char/tpm/tpm2-cmd.c:812
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff8161fd30-ffffffff8161fd68: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81659b30)
Location: drivers/char/tpm/tpm2-cmd.c:809
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
```
**Symbols:**

```
ffffffff81659b30-ffffffff81659b68: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81677e50)
Location: drivers/char/tpm/tpm2-cmd.c:146
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_calc_ordinal_duration
```
**Symbols:**

```
ffffffff81677e50-ffffffff81677e7f: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816adf20)
Location: drivers/char/tpm/tpm2-cmd.c:142
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_calc_ordinal_duration
```
**Symbols:**

```
ffffffff816adf20-ffffffff816adf54: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d0c00)
Location: drivers/char/tpm/tpm2-cmd.c:142
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_calc_ordinal_duration
```
**Symbols:**

```
ffffffff816d0c00-ffffffff816d0c34: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81785cc0)
Location: drivers/char/tpm/tpm2-cmd.c:128
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
**Symbols:**

```
ffffffff81785cc0-ffffffff81785cf4: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8179cec0)
Location: drivers/char/tpm/tpm2-cmd.c:128
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
**Symbols:**

```
ffffffff8179cec0-ffffffff8179cef4: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8177f9a0)
Location: drivers/char/tpm/tpm2-cmd.c:128
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
**Symbols:**

```
ffffffff8177f9a0-ffffffff8177f9d4: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81805d30)
Location: drivers/char/tpm/tpm2-cmd.c:128
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
**Symbols:**

```
ffffffff81805d30-ffffffff81805d82: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff819457f0)
Location: drivers/char/tpm/tpm2-cmd.c:128
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
**Symbols:**

```
ffffffff819457f0-ffffffff81945856: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa8840)
Location: drivers/char/tpm/tpm2-cmd.c:128
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
**Symbols:**

```
ffffffff81aa8840-ffffffff81aa88a6: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af4070)
Location: drivers/char/tpm/tpm2-cmd.c:128
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
**Symbols:**

```
ffffffff81af4070-ffffffff81af40d6: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b47630)
Location: drivers/char/tpm/tpm2-cmd.c:128
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
**Symbols:**

```
ffffffff81b47630-ffffffff81b47696: tpm2_calc_ordinal_duration (STB_GLOBAL)
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
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bb420)
Location: drivers/char/tpm/tpm2-cmd.c:142
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_calc_ordinal_duration
```
**Symbols:**

```
ffff8000108bb420-ffff8000108bb480: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c09b4890)
Location: drivers/char/tpm/tpm2-cmd.c:142
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_calc_ordinal_duration
```
**Symbols:**

```
c09b4890-c09b48dc: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c00000000095cac0)
Location: drivers/char/tpm/tpm2-cmd.c:142
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_calc_ordinal_duration
```
**Symbols:**

```
c00000000095cac0-c00000000095cb18: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056c48c)
Location: drivers/char/tpm/tpm2-cmd.c:142
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_calc_ordinal_duration
```
**Symbols:**

```
ffffffe00056c48c-ffffffe00056c4fc: tpm2_calc_ordinal_duration (STB_GLOBAL)
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
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81696650)
Location: drivers/char/tpm/tpm2-cmd.c:142
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_calc_ordinal_duration
```
**Symbols:**

```
ffffffff81696650-ffffffff81696684: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81674040)
Location: drivers/char/tpm/tpm2-cmd.c:142
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_calc_ordinal_duration
```
**Symbols:**

```
ffffffff81674040-ffffffff81674074: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c48c0)
Location: drivers/char/tpm/tpm2-cmd.c:142
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_calc_ordinal_duration
```
**Symbols:**

```
ffffffff816c48c0-ffffffff816c48f4: tpm2_calc_ordinal_duration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int tpm2_calc_ordinal_duration(struct tpm_chip *chip, u32 ordinal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816dee30)
Location: drivers/char/tpm/tpm2-cmd.c:142
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_calc_ordinal_duration
```
**Symbols:**

```
ffffffff816dee30-ffffffff816dee64: tpm2_calc_ordinal_duration (STB_GLOBAL)
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
