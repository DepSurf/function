# Function: <code>tpm_common_write</code>

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
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff815bb380)
Location: drivers/char/tpm/tpm-dev-common.c:88
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_write
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_write
```
**Symbols:**

```
ffffffff815bb380-ffffffff815bb4a3: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816218b0)
Location: drivers/char/tpm/tpm-dev-common.c:87
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_write
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_write
```
**Symbols:**

```
ffffffff816218b0-ffffffff816219f7: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8165b620)
Location: drivers/char/tpm/tpm-dev-common.c:81
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_write
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_write
```
**Symbols:**

```
ffffffff8165b620-ffffffff8165b76f: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81675db0)
Location: drivers/char/tpm/tpm-dev-common.c:128
Inline: False
```
**Symbols:**

```
ffffffff81675db0-ffffffff81675f69: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816abbb0)
Location: drivers/char/tpm/tpm-dev-common.c:153
Inline: False
```
**Symbols:**

```
ffffffff816abbb0-ffffffff816abd6e: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816ce920)
Location: drivers/char/tpm/tpm-dev-common.c:160
Inline: False
```
**Symbols:**

```
ffffffff816ce920-ffffffff816ceae7: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81783830)
Location: drivers/char/tpm/tpm-dev-common.c:160
Inline: False
```
**Symbols:**

```
ffffffff81783830-ffffffff817839ed: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8179adc0)
Location: drivers/char/tpm/tpm-dev-common.c:160
Inline: False
```
**Symbols:**

```
ffffffff8179adc0-ffffffff8179af7d: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8177d900)
Location: drivers/char/tpm/tpm-dev-common.c:159
Inline: False
```
**Symbols:**

```
ffffffff8177d900-ffffffff8177dabd: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: drivers/char/tpm/tpm-dev-common.c:159
Inline: False
```
**Symbols:**

```
ffffffff81cfca99-ffffffff81cfcac9: tpm_common_write.cold (STB_LOCAL)
ffffffff81803ae0-ffffffff81803cab: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: drivers/char/tpm/tpm-dev-common.c:165
Inline: False
```
**Symbols:**

```
ffffffff81ec5282-ffffffff81ec52ac: tpm_common_write.cold (STB_LOCAL)
ffffffff819433a0-ffffffff8194356b: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: drivers/char/tpm/tpm-dev-common.c:165
Inline: False
```
**Symbols:**

```
ffffffff82096acc-ffffffff82096af6: tpm_common_write.cold (STB_LOCAL)
ffffffff81aa5df0-ffffffff81aa5fbb: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: drivers/char/tpm/tpm-dev-common.c:165
Inline: False
```
**Symbols:**

```
ffffffff821179f9-ffffffff82117a23: tpm_common_write.cold (STB_LOCAL)
ffffffff81af15f0-ffffffff81af17bb: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: drivers/char/tpm/tpm-dev-common.c:165
Inline: False
```
**Symbols:**

```
ffffffff821f576e-ffffffff821f5798: tpm_common_write.cold (STB_LOCAL)
ffffffff81b44b50-ffffffff81b44d1b: tpm_common_write (STB_GLOBAL)
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
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffff8000108b8c18)
Location: drivers/char/tpm/tpm-dev-common.c:160
Inline: False
```
**Symbols:**

```
ffff8000108b8c18-ffff8000108b8ef0: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (c09b22e4)
Location: drivers/char/tpm/tpm-dev-common.c:160
Inline: False
```
**Symbols:**

```
c09b22e4-c09b24d8: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (c0000000009599f0)
Location: drivers/char/tpm/tpm-dev-common.c:160
Inline: False
```
**Symbols:**

```
c0000000009599f0-c000000000959c48: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffe0005692e2)
Location: drivers/char/tpm/tpm-dev-common.c:160
Inline: False
```
**Symbols:**

```
ffffffe0005692e2-ffffffe000569468: tpm_common_write (STB_GLOBAL)
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
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81694370)
Location: drivers/char/tpm/tpm-dev-common.c:160
Inline: False
```
**Symbols:**

```
ffffffff81694370-ffffffff81694537: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81671d60)
Location: drivers/char/tpm/tpm-dev-common.c:160
Inline: False
```
**Symbols:**

```
ffffffff81671d60-ffffffff81671f27: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816c25e0)
Location: drivers/char/tpm/tpm-dev-common.c:160
Inline: False
```
**Symbols:**

```
ffffffff816c25e0-ffffffff816c27a7: tpm_common_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file *file, const char *buf, size_t size, loff_t *off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816dcbb0)
Location: drivers/char/tpm/tpm-dev-common.c:160
Inline: False
```
**Symbols:**

```
ffffffff816dcbb0-ffffffff816dcd77: tpm_common_write (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct tpm_space *space</code>
</li>
</ul>
</details>
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
