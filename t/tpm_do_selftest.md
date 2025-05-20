# Function: <code>tpm_do_selftest</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81523e10)
Location: drivers/char/tpm/tpm-interface.c:790
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_resume
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
```
**Symbols:**

```
ffffffff81523e10-ffffffff81523f57: tpm_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81576d40)
Location: drivers/char/tpm/tpm-interface.c:789
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff81576d40-ffffffff81576e95: tpm_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a3de0)
Location: drivers/char/tpm/tpm-interface.c:779
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff815a3de0-ffffffff815a3ed8: tpm_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b7f40)
Location: drivers/char/tpm/tpm-interface.c:943
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff815b7f40-ffffffff815b8038: tpm_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161ea50)
Location: drivers/char/tpm/tpm-interface.c:961
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff8161ea50-ffffffff8161eb52: tpm_do_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm_do_selftest(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816587a0)
Location: drivers/char/tpm/tpm-interface.c:1081
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_auto_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff816587a0-ffffffff816588cd: tpm_do_selftest (STB_GLOBAL)
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
