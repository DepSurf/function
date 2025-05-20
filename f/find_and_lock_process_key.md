# Function: <code>find_and_lock_process_key</code>

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
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyinfo.c (0)
Location: fs/crypto/keyinfo.c:74
Inline: False
```
**Symbols:**

```
ffffffff812fb760-ffffffff812fb83b: find_and_lock_process_key (STB_LOCAL)
ffffffff812fbfdb-ffffffff812fc020: find_and_lock_process_key.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyinfo.c (0)
Location: fs/crypto/keyinfo.c:80
Inline: False
```
**Symbols:**

```
ffffffff81310b70-ffffffff81310c4b: find_and_lock_process_key (STB_LOCAL)
ffffffff813117fb-ffffffff81311840: find_and_lock_process_key.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyinfo.c (0)
Location: fs/crypto/keyinfo.c:79
Inline: False
```
**Symbols:**

```
ffffffff813380b0-ffffffff81338192: find_and_lock_process_key (STB_LOCAL)
ffffffff81338cef-ffffffff81338d36: find_and_lock_process_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff8134e160-ffffffff8134e242: find_and_lock_process_key (STB_LOCAL)
ffffffff8134e823-ffffffff8134e86a: find_and_lock_process_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff81394040-ffffffff81394122: find_and_lock_process_key (STB_LOCAL)
ffffffff8139477e-ffffffff813947c5: find_and_lock_process_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff813a5500-ffffffff813a55e2: find_and_lock_process_key (STB_LOCAL)
ffffffff81beaff7-ffffffff81beb03e: find_and_lock_process_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff813ac5e0-ffffffff813ac6c2: find_and_lock_process_key (STB_LOCAL)
ffffffff81bdd050-ffffffff81bdd097: find_and_lock_process_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff813fbf50-ffffffff813fc032: find_and_lock_process_key (STB_LOCAL)
ffffffff81cc6729-ffffffff81cc6770: find_and_lock_process_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff8146f350-ffffffff8146f455: find_and_lock_process_key (STB_LOCAL)
ffffffff81e78b86-ffffffff81e78bcb: find_and_lock_process_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81500a90)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff81500a90-ffffffff81500bca: find_and_lock_process_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81538120)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff81538120-ffffffff8153825a: find_and_lock_process_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff8156d270)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff8156d270-ffffffff8156d3aa: find_and_lock_process_key (STB_LOCAL)
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
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffff80001040f408)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffff80001040f408-ffff80001040f544: find_and_lock_process_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (c05dbecc)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
c05dbecc-c05dbff8: find_and_lock_process_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (c00000000051cbe0)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
c00000000051cbe0-c00000000051cd74: find_and_lock_process_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffe0002b801a)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffe0002b801a-ffffffe0002b8128: find_and_lock_process_key (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff81346740-ffffffff81346822: find_and_lock_process_key (STB_LOCAL)
ffffffff81346e03-ffffffff81346e4a: find_and_lock_process_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff81337420-ffffffff81337502: find_and_lock_process_key (STB_LOCAL)
ffffffff81337ae3-ffffffff81337b2a: find_and_lock_process_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff81344210-ffffffff813442f2: find_and_lock_process_key (STB_LOCAL)
ffffffff813448d3-ffffffff8134491a: find_and_lock_process_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct key *find_and_lock_process_key(const char *prefix, const u8 *descriptor, unsigned int min_keysize, const struct fscrypt_key **payload_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff813574f0-ffffffff813575d2: find_and_lock_process_key (STB_LOCAL)
ffffffff81357bb3-ffffffff81357bfa: find_and_lock_process_key.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
