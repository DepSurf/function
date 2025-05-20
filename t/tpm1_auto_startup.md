# Function: <code>tpm1_auto_startup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81577990)
Location: drivers/char/tpm/tpm-interface.c:853
Inline: False
```
**Symbols:**

```
ffffffff81577990-ffffffff81577a3b: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a3ee0)
Location: drivers/char/tpm/tpm-interface.c:838
Inline: False
```
**Symbols:**

```
ffffffff815a3ee0-ffffffff815a3f2e: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b8040)
Location: drivers/char/tpm/tpm-interface.c:1002
Inline: False
```
**Symbols:**

```
ffffffff815b8040-ffffffff815b808e: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161eb60)
Location: drivers/char/tpm/tpm-interface.c:1020
Inline: False
```
**Symbols:**

```
ffffffff8161eb60-ffffffff8161ebae: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816588d0)
Location: drivers/char/tpm/tpm-interface.c:1144
Inline: False
```
**Symbols:**

```
ffffffff816588d0-ffffffff8165891e: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81677870)
Location: drivers/char/tpm/tpm1-cmd.c:699
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81677870-ffffffff816778be: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:689
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff816ad8e7-ffffffff816ad901: tpm1_auto_startup.cold (STB_LOCAL)
ffffffff816ad4e0-ffffffff816ad525: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:689
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff816d05c7-ffffffff816d05e1: tpm1_auto_startup.cold (STB_LOCAL)
ffffffff816d01c0-ffffffff816d0205: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:704
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff817854b1-ffffffff817854cb: tpm1_auto_startup.cold (STB_LOCAL)
ffffffff817850e0-ffffffff81785121: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:704
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81c0a651-ffffffff81c0a66b: tpm1_auto_startup.cold (STB_LOCAL)
ffffffff8179c520-ffffffff8179c561: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:704
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81bfc0e4-ffffffff81bfc0fe: tpm1_auto_startup.cold (STB_LOCAL)
ffffffff8177f050-ffffffff8177f091: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:704
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81cfce0d-ffffffff81cfce27: tpm1_auto_startup.cold (STB_LOCAL)
ffffffff81805370-ffffffff818053b1: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:704
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81ec5660-ffffffff81ec567a: tpm1_auto_startup.cold (STB_LOCAL)
ffffffff81944dd0-ffffffff81944e24: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81aa7d40)
Location: drivers/char/tpm/tpm1-cmd.c:704
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81aa7d40-ffffffff81aa7dbc: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81af3570)
Location: drivers/char/tpm/tpm1-cmd.c:704
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81af3570-ffffffff81af35ec: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b46b00)
Location: drivers/char/tpm/tpm1-cmd.c:704
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81b46b00-ffffffff81b46b7c: tpm1_auto_startup (STB_GLOBAL)
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
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108baa18)
Location: drivers/char/tpm/tpm1-cmd.c:689
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffff8000108baa18-ffff8000108baa80: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c09b3e50)
Location: drivers/char/tpm/tpm1-cmd.c:689
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
c09b3e50-c09b3ea8: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c00000000095be30)
Location: drivers/char/tpm/tpm1-cmd.c:689
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
c00000000095be30-c00000000095bec8: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056b47c)
Location: drivers/char/tpm/tpm1-cmd.c:689
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffe00056b47c-ffffffe00056b4dc: tpm1_auto_startup (STB_GLOBAL)
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
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:689
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81696017-ffffffff81696031: tpm1_auto_startup.cold (STB_LOCAL)
ffffffff81695c10-ffffffff81695c55: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:689
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff81673a07-ffffffff81673a21: tpm1_auto_startup.cold (STB_LOCAL)
ffffffff81673600-ffffffff81673645: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:689
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff816c4287-ffffffff816c42a1: tpm1_auto_startup.cold (STB_LOCAL)
ffffffff816c3e80-ffffffff816c3ec5: tpm1_auto_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm1_auto_startup(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: drivers/char/tpm/tpm1-cmd.c:689
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_auto_startup
```
**Symbols:**

```
ffffffff816de81c-ffffffff816de836: tpm1_auto_startup.cold (STB_LOCAL)
ffffffff816de430-ffffffff816de475: tpm1_auto_startup (STB_GLOBAL)
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
