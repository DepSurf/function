# Function: <code>tpm_tis_send_main</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81528bb0)
Location: drivers/char/tpm/tpm_tis.c:380
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send
```
**Symbols:**

```
ffffffff81528bb0-ffffffff81528c74: tpm_tis_send_main.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157c200)
Location: drivers/char/tpm/tpm_tis_core.c:335
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff8157c200-ffffffff8157c314: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a86b0)
Location: drivers/char/tpm/tpm_tis_core.c:357
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff815a86b0-ffffffff815a87c4: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815bdb60)
Location: drivers/char/tpm/tpm_tis_core.c:346
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff815bdb60-ffffffff815bdc61: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816241f0)
Location: drivers/char/tpm/tpm_tis_core.c:349
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff816241f0-ffffffff816242fd: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165e800)
Location: drivers/char/tpm/tpm_tis_core.c:457
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff8165e800-ffffffff8165e90e: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167ccc0)
Location: drivers/char/tpm/tpm_tis_core.c:457
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff8167ccc0-ffffffff8167cdb3: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b39c0)
Location: drivers/char/tpm/tpm_tis_core.c:453
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff816b39c0-ffffffff816b3aaf: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d66a0)
Location: drivers/char/tpm/tpm_tis_core.c:453
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff816d66a0-ffffffff816d678f: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178b0b0)
Location: drivers/char/tpm/tpm_tis_core.c:456
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff8178b0b0-ffffffff8178b19f: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a1ac0)
Location: drivers/char/tpm/tpm_tis_core.c:423
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff817a1ac0-ffffffff817a1baf: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817847c0)
Location: drivers/char/tpm/tpm_tis_core.c:434
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff817847c0-ffffffff817848af: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180b210)
Location: drivers/char/tpm/tpm_tis_core.c:435
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff8180b210-ffffffff8180b2ff: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194b610)
Location: drivers/char/tpm/tpm_tis_core.c:435
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff8194b610-ffffffff8194b715: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aaf130)
Location: drivers/char/tpm/tpm_tis_core.c:443
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff81aaf130-ffffffff81aaf279: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81afa730)
Location: drivers/char/tpm/tpm_tis_core.c:509
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff81afa730-ffffffff81afa885: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4ddd0)
Location: drivers/char/tpm/tpm_tis_core.c:536
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff81b4ddd0-ffffffff81b4df13: tpm_tis_send_main (STB_LOCAL)
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
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c2188)
Location: drivers/char/tpm/tpm_tis_core.c:453
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffff8000108c2188-ffff8000108c22ac: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c09ba058)
Location: drivers/char/tpm/tpm_tis_core.c:453
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
c09ba058-c09ba170: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c000000000963d00)
Location: drivers/char/tpm/tpm_tis_core.c:453
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
c000000000963d00-c000000000963e60: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffe000572d34)
Location: drivers/char/tpm/tpm_tis_core.c:453
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffe000572d34-ffffffe000572e2e: tpm_tis_send_main (STB_LOCAL)
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
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169c0f0)
Location: drivers/char/tpm/tpm_tis_core.c:453
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff8169c0f0-ffffffff8169c1df: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81679ae0)
Location: drivers/char/tpm/tpm_tis_core.c:453
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff81679ae0-ffffffff81679bcf: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816ca360)
Location: drivers/char/tpm/tpm_tis_core.c:453
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff816ca360-ffffffff816ca44f: tpm_tis_send_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip *chip, const u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e4830)
Location: drivers/char/tpm/tpm_tis_core.c:453
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff816e4830-ffffffff816e491f: tpm_tis_send_main (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 *buf</code> ➡️ <code>const u8 *buf</code>
</li>
</ul>
</details>
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
