# Function: <code>tpm1_get_timeouts</code>

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
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81676f80)
Location: drivers/char/tpm/tpm1-cmd.c:345
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff81676f80-ffffffff81677380: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff816ad6f0-ffffffff816ad883: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff816acc30-ffffffff816acef5: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff816d03d0-ffffffff816d0563: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff816cf910-ffffffff816cfbd5: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff817852c3-ffffffff8178544d: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff81784880-ffffffff81784b85: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff81c0a463-ffffffff81c0a5ed: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff8179bcc0-ffffffff8179bfc5: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff81bfbef6-ffffffff81bfc080: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff8177e7f0-ffffffff8177eaf5: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff81cfcbb0-ffffffff81cfcda4: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff81804a30-ffffffff81804e1b: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff81ec5398-ffffffff81ec55f9: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff81944380-ffffffff81944805: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff82096af6-ffffffff82096b82: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff81aa7060-ffffffff81aa76cd: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff82117a23-ffffffff82117aaf: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff81af28a0-ffffffff81af2efc: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff821f5798-ffffffff821f5824: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff81b45e30-ffffffff81b46487: tpm1_get_timeouts (STB_GLOBAL)
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
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108b9ed0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffff8000108b9ed0-ffff8000108ba2e0: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c09b3290)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
c09b3290-c09b36b4: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c00000000095b020)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
c00000000095b020-c00000000095b4fc: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056a5d6)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffe00056a5d6-ffffffe00056ab36: tpm1_get_timeouts (STB_GLOBAL)
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
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff81695e20-ffffffff81695fb3: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff81695360-ffffffff81695625: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff81673810-ffffffff816739a3: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff81672d50-ffffffff81673015: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff816c4090-ffffffff816c4223: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff816c35d0-ffffffff816c3895: tpm1_get_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm1_get_timeouts(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:342
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup
```
**Symbols:**

```
ffffffff816de630-ffffffff816de7b8: tpm1_get_timeouts.cold (STB_LOCAL)
ffffffff816ddba0-ffffffff816dde65: tpm1_get_timeouts (STB_GLOBAL)
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
