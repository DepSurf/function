# Function: <code>bh_get_inode_and_lblk_num</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813a7315)
Location: fs/crypto/inline_crypt.c:258
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
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
In fs/crypto/inline_crypt.c (ffffffff813ae365)
Location: fs/crypto/inline_crypt.c:258
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813fe005)
Location: fs/crypto/inline_crypt.c:258
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bh_get_inode_and_lblk_num(const struct buffer_head *bh, const struct inode **inode_ret, u64 *lblk_num_ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff81471b75)
Location: fs/crypto/inline_crypt.c:290
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
```
**Symbols:**

```
ffffffff81471680-ffffffff81471723: bh_get_inode_and_lblk_num (STB_LOCAL)
ffffffff81e78f8b-ffffffff81e78fd9: bh_get_inode_and_lblk_num.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bh_get_inode_and_lblk_num(const struct buffer_head *bh, const struct inode **inode_ret, u64 *lblk_num_ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff81503775)
Location: fs/crypto/inline_crypt.c:281
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
```
**Symbols:**

```
ffffffff815031a0-ffffffff81503243: bh_get_inode_and_lblk_num (STB_LOCAL)
ffffffff8206a889-ffffffff8206a8d7: bh_get_inode_and_lblk_num.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bh_get_inode_and_lblk_num(const struct buffer_head *bh, const struct inode **inode_ret, u64 *lblk_num_ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8153b025)
Location: fs/crypto/inline_crypt.c:281
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
```
**Symbols:**

```
ffffffff8153aa60-ffffffff8153ab00: bh_get_inode_and_lblk_num (STB_LOCAL)
ffffffff820ea6c3-ffffffff820ea718: bh_get_inode_and_lblk_num.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool bh_get_inode_and_lblk_num(const struct buffer_head *bh, const struct inode **inode_ret, u64 *lblk_num_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:283
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
```
**Symbols:**

```
ffffffff8156fbd0-ffffffff8156fcbc: bh_get_inode_and_lblk_num (STB_LOCAL)
ffffffff821c734e-ffffffff821c73e2: bh_get_inode_and_lblk_num.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
