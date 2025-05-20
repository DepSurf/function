# Function: <code>tpm2_get_random</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81526360)
Location: drivers/char/tpm/tpm2-cmd.c:359
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff81526360-ffffffff815264bf: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81579400)
Location: drivers/char/tpm/tpm2-cmd.c:359
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff81579400-ffffffff81579561: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a5930)
Location: drivers/char/tpm/tpm2-cmd.c:359
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff815a5930-ffffffff815a5a93: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815b9c30)
Location: drivers/char/tpm/tpm2-cmd.c:347
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff815b9c30-ffffffff815b9db7: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81620480)
Location: drivers/char/tpm/tpm2-cmd.c:347
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff81620480-ffffffff81620607: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:344
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff8165b466-ffffffff8165b472: tpm2_get_random.cold.8 (STB_LOCAL)
ffffffff8165a250-ffffffff8165a3d1: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816781d0)
Location: drivers/char/tpm/tpm2-cmd.c:291
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff816781d0-ffffffff8167835e: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816ae5d0)
Location: drivers/char/tpm/tpm2-cmd.c:302
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff816ae5d0-ffffffff816ae7d8: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d12c0)
Location: drivers/char/tpm/tpm2-cmd.c:302
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff816d12c0-ffffffff816d14c8: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81786260)
Location: drivers/char/tpm/tpm2-cmd.c:288
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff81786260-ffffffff8178643d: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8179d460)
Location: drivers/char/tpm/tpm2-cmd.c:288
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff8179d460-ffffffff8179d63d: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8177ff40)
Location: drivers/char/tpm/tpm2-cmd.c:288
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff8177ff40-ffffffff81780121: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81806310)
Location: drivers/char/tpm/tpm2-cmd.c:288
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff81806310-ffffffff818064f1: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81945e20)
Location: drivers/char/tpm/tpm2-cmd.c:288
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff81945e20-ffffffff8194601a: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa8ea0)
Location: drivers/char/tpm/tpm2-cmd.c:288
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff81aa8ea0-ffffffff81aa9097: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af46d0)
Location: drivers/char/tpm/tpm2-cmd.c:288
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff81af46d0-ffffffff81af48c7: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b47c90)
Location: drivers/char/tpm/tpm2-cmd.c:288
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff81b47c90-ffffffff81b47e87: tpm2_get_random (STB_GLOBAL)
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
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bbbb0)
Location: drivers/char/tpm/tpm2-cmd.c:302
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffff8000108bbbb0-ffff8000108bbdec: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c09b4f04)
Location: drivers/char/tpm/tpm2-cmd.c:302
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
c09b4f04-c09b518c: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c00000000095d3d0)
Location: drivers/char/tpm/tpm2-cmd.c:302
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
c00000000095d3d0-c00000000095d700: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056d020)
Location: drivers/char/tpm/tpm2-cmd.c:302
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffe00056d020-ffffffe00056d302: tpm2_get_random (STB_GLOBAL)
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
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81696d10)
Location: drivers/char/tpm/tpm2-cmd.c:302
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff81696d10-ffffffff81696f18: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81674700)
Location: drivers/char/tpm/tpm2-cmd.c:302
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff81674700-ffffffff81674908: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c4f80)
Location: drivers/char/tpm/tpm2-cmd.c:302
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff816c4f80-ffffffff816c5188: tpm2_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm2_get_random(struct tpm_chip *chip, u8 *dest, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816df4d0)
Location: drivers/char/tpm/tpm2-cmd.c:302
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
```
**Symbols:**

```
ffffffff816df4d0-ffffffff816df6cd: tpm2_get_random (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *dest</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 *out</code>
</li>
</ul>
</details>
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
