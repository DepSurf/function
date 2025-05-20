# Function: <code>base64_decode</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8134b45c)
Location: fs/crypto/fname.c:158
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81390ec9)
Location: fs/crypto/fname.c:239
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a238a)
Location: fs/crypto/fname.c:213
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a950a)
Location: fs/crypto/fname.c:213
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int base64_decode(const char *src, int srclen, u8 *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/base64.c (0)
Location: lib/base64.c:73
Inline: False
```
**Symbols:**

```
ffffffff8207877f-ffffffff820787b1: base64_decode.cold (STB_LOCAL)
ffffffff817db2a0-ffffffff817db3bb: base64_decode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int base64_decode(const char *src, int srclen, u8 *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/base64.c (0)
Location: lib/base64.c:73
Inline: False
```
**Symbols:**

```
ffffffff820f8d27-ffffffff820f8d5c: base64_decode.cold (STB_LOCAL)
ffffffff8181a510-ffffffff8181a62b: base64_decode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int base64_decode(const char *src, int srclen, u8 *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/base64.c (0)
Location: lib/base64.c:73
Inline: False
```
**Symbols:**

```
ffffffff821d6848-ffffffff821d687d: base64_decode.cold (STB_LOCAL)
ffffffff8185f860-ffffffff8185f97b: base64_decode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffff80001040be90)
Location: fs/crypto/fname.c:158
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (c05d8fdc)
Location: fs/crypto/fname.c:158
Inline: True
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
In fs/crypto/fname.c (c000000000518c3c)
Location: fs/crypto/fname.c:158
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffe0002b5902)
Location: fs/crypto/fname.c:158
Inline: True
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
In fs/crypto/fname.c (ffffffff81343a3c)
Location: fs/crypto/fname.c:158
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
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
In fs/crypto/fname.c (ffffffff8133471c)
Location: fs/crypto/fname.c:158
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
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
In fs/crypto/fname.c (ffffffff8134150c)
Location: fs/crypto/fname.c:158
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
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
In fs/crypto/fname.c (ffffffff8135480c)
Location: fs/crypto/fname.c:158
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
