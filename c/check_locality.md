# Function: <code>check_locality</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81528657)
Location: drivers/char/tpm/tpm_tis.c:139
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tis_int_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157b330)
Location: drivers/char/tpm/tpm_tis_core.c:59
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
```
**Symbols:**

```
ffffffff8157b330-ffffffff8157b3a7: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a7760)
Location: drivers/char/tpm/tpm_tis_core.c:59
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
```
**Symbols:**

```
ffffffff815a7760-ffffffff815a77d7: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815bd3f0)
Location: drivers/char/tpm/tpm_tis_core.c:59
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff815bd3f0-ffffffff815bd46a: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81623880)
Location: drivers/char/tpm/tpm_tis_core.c:61
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff81623880-ffffffff81623900: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165d7d0)
Location: drivers/char/tpm/tpm_tis_core.c:122
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff8165d7d0-ffffffff8165d850: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167bc90)
Location: drivers/char/tpm/tpm_tis_core.c:122
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff8167bc90-ffffffff8167bd10: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b29d0)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff816b29d0-ffffffff816b2a50: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d56b0)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff816d56b0-ffffffff816d5730: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817899b0)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff817899b0-ffffffff81789a30: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a08b0)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff817a08b0-ffffffff817a0930: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817835c0)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff817835c0-ffffffff81783640: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81809fe0)
Location: drivers/char/tpm/tpm_tis_core.c:119
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff81809fe0-ffffffff8180a060: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194a080)
Location: drivers/char/tpm/tpm_tis_core.c:119
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff8194a080-ffffffff8194a113: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aad6b0)
Location: drivers/char/tpm/tpm_tis_core.c:119
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff81aad6b0-ffffffff81aad743: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81af8f40)
Location: drivers/char/tpm/tpm_tis_core.c:151
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
```
**Symbols:**

```
ffffffff81af8f40-ffffffff81af8fd6: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4c560)
Location: drivers/char/tpm/tpm_tis_core.c:151
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
```
**Symbols:**

```
ffffffff81b4c560-ffffffff81b4c5f6: check_locality (STB_LOCAL)
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
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c06f0)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffff8000108c06f0-ffff8000108c0794: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c09b8f7c)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
c09b8f7c-c09b9014: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c000000000962560)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
```
In drivers/char/tpm/tpm_i2c_infineon.c (c000000000966700)
Location: drivers/char/tpm/tpm_i2c_infineon.c:312
Inline: True
```
**Symbols:**

```
c000000000962560-c000000000962624: check_locality (STB_LOCAL)
c000000000966700-c000000000966798: check_locality.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffe0005720a0)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffe0005720a0-ffffffe000572114: check_locality (STB_LOCAL)
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
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169b100)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff8169b100-ffffffff8169b180: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81678af0)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff81678af0-ffffffff81678b70: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816c9370)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff816c9370-ffffffff816c93f0: check_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool check_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e3850)
Location: drivers/char/tpm/tpm_tis_core.c:118
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
**Symbols:**

```
ffffffff816e3850-ffffffff816e38d0: check_locality (STB_LOCAL)
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
