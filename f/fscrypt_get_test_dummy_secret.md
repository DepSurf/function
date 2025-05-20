# Function: <code>fscrypt_get_test_dummy_secret</code>

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
void fscrypt_get_test_dummy_secret(struct fscrypt_master_key_secret *secret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146cb10)
Location: fs/crypto/keyring.c:692
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
```
**Symbols:**

```
ffffffff8146cb10-ffffffff8146cc18: fscrypt_get_test_dummy_secret (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fscrypt_get_test_dummy_secret(struct fscrypt_master_key_secret *secret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814fe330)
Location: fs/crypto/keyring.c:748
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
```
**Symbols:**

```
ffffffff814fe330-ffffffff814fe438: fscrypt_get_test_dummy_secret (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fscrypt_get_test_dummy_secret(struct fscrypt_master_key_secret *secret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81535970)
Location: fs/crypto/keyring.c:751
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
```
**Symbols:**

```
ffffffff81535970-ffffffff81535a78: fscrypt_get_test_dummy_secret (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fscrypt_get_test_dummy_secret(struct fscrypt_master_key_secret *secret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8156a940)
Location: fs/crypto/keyring.c:766
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
```
**Symbols:**

```
ffffffff8156a940-ffffffff8156aa48: fscrypt_get_test_dummy_secret (STB_LOCAL)
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
