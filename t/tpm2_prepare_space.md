# Function: <code>tpm2_prepare_space</code>

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
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u32 cc, u8 *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff815bc410)
Location: drivers/char/tpm/tpm2-space.c:266
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff815bc410-ffffffff815bc691: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u32 cc, u8 *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff816228b0)
Location: drivers/char/tpm/tpm2-space.c:266
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff816228b0-ffffffff81622b31: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u32 cc, u8 *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff8165c6b0)
Location: drivers/char/tpm/tpm2-space.c:269
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff8165c6b0-ffffffff8165c922: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u32 cc, u8 *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81679a20)
Location: drivers/char/tpm/tpm2-space.c:267
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff81679a20-ffffffff81679c92: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:297
Inline: False
```
**Symbols:**

```
ffffffff816b0918-ffffffff816b0952: tpm2_prepare_space.cold (STB_LOCAL)
ffffffff816b0090-ffffffff816b03be: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:297
Inline: False
```
**Symbols:**

```
ffffffff816d3618-ffffffff816d3652: tpm2_prepare_space.cold (STB_LOCAL)
ffffffff816d2d90-ffffffff816d30be: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81787320)
Location: drivers/char/tpm/tpm2-space.c:300
Inline: False
```
**Symbols:**

```
ffffffff81787320-ffffffff81787523: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff8179e430)
Location: drivers/char/tpm/tpm2-space.c:300
Inline: False
```
**Symbols:**

```
ffffffff8179e430-ffffffff8179e633: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:300
Inline: False
```
**Symbols:**

```
ffffffff81bfc2e8-ffffffff81bfc322: tpm2_prepare_space.cold (STB_LOCAL)
ffffffff81780bd0-ffffffff81780ec0: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:300
Inline: False
```
**Symbols:**

```
ffffffff81cfcfec-ffffffff81cfd026: tpm2_prepare_space.cold (STB_LOCAL)
ffffffff81807080-ffffffff8180746a: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:300
Inline: False
```
**Symbols:**

```
ffffffff81ec586a-ffffffff81ec58a4: tpm2_prepare_space.cold (STB_LOCAL)
ffffffff81946c90-ffffffff81947084: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81aa9fa0)
Location: drivers/char/tpm/tpm2-space.c:300
Inline: False
```
**Symbols:**

```
ffffffff81aa9fa0-ffffffff81aaa3c8: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81af57c0)
Location: drivers/char/tpm/tpm2-space.c:300
Inline: False
```
**Symbols:**

```
ffffffff81af57c0-ffffffff81af5be5: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81b48db0)
Location: drivers/char/tpm/tpm2-space.c:300
Inline: False
```
**Symbols:**

```
ffffffff81b48db0-ffffffff81b491d5: tpm2_prepare_space (STB_GLOBAL)
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
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffff8000108bda00)
Location: drivers/char/tpm/tpm2-space.c:297
Inline: False
```
**Symbols:**

```
ffff8000108bda00-ffff8000108bdd44: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (c09b6e3c)
Location: drivers/char/tpm/tpm2-space.c:297
Inline: False
```
**Symbols:**

```
c09b6e3c-c09b7144: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (c00000000095f9b0)
Location: drivers/char/tpm/tpm2-space.c:297
Inline: False
```
**Symbols:**

```
c00000000095f9b0-c00000000095fdbc: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffe00056fe5a)
Location: drivers/char/tpm/tpm2-space.c:297
Inline: False
```
**Symbols:**

```
ffffffe00056fe5a-ffffffe000570234: tpm2_prepare_space (STB_GLOBAL)
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
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:297
Inline: False
```
**Symbols:**

```
ffffffff81699068-ffffffff816990a2: tpm2_prepare_space.cold (STB_LOCAL)
ffffffff816987e0-ffffffff81698b0e: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:297
Inline: False
```
**Symbols:**

```
ffffffff81676a58-ffffffff81676a92: tpm2_prepare_space.cold (STB_LOCAL)
ffffffff816761d0-ffffffff816764fe: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:297
Inline: False
```
**Symbols:**

```
ffffffff816c72d8-ffffffff816c7312: tpm2_prepare_space.cold (STB_LOCAL)
ffffffff816c6a50-ffffffff816c6d7e: tpm2_prepare_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm2_prepare_space(struct tpm_chip *chip, struct tpm_space *space, u8 *cmd, size_t cmdsiz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:297
Inline: False
```
**Symbols:**

```
ffffffff816e17c8-ffffffff816e1802: tpm2_prepare_space.cold (STB_LOCAL)
ffffffff816e0f40-ffffffff816e126e: tpm2_prepare_space (STB_GLOBAL)
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
<b>Param added. </b>
<code>size_t cmdsiz</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 cc</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, space, cc, cmd</code> ➡️ <code>chip, space, cmd, cmdsiz</code>
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
