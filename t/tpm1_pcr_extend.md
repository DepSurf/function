# Function: <code>tpm1_pcr_extend</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, int pcr_idx, const u8 *hash, char *log_msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b71d0)
Location: drivers/char/tpm/tpm-interface.c:872
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff815b71d0-ffffffff815b733a: tpm1_pcr_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, int pcr_idx, const u8 *hash, char *log_msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161de40)
Location: drivers/char/tpm/tpm-interface.c:890
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff8161de40-ffffffff8161df13: tpm1_pcr_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, int pcr_idx, const u8 *hash, char *log_msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81657b50)
Location: drivers/char/tpm/tpm-interface.c:1009
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff81657b50-ffffffff81657c23: tpm1_pcr_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81677380)
Location: drivers/char/tpm/tpm1-cmd.c:452
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff81677380-ffffffff81677453: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816acf00)
Location: drivers/char/tpm/tpm1-cmd.c:448
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff816acf00-ffffffff816ad055: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816cfbe0)
Location: drivers/char/tpm/tpm1-cmd.c:448
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff816cfbe0-ffffffff816cfd35: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81784b90)
Location: drivers/char/tpm/tpm1-cmd.c:463
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff81784b90-ffffffff81784cb9: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8179bfd0)
Location: drivers/char/tpm/tpm1-cmd.c:463
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff8179bfd0-ffffffff8179c0f9: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8177eb00)
Location: drivers/char/tpm/tpm1-cmd.c:463
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff8177eb00-ffffffff8177ec29: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81804e20)
Location: drivers/char/tpm/tpm1-cmd.c:463
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff81804e20-ffffffff81804f49: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81944810)
Location: drivers/char/tpm/tpm1-cmd.c:463
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff81944810-ffffffff81944952: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81aa76e0)
Location: drivers/char/tpm/tpm1-cmd.c:463
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff81aa76e0-ffffffff81aa7822: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81af2f10)
Location: drivers/char/tpm/tpm1-cmd.c:463
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff81af2f10-ffffffff81af3052: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b464a0)
Location: drivers/char/tpm/tpm1-cmd.c:463
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff81b464a0-ffffffff81b465e2: tpm1_pcr_extend (STB_GLOBAL)
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
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108ba2e0)
Location: drivers/char/tpm/tpm1-cmd.c:448
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffff8000108ba2e0-ffff8000108ba46c: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c09b36b4)
Location: drivers/char/tpm/tpm1-cmd.c:448
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
c09b36b4-c09b386c: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c00000000095b500)
Location: drivers/char/tpm/tpm1-cmd.c:448
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
c00000000095b500-c00000000095b6f4: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056ab36)
Location: drivers/char/tpm/tpm1-cmd.c:448
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffe00056ab36-ffffffe00056ad84: tpm1_pcr_extend (STB_GLOBAL)
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
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81695630)
Location: drivers/char/tpm/tpm1-cmd.c:448
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff81695630-ffffffff81695785: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81673020)
Location: drivers/char/tpm/tpm1-cmd.c:448
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff81673020-ffffffff81673175: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816c38a0)
Location: drivers/char/tpm/tpm1-cmd.c:448
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff816c38a0-ffffffff816c39f5: tpm1_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash, const char *log_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816dde70)
Location: drivers/char/tpm/tpm1-cmd.c:448
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
```
**Symbols:**

```
ffffffff816dde70-ffffffff816ddfb3: tpm1_pcr_extend (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pcr_idx</code> ➡️ <code>u32 pcr_idx</code>
</li>
<li>
<b>Param type changed. </b>
<code>char *log_msg</code> ➡️ <code>const char *log_msg</code>
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
