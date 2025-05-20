# Function: <code>find_master_key_user</code>

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
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8134c1f0)
Location: fs/crypto/keyring.c:264
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff8134c1f0-ffffffff8134c272: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81391e00)
Location: fs/crypto/keyring.c:268
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:do_add_master_key
```
**Symbols:**

```
ffffffff81391e00-ffffffff81391ea8: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a31a0)
Location: fs/crypto/keyring.c:277
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:do_add_master_key
```
**Symbols:**

```
ffffffff813a31a0-ffffffff813a3242: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813aa3e0)
Location: fs/crypto/keyring.c:277
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:do_add_master_key
```
**Symbols:**

```
ffffffff813aa3e0-ffffffff813aa482: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813f9c30)
Location: fs/crypto/keyring.c:277
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:do_add_master_key
```
**Symbols:**

```
ffffffff813f9c30-ffffffff813f9cd2: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146cf30)
Location: fs/crypto/keyring.c:277
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:do_add_master_key
```
**Symbols:**

```
ffffffff8146cf30-ffffffff8146cff5: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814fe4d0)
Location: fs/crypto/keyring.c:345
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff814fe4d0-ffffffff814fe59b: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81535b10)
Location: fs/crypto/keyring.c:348
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff81535b10-ffffffff81535bdb: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8156aae0)
Location: fs/crypto/keyring.c:355
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff8156aae0-ffffffff8156abab: find_master_key_user (STB_LOCAL)
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
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffff80001040cda0)
Location: fs/crypto/keyring.c:264
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffff80001040cda0-ffff80001040ce20: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c05d9dd0)
Location: fs/crypto/keyring.c:264
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
c05d9dd0-c05d9e44: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c00000000051a120)
Location: fs/crypto/keyring.c:264
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
c00000000051a120-c00000000051a1bc: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffe0002b65e8)
Location: fs/crypto/keyring.c:264
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffe0002b65e8-ffffffe0002b663e: find_master_key_user (STB_LOCAL)
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
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813447d0)
Location: fs/crypto/keyring.c:264
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff813447d0-ffffffff81344852: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813354b0)
Location: fs/crypto/keyring.c:264
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff813354b0-ffffffff81335532: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813422a0)
Location: fs/crypto/keyring.c:264
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff813422a0-ffffffff81342322: find_master_key_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key *find_master_key_user(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813555a0)
Location: fs/crypto/keyring.c:264
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff813555a0-ffffffff81355622: find_master_key_user (STB_LOCAL)
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
