# Function: <code>keyctl_dh_compute_kdf</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8139624e)
Location: security/keys/dh.c:213
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff813bb9c2)
Location: security/keys/dh.c:213
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff813ec71a)
Location: security/keys/dh.c:204
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8140730e)
Location: security/keys/dh.c:204
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81434470)
Location: security/keys/dh.c:199
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8144e1cb)
Location: security/keys/dh.c:199
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int keyctl_dh_compute_kdf(struct kdf_sdesc *sdesc, char *buffer, size_t buflen, uint8_t *kbuf, size_t kbuflen, size_t lzero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8149ff80)
Location: security/keys/dh.c:199
Inline: False
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff8149ff80-ffffffff814a0063: keyctl_dh_compute_kdf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int keyctl_dh_compute_kdf(struct kdf_sdesc *sdesc, char *buffer, size_t buflen, uint8_t *kbuf, size_t kbuflen, size_t lzero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814bd990)
Location: security/keys/dh.c:199
Inline: False
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff814bd990-ffffffff814bda73: keyctl_dh_compute_kdf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int keyctl_dh_compute_kdf(struct kdf_sdesc *sdesc, char *buffer, size_t buflen, uint8_t *kbuf, size_t kbuflen, size_t lzero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814c3800)
Location: security/keys/dh.c:199
Inline: False
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff814c3800-ffffffff814c38e1: keyctl_dh_compute_kdf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int keyctl_dh_compute_kdf(struct kdf_sdesc *sdesc, char *buffer, size_t buflen, uint8_t *kbuf, size_t kbuflen, size_t lzero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8151c1d0)
Location: security/keys/dh.c:199
Inline: False
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff8151c1d0-ffffffff8151c2b1: keyctl_dh_compute_kdf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int keyctl_dh_compute_kdf(struct crypto_shash *hash, char *buffer, size_t buflen, uint8_t *kbuf, size_t kbuflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff815af1d0)
Location: security/keys/dh.c:110
Inline: False
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff815af1d0-ffffffff815af2d1: keyctl_dh_compute_kdf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int keyctl_dh_compute_kdf(struct crypto_shash *hash, char *buffer, size_t buflen, uint8_t *kbuf, size_t kbuflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff816599d0)
Location: security/keys/dh.c:110
Inline: False
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff816599d0-ffffffff81659ad1: keyctl_dh_compute_kdf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int keyctl_dh_compute_kdf(struct crypto_shash *hash, char *buffer, size_t buflen, uint8_t *kbuf, size_t kbuflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81692230)
Location: security/keys/dh.c:94
Inline: False
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff81692230-ffffffff81692331: keyctl_dh_compute_kdf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int keyctl_dh_compute_kdf(struct crypto_shash *hash, char *buffer, size_t buflen, uint8_t *kbuf, size_t kbuflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff816ce800)
Location: security/keys/dh.c:94
Inline: False
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff816ce800-ffffffff816ce901: keyctl_dh_compute_kdf (STB_LOCAL)
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
int keyctl_dh_compute_kdf(struct kdf_sdesc *sdesc, char *buffer, size_t buflen, uint8_t *kbuf, size_t kbuflen, size_t lzero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffff800010538318)
Location: security/keys/dh.c:199
Inline: False
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffff800010538318-ffff8000105385e0: keyctl_dh_compute_kdf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int keyctl_dh_compute_kdf(struct kdf_sdesc *sdesc, char *buffer, size_t buflen, uint8_t *kbuf, size_t kbuflen, size_t lzero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (c06eecac)
Location: security/keys/dh.c:199
Inline: False
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
c06eecac-c06eef60: keyctl_dh_compute_kdf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (c0000000006875f4)
Location: security/keys/dh.c:199
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int keyctl_dh_compute_kdf(struct kdf_sdesc *sdesc, char *buffer, size_t buflen, uint8_t *kbuf, size_t kbuflen, size_t lzero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffe0003970be)
Location: security/keys/dh.c:199
Inline: False
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffe0003970be-ffffffe0003972f2: keyctl_dh_compute_kdf (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814467ab)
Location: security/keys/dh.c:199
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814371fb)
Location: security/keys/dh.c:199
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8144284b)
Location: security/keys/dh.c:199
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81459b7b)
Location: security/keys/dh.c:199
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct crypto_shash *hash</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kdf_sdesc *sdesc</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t lzero</code>
</li>
</ul>
</details>
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
</ul>
