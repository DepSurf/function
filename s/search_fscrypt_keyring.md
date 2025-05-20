# Function: <code>search_fscrypt_keyring</code>

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
struct key *search_fscrypt_keyring(struct key *keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8134c1b0)
Location: fs/crypto/keyring.c:131
Inline: False
Direct callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffffffff8134c1b0-ffffffff8134c1e7: search_fscrypt_keyring (STB_LOCAL)
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
In fs/crypto/keyring.c (ffffffff81391e50)
Location: fs/crypto/keyring.c:135
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
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
In fs/crypto/keyring.c (ffffffff813a31ed)
Location: fs/crypto/keyring.c:135
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
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
In fs/crypto/keyring.c (ffffffff813aa42d)
Location: fs/crypto/keyring.c:135
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
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
In fs/crypto/keyring.c (ffffffff813f9c7d)
Location: fs/crypto/keyring.c:135
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146cf8e)
Location: fs/crypto/keyring.c:135
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct key *search_fscrypt_keyring(struct key *keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffff80001040cd28)
Location: fs/crypto/keyring.c:131
Inline: False
Direct callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffff80001040cd28-ffff80001040cd9c: search_fscrypt_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *search_fscrypt_keyring(struct key *keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c05d9d90)
Location: fs/crypto/keyring.c:131
Inline: False
Direct callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
c05d9d90-c05d9dd0: search_fscrypt_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key *search_fscrypt_keyring(struct key *keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c00000000051a0b0)
Location: fs/crypto/keyring.c:131
Inline: False
Direct callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
c00000000051a0b0-c00000000051a118: search_fscrypt_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *search_fscrypt_keyring(struct key *keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffe0002b658e)
Location: fs/crypto/keyring.c:131
Inline: False
Direct callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffffffe0002b658e-ffffffe0002b65e8: search_fscrypt_keyring (STB_LOCAL)
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
struct key *search_fscrypt_keyring(struct key *keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81344790)
Location: fs/crypto/keyring.c:131
Inline: False
Direct callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffffffff81344790-ffffffff813447c7: search_fscrypt_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key *search_fscrypt_keyring(struct key *keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81335470)
Location: fs/crypto/keyring.c:131
Inline: False
Direct callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffffffff81335470-ffffffff813354a7: search_fscrypt_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key *search_fscrypt_keyring(struct key *keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81342260)
Location: fs/crypto/keyring.c:131
Inline: False
Direct callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffffffff81342260-ffffffff81342297: search_fscrypt_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key *search_fscrypt_keyring(struct key *keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81355560)
Location: fs/crypto/keyring.c:131
Inline: False
Direct callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffffffff81355560-ffffffff81355597: search_fscrypt_keyring (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
