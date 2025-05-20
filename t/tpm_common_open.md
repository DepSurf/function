# Function: <code>tpm_common_open</code>

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
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff815bb230)
Location: drivers/char/tpm/tpm-dev-common.c:45
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff815bb230-ffffffff815bb2ad: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81621770)
Location: drivers/char/tpm/tpm-dev-common.c:45
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff81621770-ffffffff816217e9: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8165b4e0)
Location: drivers/char/tpm/tpm-dev-common.c:45
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff8165b4e0-ffffffff8165b552: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81675ba0)
Location: drivers/char/tpm/tpm-dev-common.c:73
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff81675ba0-ffffffff81675c5b: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816ab9a0)
Location: drivers/char/tpm/tpm-dev-common.c:98
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff816ab9a0-ffffffff816aba5b: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816ce700)
Location: drivers/char/tpm/tpm-dev-common.c:105
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff816ce700-ffffffff816ce7bb: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81783610)
Location: drivers/char/tpm/tpm-dev-common.c:105
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff81783610-ffffffff817836cb: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8179aba0)
Location: drivers/char/tpm/tpm-dev-common.c:105
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff8179aba0-ffffffff8179ac5b: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8177d6f0)
Location: drivers/char/tpm/tpm-dev-common.c:104
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff8177d6f0-ffffffff8177d7ab: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff818038d0)
Location: drivers/char/tpm/tpm-dev-common.c:104
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff818038d0-ffffffff8180398b: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81943170)
Location: drivers/char/tpm/tpm-dev-common.c:110
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff81943170-ffffffff8194323c: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81aa5b90)
Location: drivers/char/tpm/tpm-dev-common.c:110
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff81aa5b90-ffffffff81aa5c5c: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81af1390)
Location: drivers/char/tpm/tpm-dev-common.c:110
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff81af1390-ffffffff81af145c: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81b448f0)
Location: drivers/char/tpm/tpm-dev-common.c:110
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff81b448f0-ffffffff81b449bc: tpm_common_open (STB_GLOBAL)
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
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffff8000108b88d0)
Location: drivers/char/tpm/tpm-dev-common.c:105
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffff8000108b88d0-ffff8000108b8998: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (c09b20c0)
Location: drivers/char/tpm/tpm-dev-common.c:105
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
c09b20c0-c09b2184: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (c0000000009596f0)
Location: drivers/char/tpm/tpm-dev-common.c:105
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
c0000000009596f0-c0000000009597f4: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffe00056910a)
Location: drivers/char/tpm/tpm-dev-common.c:105
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffe00056910a-ffffffe0005691ce: tpm_common_open (STB_GLOBAL)
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
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81694150)
Location: drivers/char/tpm/tpm-dev-common.c:105
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff81694150-ffffffff8169420b: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81671b40)
Location: drivers/char/tpm/tpm-dev-common.c:105
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff81671b40-ffffffff81671bfb: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816c23c0)
Location: drivers/char/tpm/tpm-dev-common.c:105
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff816c23c0-ffffffff816c247b: tpm_common_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tpm_common_open(struct file *file, struct tpm_chip *chip, struct file_priv *priv, struct tpm_space *space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816dc990)
Location: drivers/char/tpm/tpm-dev-common.c:105
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
**Symbols:**

```
ffffffff816dc990-ffffffff816dca4b: tpm_common_open (STB_GLOBAL)
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
<b>Param added. </b>
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
