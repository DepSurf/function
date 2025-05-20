# Function: <code>tpm2_commit_space</code>

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
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, u32 cc, u8 *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff815bc6a0)
Location: drivers/char/tpm/tpm2-space.c:491
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff815bc6a0-ffffffff815bcb14: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, u32 cc, u8 *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81622b40)
Location: drivers/char/tpm/tpm2-space.c:491
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff81622b40-ffffffff81622fb4: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, u32 cc, u8 *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff8165c930)
Location: drivers/char/tpm/tpm2-space.c:496
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff8165c930-ffffffff8165cd99: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, u32 cc, u8 *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81679ca0)
Location: drivers/char/tpm/tpm2-space.c:492
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff81679ca0-ffffffff8167a109: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:527
Inline: False
```
**Symbols:**

```
ffffffff816b0952-ffffffff816b0970: tpm2_commit_space.cold (STB_LOCAL)
ffffffff816b03c0-ffffffff816b0834: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:527
Inline: False
```
**Symbols:**

```
ffffffff816d3652-ffffffff816d3670: tpm2_commit_space.cold (STB_LOCAL)
ffffffff816d30c0-ffffffff816d3534: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81787530)
Location: drivers/char/tpm/tpm2-space.c:531
Inline: False
```
**Symbols:**

```
ffffffff81787530-ffffffff81787704: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff8179e640)
Location: drivers/char/tpm/tpm2-space.c:531
Inline: False
```
**Symbols:**

```
ffffffff8179e640-ffffffff8179e814: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:531
Inline: False
```
**Symbols:**

```
ffffffff81bfc322-ffffffff81bfc340: tpm2_commit_space.cold (STB_LOCAL)
ffffffff81780ec0-ffffffff817812ff: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:534
Inline: False
```
**Symbols:**

```
ffffffff81cfd026-ffffffff81cfd044: tpm2_commit_space.cold (STB_LOCAL)
ffffffff81807470-ffffffff81807a0d: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:534
Inline: False
```
**Symbols:**

```
ffffffff81ec58a4-ffffffff81ec58c2: tpm2_commit_space.cold (STB_LOCAL)
ffffffff81947090-ffffffff81947656: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81aaa3e0)
Location: drivers/char/tpm/tpm2-space.c:534
Inline: False
```
**Symbols:**

```
ffffffff81aaa3e0-ffffffff81aaa9b1: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81af5c00)
Location: drivers/char/tpm/tpm2-space.c:534
Inline: False
```
**Symbols:**

```
ffffffff81af5c00-ffffffff81af61d1: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81b491f0)
Location: drivers/char/tpm/tpm2-space.c:534
Inline: False
```
**Symbols:**

```
ffffffff81b491f0-ffffffff81b497c1: tpm2_commit_space (STB_GLOBAL)
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
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffff8000108bdd48)
Location: drivers/char/tpm/tpm2-space.c:527
Inline: False
```
**Symbols:**

```
ffff8000108bdd48-ffff8000108be184: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (c09b7144)
Location: drivers/char/tpm/tpm2-space.c:527
Inline: False
```
**Symbols:**

```
c09b7144-c09b7578: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (c00000000095fdc0)
Location: drivers/char/tpm/tpm2-space.c:527
Inline: False
```
**Symbols:**

```
c00000000095fdc0-c000000000960374: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffe000570234)
Location: drivers/char/tpm/tpm2-space.c:527
Inline: False
```
**Symbols:**

```
ffffffe000570234-ffffffe0005708a4: tpm2_commit_space (STB_GLOBAL)
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
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:527
Inline: False
```
**Symbols:**

```
ffffffff816990a2-ffffffff816990c0: tpm2_commit_space.cold (STB_LOCAL)
ffffffff81698b10-ffffffff81698f84: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:527
Inline: False
```
**Symbols:**

```
ffffffff81676a92-ffffffff81676ab0: tpm2_commit_space.cold (STB_LOCAL)
ffffffff81676500-ffffffff81676974: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:527
Inline: False
```
**Symbols:**

```
ffffffff816c7312-ffffffff816c7330: tpm2_commit_space.cold (STB_LOCAL)
ffffffff816c6d80-ffffffff816c71f4: tpm2_commit_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm2_commit_space(struct tpm_chip *chip, struct tpm_space *space, void *buf, size_t *bufsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:527
Inline: False
```
**Symbols:**

```
ffffffff816e1802-ffffffff816e1820: tpm2_commit_space.cold (STB_LOCAL)
ffffffff816e1270-ffffffff816e16e4: tpm2_commit_space (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 cc</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, space, cc, buf, bufsiz</code> ➡️ <code>chip, space, buf, bufsiz</code>
</li>
<li>
<b>Param type changed. </b>
<code>u8 *buf</code> ➡️ <code>void *buf</code>
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
