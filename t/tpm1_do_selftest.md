# Function: <code>tpm1_do_selftest</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816776c0)
Location: drivers/char/tpm/tpm1-cmd.c:637
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff816776c0-ffffffff8167786b: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff816ad883-ffffffff816ad8e7: tpm1_do_selftest.cold (STB_LOCAL)
ffffffff816ad390-ffffffff816ad4dd: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff816d0563-ffffffff816d05c7: tpm1_do_selftest.cold (STB_LOCAL)
ffffffff816d0070-ffffffff816d01bd: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:642
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff8178544d-ffffffff817854b1: tpm1_do_selftest.cold (STB_LOCAL)
ffffffff81784fb0-ffffffff817850d8: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:642
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff81c0a5ed-ffffffff81c0a651: tpm1_do_selftest.cold (STB_LOCAL)
ffffffff8179c3f0-ffffffff8179c518: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:642
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff81bfc080-ffffffff81bfc0e4: tpm1_do_selftest.cold (STB_LOCAL)
ffffffff8177ef20-ffffffff8177f048: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:642
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff81cfcda4-ffffffff81cfce0d: tpm1_do_selftest.cold (STB_LOCAL)
ffffffff81805240-ffffffff8180536d: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:642
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff81ec55f9-ffffffff81ec5660: tpm1_do_selftest.cold (STB_LOCAL)
ffffffff81944c70-ffffffff81944dd0: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81aa7b70)
Location: drivers/char/tpm/tpm1-cmd.c:642
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff81aa7b70-ffffffff81aa7d2b: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81af33a0)
Location: drivers/char/tpm/tpm1-cmd.c:642
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff81af33a0-ffffffff81af355b: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b46930)
Location: drivers/char/tpm/tpm1-cmd.c:642
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff81b46930-ffffffff81b46aeb: tpm1_do_selftest (STB_GLOBAL)
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
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108ba810)
Location: drivers/char/tpm/tpm1-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffff8000108ba810-ffff8000108baa14: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c09b3c64)
Location: drivers/char/tpm/tpm1-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
c09b3c64-c09b3e50: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c00000000095bbc0)
Location: drivers/char/tpm/tpm1-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
c00000000095bbc0-c00000000095be2c: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056b2b8)
Location: drivers/char/tpm/tpm1-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffe00056b2b8-ffffffe00056b47c: tpm1_do_selftest (STB_GLOBAL)
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
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff81695fb3-ffffffff81696017: tpm1_do_selftest.cold (STB_LOCAL)
ffffffff81695ac0-ffffffff81695c0d: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff816739a3-ffffffff81673a07: tpm1_do_selftest.cold (STB_LOCAL)
ffffffff816734b0-ffffffff816735fd: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff816c4223-ffffffff816c4287: tpm1_do_selftest.cold (STB_LOCAL)
ffffffff816c3d30-ffffffff816c3e7d: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm1_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff816de7b8-ffffffff816de81c: tpm1_do_selftest.cold (STB_LOCAL)
ffffffff816de2e0-ffffffff816de422: tpm1_do_selftest (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
