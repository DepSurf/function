# Function: <code>tpm_pcr_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm_pcr_read(u32 chip_num, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815249b0)
Location: drivers/char/tpm/tpm-interface.c:720
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_init
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff815249b0-ffffffff81524a19: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_pcr_read(u32 chip_num, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81577930)
Location: drivers/char/tpm/tpm-interface.c:719
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_init
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff81577930-ffffffff8157798f: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_pcr_read(u32 chip_num, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a3d80)
Location: drivers/char/tpm/tpm-interface.c:709
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_init
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff815a3d80-ffffffff815a3ddf: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_pcr_read(u32 chip_num, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b7ee0)
Location: drivers/char/tpm/tpm-interface.c:846
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_init
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff815b7ee0-ffffffff815b7f3f: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_pcr_read(u32 chip_num, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161e9f0)
Location: drivers/char/tpm/tpm-interface.c:864
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_init
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff8161e9f0-ffffffff8161ea4f: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81658740)
Location: drivers/char/tpm/tpm-interface.c:984
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_init
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff81658740-ffffffff8165879f: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816761f0)
Location: drivers/char/tpm/tpm-interface.c:467
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
ffffffff816761f0-ffffffff8167624f: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816ac000)
Location: drivers/char/tpm/tpm-interface.c:283
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
ffffffff816ac000-ffffffff816ac06d: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816ced80)
Location: drivers/char/tpm/tpm-interface.c:283
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
ffffffff816ced80-ffffffff816ceded: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81783c80)
Location: drivers/char/tpm/tpm-interface.c:284
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
ffffffff81783c80-ffffffff81783ced: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8179b1d0)
Location: drivers/char/tpm/tpm-interface.c:284
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
ffffffff8179b1d0-ffffffff8179b23d: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8177dd10)
Location: drivers/char/tpm/tpm-interface.c:284
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - drivers/char/tpm/tpm-sysfs.c:pcr_value_show
```
**Symbols:**

```
ffffffff8177dd10-ffffffff8177dd7d: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81803f00)
Location: drivers/char/tpm/tpm-interface.c:284
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - drivers/char/tpm/tpm-sysfs.c:pcr_value_show
```
**Symbols:**

```
ffffffff81803f00-ffffffff81803f6d: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81943810)
Location: drivers/char/tpm/tpm-interface.c:284
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - drivers/char/tpm/tpm-sysfs.c:pcr_value_show
```
**Symbols:**

```
ffffffff81943810-ffffffff81943888: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81aa62f0)
Location: drivers/char/tpm/tpm-interface.c:284
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - drivers/char/tpm/tpm-sysfs.c:pcr_value_show
```
**Symbols:**

```
ffffffff81aa62f0-ffffffff81aa6368: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81af1b10)
Location: drivers/char/tpm/tpm-interface.c:284
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - drivers/char/tpm/tpm-sysfs.c:pcr_value_show
```
**Symbols:**

```
ffffffff81af1b10-ffffffff81af1b88: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81b450a0)
Location: drivers/char/tpm/tpm-interface.c:284
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - drivers/char/tpm/tpm-sysfs.c:pcr_value_show
```
**Symbols:**

```
ffffffff81b450a0-ffffffff81b45118: tpm_pcr_read (STB_GLOBAL)
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
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffff8000108b9330)
Location: drivers/char/tpm/tpm-interface.c:283
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
ffff8000108b9330-ffff8000108b93b8: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c09b27b0)
Location: drivers/char/tpm/tpm-interface.c:283
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
c09b27b0-c09b2824: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c00000000095a0f0)
Location: drivers/char/tpm/tpm-interface.c:283
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
c00000000095a0f0-c00000000095a1a4: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffe000569766)
Location: drivers/char/tpm/tpm-interface.c:283
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
ffffffe000569766-ffffffe0005697da: tpm_pcr_read (STB_GLOBAL)
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
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816947d0)
Location: drivers/char/tpm/tpm-interface.c:283
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
ffffffff816947d0-ffffffff8169483d: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816721c0)
Location: drivers/char/tpm/tpm-interface.c:283
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
ffffffff816721c0-ffffffff8167222d: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816c2a40)
Location: drivers/char/tpm/tpm-interface.c:283
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
ffffffff816c2a40-ffffffff816c2aad: tpm_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816dd010)
Location: drivers/char/tpm/tpm-interface.c:283
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
```
**Symbols:**

```
ffffffff816dd010-ffffffff816dd07d: tpm_pcr_read (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_chip *chip</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 chip_num</code>
</li>
</ul>
</details>
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
