# Function: <code>fscrypt_parse_test_dummy_encryption</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_parse_test_dummy_encryption(const struct fs_parameter *param, struct fscrypt_dummy_policy *dummy_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81470140)
Location: fs/crypto/policy.c:738
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_test_dummy_encryption
  - fs/ext4/super.c:ext4_parse_param
```
**Symbols:**

```
ffffffff81470140-ffffffff8147026b: fscrypt_parse_test_dummy_encryption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_parse_test_dummy_encryption(const struct fs_parameter *param, struct fscrypt_dummy_policy *dummy_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81501b80)
Location: fs/crypto/policy.c:777
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_parse_param
```
**Symbols:**

```
ffffffff81501b80-ffffffff81501cab: fscrypt_parse_test_dummy_encryption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_parse_test_dummy_encryption(const struct fs_parameter *param, struct fscrypt_dummy_policy *dummy_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81539180)
Location: fs/crypto/policy.c:776
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_parse_param
```
**Symbols:**

```
ffffffff81539180-ffffffff815392a7: fscrypt_parse_test_dummy_encryption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_parse_test_dummy_encryption(const struct fs_parameter *param, struct fscrypt_dummy_policy *dummy_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8156e320)
Location: fs/crypto/policy.c:803
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_parse_param
```
**Symbols:**

```
ffffffff8156e320-ffffffff8156e494: fscrypt_parse_test_dummy_encryption (STB_GLOBAL)
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
