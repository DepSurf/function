# Function: <code>tpm1_pcr_read</code>

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
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816775d0)
Location: drivers/char/tpm/tpm1-cmd.c:575
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff816775d0-ffffffff816776b2: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816ad240)
Location: drivers/char/tpm/tpm1-cmd.c:569
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
ffffffff816ad240-ffffffff816ad38e: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816cff20)
Location: drivers/char/tpm/tpm1-cmd.c:569
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
ffffffff816cff20-ffffffff816d006e: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81784e90)
Location: drivers/char/tpm/tpm1-cmd.c:584
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
ffffffff81784e90-ffffffff81784fa8: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8179c2d0)
Location: drivers/char/tpm/tpm1-cmd.c:584
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
ffffffff8179c2d0-ffffffff8179c3e8: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8177ee00)
Location: drivers/char/tpm/tpm1-cmd.c:584
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
ffffffff8177ee00-ffffffff8177ef18: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81805120)
Location: drivers/char/tpm/tpm1-cmd.c:584
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
ffffffff81805120-ffffffff81805238: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81944b30)
Location: drivers/char/tpm/tpm1-cmd.c:584
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff81944b30-ffffffff81944c67: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81aa7a20)
Location: drivers/char/tpm/tpm1-cmd.c:584
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff81aa7a20-ffffffff81aa7b57: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81af3250)
Location: drivers/char/tpm/tpm1-cmd.c:584
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff81af3250-ffffffff81af3387: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b467e0)
Location: drivers/char/tpm/tpm1-cmd.c:584
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff81b467e0-ffffffff81b46917: tpm1_pcr_read (STB_GLOBAL)
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
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108ba690)
Location: drivers/char/tpm/tpm1-cmd.c:569
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
ffff8000108ba690-ffff8000108ba80c: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c09b3ac0)
Location: drivers/char/tpm/tpm1-cmd.c:569
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
c09b3ac0-c09b3c64: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c00000000095b9e0)
Location: drivers/char/tpm/tpm1-cmd.c:569
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
c00000000095b9e0-c00000000095bbb8: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056b096)
Location: drivers/char/tpm/tpm1-cmd.c:569
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
ffffffe00056b096-ffffffe00056b2b8: tpm1_pcr_read (STB_GLOBAL)
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
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81695970)
Location: drivers/char/tpm/tpm1-cmd.c:569
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
ffffffff81695970-ffffffff81695abe: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81673360)
Location: drivers/char/tpm/tpm1-cmd.c:569
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
ffffffff81673360-ffffffff816734ae: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816c3be0)
Location: drivers/char/tpm/tpm1-cmd.c:569
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
ffffffff816c3be0-ffffffff816c3d2e: tpm1_pcr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip *chip, u32 pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816de1a0)
Location: drivers/char/tpm/tpm1-cmd.c:569
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
**Symbols:**

```
ffffffff816de1a0-ffffffff816de2dd: tpm1_pcr_read (STB_GLOBAL)
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
