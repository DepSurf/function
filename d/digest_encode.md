# Function: <code>digest_encode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int digest_encode(const char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto_fname.c (ffffffff812e5f00)
Location: fs/ext4/crypto_fname.c:208
Inline: False
Direct callers:
  - fs/ext4/crypto_fname.c:_ext4_fname_disk_to_usr
  - fs/ext4/crypto_fname.c:_ext4_fname_disk_to_usr
```
**Symbols:**

```
ffffffff812e5f00-ffffffff812e5f71: digest_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int digest_encode(const char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81288fa0)
Location: fs/crypto/fname.c:183
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff81288fa0-ffffffff8128901a: digest_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int digest_encode(const char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8129dd40)
Location: fs/crypto/fname.c:168
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff8129dd40-ffffffff8129ddba: digest_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int digest_encode(const char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812ac7f0)
Location: fs/crypto/fname.c:170
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff812ac7f0-ffffffff812ac863: digest_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int digest_encode(const char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812d0000)
Location: fs/crypto/fname.c:147
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff812d0000-ffffffff812d0073: digest_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int digest_encode(const char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812fa950)
Location: fs/crypto/fname.c:140
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff812fa950-ffffffff812fa9c3: digest_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int digest_encode(const char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8130fcd0)
Location: fs/crypto/fname.c:142
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff8130fcd0-ffffffff8130fd43: digest_encode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int digest_encode(const char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813371c0)
Location: fs/crypto/fname.c:141
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff813371c0-ffffffff81337234: digest_encode (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
