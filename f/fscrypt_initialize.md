# Function: <code>fscrypt_initialize</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_initialize();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81288850)
Location: fs/crypto/crypto.c:491
Inline: True
```
**Symbols:**

```
ffffffff81288850-ffffffff81288921: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8129dc60)
Location: fs/crypto/crypto.c:527
Inline: False
```
**Symbols:**

```
ffffffff8129dc60-ffffffff8129dd38: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812ac710)
Location: fs/crypto/crypto.c:409
Inline: False
```
**Symbols:**

```
ffffffff812ac710-ffffffff812ac7e7: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812cff30)
Location: fs/crypto/crypto.c:389
Inline: False
```
**Symbols:**

```
ffffffff812cff30-ffffffff812cfffb: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812fa2c0)
Location: fs/crypto/crypto.c:391
Inline: False
```
**Symbols:**

```
ffffffff812fa2c0-ffffffff812fa38f: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8130f610)
Location: fs/crypto/crypto.c:393
Inline: False
```
**Symbols:**

```
ffffffff8130f610-ffffffff8130f6df: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81336af0)
Location: fs/crypto/crypto.c:421
Inline: False
```
**Symbols:**

```
ffffffff81336af0-ffffffff81336bb9: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8134a670)
Location: fs/crypto/crypto.c:419
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff8134a670-ffffffff8134a78f: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8138fe70)
Location: fs/crypto/crypto.c:308
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff8138fe70-ffffffff8138fee9: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a14b0)
Location: fs/crypto/crypto.c:308
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff813a14b0-ffffffff813a1529: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a8640)
Location: fs/crypto/crypto.c:308
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff813a8640-ffffffff813a86b9: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813f7d80)
Location: fs/crypto/crypto.c:308
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff813f7d80-ffffffff813f7df9: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8146aa90)
Location: fs/crypto/crypto.c:316
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff8146aa90-ffffffff8146ab1b: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff814fba50)
Location: fs/crypto/crypto.c:316
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff814fba50-ffffffff814fbadb: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_initialize(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81532d70)
Location: fs/crypto/crypto.c:318
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff81532d70-ffffffff81532e0c: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_initialize(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81567c70)
Location: fs/crypto/crypto.c:336
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff81567c70-ffffffff81567d0c: fscrypt_initialize (STB_GLOBAL)
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
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffff80001040ae60)
Location: fs/crypto/crypto.c:419
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffff80001040ae60-ffff80001040af7c: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c05d7ffc)
Location: fs/crypto/crypto.c:419
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
c05d7ffc-c05d8110: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c000000000517840)
Location: fs/crypto/crypto.c:419
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
c000000000517840-c000000000517a08: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffe0002b4b8a)
Location: fs/crypto/crypto.c:419
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffe0002b4b8a-ffffffe0002b4cc4: fscrypt_initialize (STB_GLOBAL)
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
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81342c50)
Location: fs/crypto/crypto.c:419
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81342c50-ffffffff81342d6f: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81333930)
Location: fs/crypto/crypto.c:419
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81333930-ffffffff81333a4f: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81340720)
Location: fs/crypto/crypto.c:419
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81340720-ffffffff8134083f: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fscrypt_initialize(unsigned int cop_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81353a20)
Location: fs/crypto/crypto.c:419
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81353a20-ffffffff81353b3f: fscrypt_initialize (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int cop_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct super_block *sb</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int cop_flags</code>
</li>
</ul>
</details>
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
