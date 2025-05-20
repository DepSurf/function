# Function: <code>tpm1_pm_suspend</code>

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
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816778c0)
Location: drivers/char/tpm/tpm1-cmd.c:732
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff816778c0-ffffffff81677a23: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:722
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff816ad901-ffffffff816ad918: tpm1_pm_suspend.cold (STB_LOCAL)
ffffffff816ad530-ffffffff816ad681: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:722
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff816d05e1-ffffffff816d05f8: tpm1_pm_suspend.cold (STB_LOCAL)
ffffffff816d0210-ffffffff816d0361: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:737
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff817854cb-ffffffff817854e2: tpm1_pm_suspend.cold (STB_LOCAL)
ffffffff81785130-ffffffff8178525c: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:737
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81c0a66b-ffffffff81c0a682: tpm1_pm_suspend.cold (STB_LOCAL)
ffffffff8179c570-ffffffff8179c69c: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:737
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81bfc0fe-ffffffff81bfc115: tpm1_pm_suspend.cold (STB_LOCAL)
ffffffff8177f0a0-ffffffff8177f1cc: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:737
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81cfce27-ffffffff81cfce3e: tpm1_pm_suspend.cold (STB_LOCAL)
ffffffff818053c0-ffffffff818054f1: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:737
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81ec567a-ffffffff81ec5691: tpm1_pm_suspend.cold (STB_LOCAL)
ffffffff81944e30-ffffffff81944f7d: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81aa7dd0)
Location: drivers/char/tpm/tpm1-cmd.c:742
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81aa7dd0-ffffffff81aa7f2d: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81af3600)
Location: drivers/char/tpm/tpm1-cmd.c:742
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81af3600-ffffffff81af375d: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b46b90)
Location: drivers/char/tpm/tpm1-cmd.c:742
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81b46b90-ffffffff81b46ced: tpm1_pm_suspend (STB_GLOBAL)
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
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108baa80)
Location: drivers/char/tpm/tpm1-cmd.c:722
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffff8000108baa80-ffff8000108bac28: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c09b3ea8)
Location: drivers/char/tpm/tpm1-cmd.c:722
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
c09b3ea8-c09b4088: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c00000000095bed0)
Location: drivers/char/tpm/tpm1-cmd.c:722
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
c00000000095bed0-c00000000095c0f4: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056b4dc)
Location: drivers/char/tpm/tpm1-cmd.c:722
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffe00056b4dc-ffffffe00056b682: tpm1_pm_suspend (STB_GLOBAL)
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
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:722
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81696031-ffffffff81696048: tpm1_pm_suspend.cold (STB_LOCAL)
ffffffff81695c60-ffffffff81695db1: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:722
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81673a21-ffffffff81673a38: tpm1_pm_suspend.cold (STB_LOCAL)
ffffffff81673650-ffffffff816737a1: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:722
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff816c42a1-ffffffff816c42b8: tpm1_pm_suspend.cold (STB_LOCAL)
ffffffff816c3ed0-ffffffff816c4021: tpm1_pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm1_pm_suspend(struct tpm_chip *chip, u32 tpm_suspend_pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:722
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff816de836-ffffffff816de84d: tpm1_pm_suspend.cold (STB_LOCAL)
ffffffff816de480-ffffffff816de5c6: tpm1_pm_suspend (STB_GLOBAL)
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
