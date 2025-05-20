# Function: <code>fscrypt_set_test_dummy_encryption</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_set_test_dummy_encryption(struct super_block *sb, const substring_t *arg, struct fscrypt_dummy_context *dummy_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81394a50)
Location: fs/crypto/policy.c:665
Inline: False
Direct callers:
  - fs/ext4/super.c:handle_mount_opt
```
**Symbols:**

```
ffffffff81394a50-ffffffff81394c1c: fscrypt_set_test_dummy_encryption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_set_test_dummy_encryption(struct super_block *sb, const char *arg, struct fscrypt_dummy_policy *dummy_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813a6140)
Location: fs/crypto/policy.c:723
Inline: False
Direct callers:
  - fs/ext4/super.c:handle_mount_opt
```
**Symbols:**

```
ffffffff813a6140-ffffffff813a62f8: fscrypt_set_test_dummy_encryption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_set_test_dummy_encryption(struct super_block *sb, const char *arg, struct fscrypt_dummy_policy *dummy_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813ad1c0)
Location: fs/crypto/policy.c:723
Inline: False
Direct callers:
  - fs/ext4/super.c:handle_mount_opt
```
**Symbols:**

```
ffffffff813ad1c0-ffffffff813ad378: fscrypt_set_test_dummy_encryption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_set_test_dummy_encryption(struct super_block *sb, const char *arg, struct fscrypt_dummy_policy *dummy_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813fcb30)
Location: fs/crypto/policy.c:723
Inline: False
Direct callers:
  - fs/ext4/super.c:handle_mount_opt
```
**Symbols:**

```
ffffffff813fcb30-ffffffff813fcce8: fscrypt_set_test_dummy_encryption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_set_test_dummy_encryption(struct super_block *sb, const char *arg, struct fscrypt_dummy_policy *dummy_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81470270)
Location: fs/crypto/policy.c:806
Inline: False
```
**Symbols:**

```
ffffffff81470270-ffffffff8147030f: fscrypt_set_test_dummy_encryption (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fscrypt_dummy_policy *dummy_policy</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fscrypt_dummy_context *dummy_ctx</code>
</li>
<li>
<b>Param type changed. </b>
<code>const substring_t *arg</code> ➡️ <code>const char *arg</code>
</li>
</ul>
</details>
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
</ul>
