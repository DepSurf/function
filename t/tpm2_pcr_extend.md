# Function: <code>tpm2_pcr_extend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, int pcr_idx, const u8 *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815262a0)
Location: drivers/char/tpm/tpm2-cmd.c:315
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff815262a0-ffffffff81526360: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, int pcr_idx, const u8 *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81579340)
Location: drivers/char/tpm/tpm2-cmd.c:315
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff81579340-ffffffff81579400: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, int pcr_idx, const u8 *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a5860)
Location: drivers/char/tpm/tpm2-cmd.c:315
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff815a5860-ffffffff815a5922: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, int pcr_idx, u32 count, struct tpm2_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815b9930)
Location: drivers/char/tpm/tpm2-cmd.c:279
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff815b9930-ffffffff815b9c2e: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, int pcr_idx, u32 count, struct tpm2_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816202b0)
Location: drivers/char/tpm/tpm2-cmd.c:279
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff816202b0-ffffffff8162047b: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, int pcr_idx, u32 count, struct tpm2_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165a060)
Location: drivers/char/tpm/tpm2-cmd.c:276
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff8165a060-ffffffff8165a250: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, u32 count, struct tpm2_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81677fe0)
Location: drivers/char/tpm/tpm2-cmd.c:228
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff81677fe0-ffffffff816781d0: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816ae340)
Location: drivers/char/tpm/tpm2-cmd.c:249
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff816ae340-ffffffff816ae5c5: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d1030)
Location: drivers/char/tpm/tpm2-cmd.c:249
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff816d1030-ffffffff816d12b5: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81786000)
Location: drivers/char/tpm/tpm2-cmd.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff81786000-ffffffff81786260: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8179d200)
Location: drivers/char/tpm/tpm2-cmd.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff8179d200-ffffffff8179d460: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8177fce0)
Location: drivers/char/tpm/tpm2-cmd.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff8177fce0-ffffffff8177ff40: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff818060b0)
Location: drivers/char/tpm/tpm2-cmd.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff818060b0-ffffffff81806310: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81945ba0)
Location: drivers/char/tpm/tpm2-cmd.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff81945ba0-ffffffff81945e15: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa8c10)
Location: drivers/char/tpm/tpm2-cmd.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff81aa8c10-ffffffff81aa8e85: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af4440)
Location: drivers/char/tpm/tpm2-cmd.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff81af4440-ffffffff81af46b5: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b47a00)
Location: drivers/char/tpm/tpm2-cmd.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff81b47a00-ffffffff81b47c75: tpm2_pcr_extend (STB_GLOBAL)
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
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bb880)
Location: drivers/char/tpm/tpm2-cmd.c:249
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffff8000108bb880-ffff8000108bbbac: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c09b4bc4)
Location: drivers/char/tpm/tpm2-cmd.c:249
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
c09b4bc4-c09b4f04: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c00000000095d040)
Location: drivers/char/tpm/tpm2-cmd.c:249
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
c00000000095d040-c00000000095d3d0: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056ca48)
Location: drivers/char/tpm/tpm2-cmd.c:249
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffe00056ca48-ffffffe00056d020: tpm2_pcr_extend (STB_GLOBAL)
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
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81696a80)
Location: drivers/char/tpm/tpm2-cmd.c:249
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff81696a80-ffffffff81696d05: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81674470)
Location: drivers/char/tpm/tpm2-cmd.c:249
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff81674470-ffffffff816746f5: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c4cf0)
Location: drivers/char/tpm/tpm2-cmd.c:249
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff816c4cf0-ffffffff816c4f75: tpm2_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm2_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816df250)
Location: drivers/char/tpm/tpm2-cmd.c:249
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
```
**Symbols:**

```
ffffffff816df250-ffffffff816df4ca: tpm2_pcr_extend (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 count</code>
</li>
<li>
<b>Param added. </b>
<code>struct tpm2_digest *digests</code>
</li>
<li>
<b>Param removed. </b>
<code>const u8 *hash</code>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pcr_idx</code> ➡️ <code>u32 pcr_idx</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 count</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, pcr_idx, count, digests</code> ➡️ <code>chip, pcr_idx, digests</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct tpm2_digest *digests</code> ➡️ <code>struct tpm_digest *digests</code>
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
