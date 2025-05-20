# Function: <code>tpm_tis_update_timeouts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81528440)
Location: drivers/char/tpm/tpm_tis.c:448
Inline: False
```
**Symbols:**

```
ffffffff81528440-ffffffff815284a0: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157b5f0)
Location: drivers/char/tpm/tpm_tis_core.c:407
Inline: False
```
**Symbols:**

```
ffffffff8157b5f0-ffffffff8157b68a: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a7a20)
Location: drivers/char/tpm/tpm_tis_core.c:429
Inline: False
```
**Symbols:**

```
ffffffff815a7a20-ffffffff815a7aba: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815be450)
Location: drivers/char/tpm/tpm_tis_core.c:417
Inline: True
```
**Symbols:**

```
ffffffff815be450-ffffffff815be4e5: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81623e40)
Location: drivers/char/tpm/tpm_tis_core.c:420
Inline: False
```
**Symbols:**

```
ffffffff81623e40-ffffffff81623f1f: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165e530)
Location: drivers/char/tpm/tpm_tis_core.c:528
Inline: False
```
**Symbols:**

```
ffffffff8165e530-ffffffff8165e610: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167c9f0)
Location: drivers/char/tpm/tpm_tis_core.c:524
Inline: False
```
**Symbols:**

```
ffffffff8167c9f0-ffffffff8167cad0: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:520
Inline: False
```
**Symbols:**

```
ffffffff816b2d70-ffffffff816b2e54: tpm_tis_update_timeouts (STB_LOCAL)
ffffffff816b40b2-ffffffff816b40cf: tpm_tis_update_timeouts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:520
Inline: False
```
**Symbols:**

```
ffffffff816d5a50-ffffffff816d5b34: tpm_tis_update_timeouts (STB_LOCAL)
ffffffff816d6d92-ffffffff816d6daf: tpm_tis_update_timeouts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:601
Inline: False
```
**Symbols:**

```
ffffffff81789e60-ffffffff81789f44: tpm_tis_update_timeouts (STB_LOCAL)
ffffffff8178b23c-ffffffff8178b259: tpm_tis_update_timeouts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:568
Inline: False
```
**Symbols:**

```
ffffffff817a0ca0-ffffffff817a0d84: tpm_tis_update_timeouts (STB_LOCAL)
ffffffff81c0a92f-ffffffff81c0a94c: tpm_tis_update_timeouts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:579
Inline: False
```
**Symbols:**

```
ffffffff817838a0-ffffffff81783978: tpm_tis_update_timeouts (STB_LOCAL)
ffffffff81bfc3fe-ffffffff81bfc41b: tpm_tis_update_timeouts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:580
Inline: False
```
**Symbols:**

```
ffffffff8180a2c0-ffffffff8180a398: tpm_tis_update_timeouts (STB_LOCAL)
ffffffff81cfd12e-ffffffff81cfd14b: tpm_tis_update_timeouts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:580
Inline: False
```
**Symbols:**

```
ffffffff8194ab70-ffffffff8194ac6e: tpm_tis_update_timeouts (STB_LOCAL)
ffffffff81ec5c6c-ffffffff81ec5c89: tpm_tis_update_timeouts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aae250)
Location: drivers/char/tpm/tpm_tis_core.c:594
Inline: False
```
**Symbols:**

```
ffffffff81aae250-ffffffff81aae362: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81af9f80)
Location: drivers/char/tpm/tpm_tis_core.c:661
Inline: False
```
**Symbols:**

```
ffffffff81af9f80-ffffffff81afa095: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4d5a0)
Location: drivers/char/tpm/tpm_tis_core.c:689
Inline: False
```
**Symbols:**

```
ffffffff81b4d5a0-ffffffff81b4d6b5: tpm_tis_update_timeouts (STB_LOCAL)
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
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c0aa8)
Location: drivers/char/tpm/tpm_tis_core.c:520
Inline: False
```
**Symbols:**

```
ffff8000108c0aa8-ffff8000108c0ba8: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c09b9d8c)
Location: drivers/char/tpm/tpm_tis_core.c:520
Inline: False
```
**Symbols:**

```
c09b9d8c-c09b9e9c: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c000000000963930)
Location: drivers/char/tpm/tpm_tis_core.c:520
Inline: False
```
**Symbols:**

```
c000000000963930-c000000000963a8c: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffe000572aec)
Location: drivers/char/tpm/tpm_tis_core.c:520
Inline: False
```
**Symbols:**

```
ffffffe000572aec-ffffffe000572b9c: tpm_tis_update_timeouts (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:520
Inline: False
```
**Symbols:**

```
ffffffff8169b4a0-ffffffff8169b584: tpm_tis_update_timeouts (STB_LOCAL)
ffffffff8169c7e2-ffffffff8169c7ff: tpm_tis_update_timeouts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:520
Inline: False
```
**Symbols:**

```
ffffffff81678e90-ffffffff81678f74: tpm_tis_update_timeouts (STB_LOCAL)
ffffffff8167a1d2-ffffffff8167a1ef: tpm_tis_update_timeouts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:520
Inline: False
```
**Symbols:**

```
ffffffff816c9710-ffffffff816c97f4: tpm_tis_update_timeouts (STB_LOCAL)
ffffffff816caa52-ffffffff816caa6f: tpm_tis_update_timeouts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void tpm_tis_update_timeouts(struct tpm_chip *chip, long unsigned int *timeout_cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:520
Inline: False
```
**Symbols:**

```
ffffffff816e3bf0-ffffffff816e3cd4: tpm_tis_update_timeouts (STB_LOCAL)
ffffffff816e4f22-ffffffff816e4f3f: tpm_tis_update_timeouts.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
