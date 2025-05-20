# Function: <code>fscrypt_generate_dun</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fscrypt_generate_dun(const struct fscrypt_info *ci, u64 lblk_num, u64 *dun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813a71b0)
Location: fs/crypto/inline_crypt.c:212
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
```
**Symbols:**

```
ffffffff813a71b0-ffffffff813a724d: fscrypt_generate_dun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fscrypt_generate_dun(const struct fscrypt_info *ci, u64 lblk_num, u64 *dun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813ae210)
Location: fs/crypto/inline_crypt.c:212
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
```
**Symbols:**

```
ffffffff813ae210-ffffffff813ae2ad: fscrypt_generate_dun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fscrypt_generate_dun(const struct fscrypt_info *ci, u64 lblk_num, u64 *dun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813fdd90)
Location: fs/crypto/inline_crypt.c:212
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
```
**Symbols:**

```
ffffffff813fdd90-ffffffff813fde5a: fscrypt_generate_dun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fscrypt_generate_dun(const struct fscrypt_info *ci, u64 lblk_num, u64 *dun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff81471580)
Location: fs/crypto/inline_crypt.c:244
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
```
**Symbols:**

```
ffffffff81471580-ffffffff81471676: fscrypt_generate_dun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fscrypt_generate_dun(const struct fscrypt_info *ci, u64 lblk_num, u64 *dun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff81503090)
Location: fs/crypto/inline_crypt.c:235
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
```
**Symbols:**

```
ffffffff81503090-ffffffff81503186: fscrypt_generate_dun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fscrypt_generate_dun(const struct fscrypt_info *ci, u64 lblk_num, u64 *dun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8153a950)
Location: fs/crypto/inline_crypt.c:235
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
```
**Symbols:**

```
ffffffff8153a950-ffffffff8153aa46: fscrypt_generate_dun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fscrypt_generate_dun(const struct fscrypt_inode_info *ci, u64 lblk_num, u64 *dun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:235
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
```
**Symbols:**

```
ffffffff8156fab0-ffffffff8156fbb8: fscrypt_generate_dun (STB_LOCAL)
ffffffff821c732d-ffffffff821c734e: fscrypt_generate_dun.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct fscrypt_info *ci</code> ➡️ <code>const struct fscrypt_inode_info *ci</code>
</li>
</ul>
</details>
</li>
</ul>
