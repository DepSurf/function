# Function: <code>tpm2_pcr_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815261b0)
Location: drivers/char/tpm/tpm2-cmd.c:267
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
```
**Symbols:**

```
ffffffff815261b0-ffffffff8152629b: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81579250)
Location: drivers/char/tpm/tpm2-cmd.c:267
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
```
**Symbols:**

```
ffffffff81579250-ffffffff8157933b: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a5770)
Location: drivers/char/tpm/tpm2-cmd.c:267
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
```
**Symbols:**

```
ffffffff815a5770-ffffffff815a585d: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815b9640)
Location: drivers/char/tpm/tpm2-cmd.c:229
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
```
**Symbols:**

```
ffffffff815b9640-ffffffff815b9893: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81620140)
Location: drivers/char/tpm/tpm2-cmd.c:229
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
```
**Symbols:**

```
ffffffff81620140-ffffffff816202a1: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81659ef0)
Location: drivers/char/tpm/tpm2-cmd.c:226
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
```
**Symbols:**

```
ffffffff81659ef0-ffffffff8165a051: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81677e80)
Location: drivers/char/tpm/tpm2-cmd.c:178
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
```
**Symbols:**

```
ffffffff81677e80-ffffffff81677fdf: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816adf60)
Location: drivers/char/tpm/tpm2-cmd.c:175
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_init_bank_info
```
**Symbols:**

```
ffffffff816adf60-ffffffff816ae278: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d0c40)
Location: drivers/char/tpm/tpm2-cmd.c:175
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_init_bank_info
```
**Symbols:**

```
ffffffff816d0c40-ffffffff816d0f57: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81785d00)
Location: drivers/char/tpm/tpm2-cmd.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff81785d00-ffffffff81785ff4: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8179cf00)
Location: drivers/char/tpm/tpm2-cmd.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff8179cf00-ffffffff8179d1f4: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8177f9e0)
Location: drivers/char/tpm/tpm2-cmd.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff8177f9e0-ffffffff8177fcd4: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81805d90)
Location: drivers/char/tpm/tpm2-cmd.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff81805d90-ffffffff818060aa: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81945860)
Location: drivers/char/tpm/tpm2-cmd.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff81945860-ffffffff81945b9e: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa88c0)
Location: drivers/char/tpm/tpm2-cmd.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff81aa88c0-ffffffff81aa8bfc: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af40f0)
Location: drivers/char/tpm/tpm2-cmd.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff81af40f0-ffffffff81af442e: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b476b0)
Location: drivers/char/tpm/tpm2-cmd.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff81b476b0-ffffffff81b479ee: tpm2_pcr_read (STB_GLOBAL)
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
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bb480)
Location: drivers/char/tpm/tpm2-cmd.c:175
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_init_bank_info
```
**Symbols:**

```
ffff8000108bb480-ffff8000108bb774: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c09b48dc)
Location: drivers/char/tpm/tpm2-cmd.c:175
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
c09b48dc-c09b4bc4: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c00000000095cb20)
Location: drivers/char/tpm/tpm2-cmd.c:175
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_init_bank_info
```
**Symbols:**

```
c00000000095cb20-c00000000095cf1c: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056c4fc)
Location: drivers/char/tpm/tpm2-cmd.c:175
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_init_bank_info
```
**Symbols:**

```
ffffffe00056c4fc-ffffffe00056c968: tpm2_pcr_read (STB_GLOBAL)
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
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81696690)
Location: drivers/char/tpm/tpm2-cmd.c:175
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_init_bank_info
```
**Symbols:**

```
ffffffff81696690-ffffffff816969a7: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81674080)
Location: drivers/char/tpm/tpm2-cmd.c:175
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_init_bank_info
```
**Symbols:**

```
ffffffff81674080-ffffffff81674397: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c4900)
Location: drivers/char/tpm/tpm2-cmd.c:175
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_init_bank_info
```
**Symbols:**

```
ffffffff816c4900-ffffffff816c4c17: tpm2_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm2_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest, u16 *digest_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816dee70)
Location: drivers/char/tpm/tpm2-cmd.c:175
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_init_bank_info
```
**Symbols:**

```
ffffffff816dee70-ffffffff816df172: tpm2_pcr_read (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
<b>Param added. </b>
<code>struct tpm_digest *digest</code>
</li>
<li>
<b>Param added. </b>
<code>u16 *digest_size_ptr</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 *res_buf</code>
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
