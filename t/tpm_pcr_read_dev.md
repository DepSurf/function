# Function: <code>tpm_pcr_read_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm_pcr_read_dev(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81524910)
Location: drivers/char/tpm/tpm-interface.c:669
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff81524910-ffffffff815249af: tpm_pcr_read_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_pcr_read_dev(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81577890)
Location: drivers/char/tpm/tpm-interface.c:668
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff81577890-ffffffff8157792f: tpm_pcr_read_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_pcr_read_dev(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a3cd0)
Location: drivers/char/tpm/tpm-interface.c:658
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff815a3cd0-ffffffff815a3d75: tpm_pcr_read_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_pcr_read_dev(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b7e30)
Location: drivers/char/tpm/tpm-interface.c:794
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff815b7e30-ffffffff815b7ed6: tpm_pcr_read_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_pcr_read_dev(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161e940)
Location: drivers/char/tpm/tpm-interface.c:812
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff8161e940-ffffffff8161e9e6: tpm_pcr_read_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm_pcr_read_dev(struct tpm_chip *chip, int pcr_idx, u8 *res_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81658690)
Location: drivers/char/tpm/tpm-interface.c:934
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff81658690-ffffffff81658736: tpm_pcr_read_dev (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
