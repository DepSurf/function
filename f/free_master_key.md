# Function: <code>free_master_key</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff8131107f)
Location: fs/crypto/keyinfo.c:282
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:find_or_insert_master_key
Direct callers:
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:find_or_insert_master_key
```
**Symbols:**

```
ffffffff81310d40-ffffffff81310d65: free_master_key.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff813383fd)
Location: fs/crypto/keyinfo.c:281
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:find_or_insert_master_key
Direct callers:
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:find_or_insert_master_key
```
**Symbols:**

```
ffffffff81338280-ffffffff813382a7: free_master_key.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8134c3c0)
Location: fs/crypto/keyring.c:40
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
ffffffff8134c3c0-ffffffff8134c442: free_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81391f20)
Location: fs/crypto/keyring.c:41
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
ffffffff81391f20-ffffffff81391fbf: free_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a32c0)
Location: fs/crypto/keyring.c:41
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
ffffffff813a32c0-ffffffff813a3353: free_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813aa500)
Location: fs/crypto/keyring.c:41
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
ffffffff813aa500-ffffffff813aa593: free_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813f9d50)
Location: fs/crypto/keyring.c:41
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
ffffffff813f9d50-ffffffff813f9e25: free_master_key (STB_LOCAL)
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
In fs/crypto/keyring.c (ffffffff8146d22a)
Location: fs/crypto/keyring.c:41
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
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
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffff80001040cf68)
Location: fs/crypto/keyring.c:40
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
ffff80001040cf68-ffff80001040cfdc: free_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c05d9f80)
Location: fs/crypto/keyring.c:40
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
c05d9f80-c05d9fdc: free_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c00000000051a380)
Location: fs/crypto/keyring.c:40
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
c00000000051a380-c00000000051a41c: free_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffe0002b64b2)
Location: fs/crypto/keyring.c:40
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
ffffffe0002b64b2-ffffffe0002b6516: free_master_key (STB_LOCAL)
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
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813449a0)
Location: fs/crypto/keyring.c:40
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
ffffffff813449a0-ffffffff81344a22: free_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81335680)
Location: fs/crypto/keyring.c:40
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
ffffffff81335680-ffffffff81335702: free_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81342470)
Location: fs/crypto/keyring.c:40
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
ffffffff81342470-ffffffff813424f2: free_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_master_key(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81355770)
Location: fs/crypto/keyring.c:40
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
ffffffff81355770-ffffffff813557f2: free_master_key (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
