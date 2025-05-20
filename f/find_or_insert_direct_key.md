# Function: <code>find_or_insert_direct_key</code>

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
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff8134e280)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff8134e280-ffffffff8134e389: find_or_insert_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81394350)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff81394350-ffffffff813944a3: find_or_insert_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813a5810)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff813a5810-ffffffff813a5996: find_or_insert_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813ac870)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff813ac870-ffffffff813ac9f2: find_or_insert_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff813fc1e0-ffffffff813fc36b: find_or_insert_direct_key (STB_LOCAL)
ffffffff81cc6770-ffffffff81cc678d: find_or_insert_direct_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff8146f660-ffffffff8146f7ef: find_or_insert_direct_key (STB_LOCAL)
ffffffff81e78bcb-ffffffff81e78bee: find_or_insert_direct_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:180
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff81500df0-ffffffff81500f86: find_or_insert_direct_key (STB_LOCAL)
ffffffff8206a6fc-ffffffff8206a719: find_or_insert_direct_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:180
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff81538480-ffffffff81538616: find_or_insert_direct_key (STB_LOCAL)
ffffffff820ea50a-ffffffff820ea527: find_or_insert_direct_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_inode_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:180
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff8156d5d0-ffffffff8156d766: find_or_insert_direct_key (STB_LOCAL)
ffffffff821c7088-ffffffff821c70a5: find_or_insert_direct_key.cold (STB_LOCAL)
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
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffff80001040f760)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffff80001040f760-ffff80001040f8dc: find_or_insert_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (c05dc028)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
c05dc028-c05dc174: find_or_insert_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (c00000000051cde0)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
c00000000051cde0-c00000000051d00c: find_or_insert_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffe0002b81c6)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffe0002b81c6-ffffffe0002b8380: find_or_insert_direct_key (STB_LOCAL)
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
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81346860)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff81346860-ffffffff81346969: find_or_insert_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81337540)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff81337540-ffffffff81337649: find_or_insert_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81344330)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff81344330-ffffffff81344439: find_or_insert_direct_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fscrypt_direct_key *find_or_insert_direct_key(struct fscrypt_direct_key *to_insert, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81357610)
Location: fs/crypto/keysetup_v1.c:179
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff81357610-ffffffff81357715: find_or_insert_direct_key (STB_LOCAL)
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
