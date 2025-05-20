# Function: <code>tpm_unseal_trusted</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm_unseal_trusted(u32 chip_num, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81523920)
Location: drivers/char/tpm/tpm-interface.c:1100
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81523920-ffffffff81523984: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_unseal_trusted(u32 chip_num, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81576850)
Location: drivers/char/tpm/tpm-interface.c:1128
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81576850-ffffffff815768af: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_unseal_trusted(u32 chip_num, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a2ec0)
Location: drivers/char/tpm/tpm-interface.c:1114
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff815a2ec0-ffffffff815a2f1f: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_unseal_trusted(u32 chip_num, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b6a20)
Location: drivers/char/tpm/tpm-interface.c:1285
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff815b6a20-ffffffff815b6a75: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_unseal_trusted(u32 chip_num, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161d750)
Location: drivers/char/tpm/tpm-interface.c:1307
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff8161d750-ffffffff8161d7a5: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm_unseal_trusted(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81657180)
Location: drivers/char/tpm/tpm-interface.c:1380
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81657180-ffffffff816571d5: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm_unseal_trusted(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816764d0)
Location: drivers/char/tpm/tpm-interface.c:674
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff816764d0-ffffffff81676525: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm_unseal_trusted(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816ac2b0)
Location: drivers/char/tpm/tpm-interface.c:495
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff816ac2b0-ffffffff816ac307: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm_unseal_trusted(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816cf010)
Location: drivers/char/tpm/tpm-interface.c:494
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff816cf010-ffffffff816cf067: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int tpm_unseal_trusted(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffff8000108b9638)
Location: drivers/char/tpm/tpm-interface.c:494
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffff8000108b9638-ffff8000108b96a8: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_unseal_trusted(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c09b2a6c)
Location: drivers/char/tpm/tpm-interface.c:494
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
c09b2a6c-c09b2acc: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_unseal_trusted(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c00000000095a550)
Location: drivers/char/tpm/tpm-interface.c:494
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
c00000000095a550-c00000000095a5e8: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_unseal_trusted(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffe000569a08)
Location: drivers/char/tpm/tpm-interface.c:494
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffe000569a08-ffffffe000569a6a: tpm_unseal_trusted (STB_GLOBAL)
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
int tpm_unseal_trusted(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81694a60)
Location: drivers/char/tpm/tpm-interface.c:494
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81694a60-ffffffff81694ab7: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm_unseal_trusted(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81672450)
Location: drivers/char/tpm/tpm-interface.c:494
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81672450-ffffffff816724a7: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm_unseal_trusted(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816c2cd0)
Location: drivers/char/tpm/tpm-interface.c:494
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff816c2cd0-ffffffff816c2d27: tpm_unseal_trusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm_unseal_trusted(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816dd2a0)
Location: drivers/char/tpm/tpm-interface.c:494
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff816dd2a0-ffffffff816dd2f7: tpm_unseal_trusted (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
