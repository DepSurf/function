# Function: <code>base64_encode</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int base64_encode(const u8 *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8134ad80)
Location: fs/crypto/fname.c:139
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff8134ad80-ffffffff8134adf1: base64_encode (STB_LOCAL)
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
In fs/crypto/fname.c (ffffffff81390a0e)
Location: fs/crypto/fname.c:220
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
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
In fs/crypto/fname.c (ffffffff813a1f2e)
Location: fs/crypto/fname.c:194
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
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
In fs/crypto/fname.c (ffffffff813a90c2)
Location: fs/crypto/fname.c:194
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
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
<summary>In <code>6.2</code>: ✅</summary>

```c
int base64_encode(const u8 *src, int srclen, char *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/base64.c (ffffffff817db170)
Location: lib/base64.c:32
Inline: False
```
**Symbols:**

```
ffffffff817db170-ffffffff817db286: base64_encode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int base64_encode(const u8 *src, int srclen, char *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/base64.c (0)
Location: lib/base64.c:32
Inline: False
```
**Symbols:**

```
ffffffff820f8cd3-ffffffff820f8d27: base64_encode.cold (STB_LOCAL)
ffffffff8181a3e0-ffffffff8181a4f8: base64_encode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int base64_encode(const u8 *src, int srclen, char *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/base64.c (0)
Location: lib/base64.c:32
Inline: False
```
**Symbols:**

```
ffffffff821d67f4-ffffffff821d6848: base64_encode.cold (STB_LOCAL)
ffffffff8185f730-ffffffff8185f848: base64_encode (STB_GLOBAL)
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
int base64_encode(const u8 *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffff80001040b6b0)
Location: fs/crypto/fname.c:139
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffff80001040b6b0-ffff80001040b75c: base64_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int base64_encode(const u8 *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (c05d887c)
Location: fs/crypto/fname.c:139
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
c05d887c-c05d88fc: base64_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int base64_encode(const u8 *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (c000000000518260)
Location: fs/crypto/fname.c:139
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
c000000000518260-c000000000518328: base64_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int base64_encode(const u8 *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffe0002b51fc)
Location: fs/crypto/fname.c:139
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffe0002b51fc-ffffffe0002b528e: base64_encode (STB_LOCAL)
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
int base64_encode(const u8 *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81343360)
Location: fs/crypto/fname.c:139
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff81343360-ffffffff813433d1: base64_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int base64_encode(const u8 *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81334040)
Location: fs/crypto/fname.c:139
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff81334040-ffffffff813340b1: base64_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int base64_encode(const u8 *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81340e30)
Location: fs/crypto/fname.c:139
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff81340e30-ffffffff81340ea1: base64_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int base64_encode(const u8 *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81354130)
Location: fs/crypto/fname.c:139
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff81354130-ffffffff813541a1: base64_encode (STB_LOCAL)
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
