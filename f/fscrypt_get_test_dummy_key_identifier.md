# Function: <code>fscrypt_get_test_dummy_key_identifier</code>

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
int fscrypt_get_test_dummy_key_identifier(u8 *key_identifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146e150)
Location: fs/crypto/keyring.c:703
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption
```
**Symbols:**

```
ffffffff8146e150-ffffffff8146e207: fscrypt_get_test_dummy_key_identifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_get_test_dummy_key_identifier(u8 *key_identifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814ff760)
Location: fs/crypto/keyring.c:759
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption
```
**Symbols:**

```
ffffffff814ff760-ffffffff814ff817: fscrypt_get_test_dummy_key_identifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_get_test_dummy_key_identifier(u8 *key_identifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81536c80)
Location: fs/crypto/keyring.c:762
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption
```
**Symbols:**

```
ffffffff81536c80-ffffffff81536d37: fscrypt_get_test_dummy_key_identifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_get_test_dummy_key_identifier(u8 *key_identifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8156bd30)
Location: fs/crypto/keyring.c:777
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption
```
**Symbols:**

```
ffffffff8156bd30-ffffffff8156bde7: fscrypt_get_test_dummy_key_identifier (STB_GLOBAL)
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
