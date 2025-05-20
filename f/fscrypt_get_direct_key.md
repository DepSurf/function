# Function: <code>fscrypt_get_direct_key</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff8134e5e6)
Location: fs/crypto/keysetup_v1.c:218
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fscrypt_direct_key *fscrypt_get_direct_key(const struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813944b0)
Location: fs/crypto/keysetup_v1.c:218
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff813944b0-ffffffff81394596: fscrypt_get_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fscrypt_direct_key *fscrypt_get_direct_key(const struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813a59a0)
Location: fs/crypto/keysetup_v1.c:220
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff813a59a0-ffffffff813a5a6f: fscrypt_get_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fscrypt_direct_key *fscrypt_get_direct_key(const struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813aca00)
Location: fs/crypto/keysetup_v1.c:220
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff813aca00-ffffffff813acacf: fscrypt_get_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fscrypt_direct_key *fscrypt_get_direct_key(const struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813fc370)
Location: fs/crypto/keysetup_v1.c:220
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff813fc370-ffffffff813fc43f: fscrypt_get_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct fscrypt_direct_key *fscrypt_get_direct_key(const struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:220
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff8146f7f0-ffffffff8146f8e5: fscrypt_get_direct_key (STB_LOCAL)
ffffffff81e78bee-ffffffff81e78bfa: fscrypt_get_direct_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fscrypt_direct_key *fscrypt_get_direct_key(const struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81500fa0)
Location: fs/crypto/keysetup_v1.c:221
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff81500fa0-ffffffff815010a9: fscrypt_get_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fscrypt_direct_key *fscrypt_get_direct_key(const struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81538630)
Location: fs/crypto/keysetup_v1.c:221
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff81538630-ffffffff81538739: fscrypt_get_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fscrypt_direct_key *fscrypt_get_direct_key(const struct fscrypt_inode_info *ci, const u8 *raw_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff8156d780)
Location: fs/crypto/keysetup_v1.c:222
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff8156d780-ffffffff8156d8b8: fscrypt_get_direct_key (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffff80001040f9a0)
Location: fs/crypto/keysetup_v1.c:218
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (c05dc26c)
Location: fs/crypto/keysetup_v1.c:218
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (c00000000051d3b4)
Location: fs/crypto/keysetup_v1.c:218
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffe0002b8468)
Location: fs/crypto/keysetup_v1.c:218
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81346bc6)
Location: fs/crypto/keysetup_v1.c:218
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813378a6)
Location: fs/crypto/keysetup_v1.c:218
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81344696)
Location: fs/crypto/keysetup_v1.c:218
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81357976)
Location: fs/crypto/keysetup_v1.c:218
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
