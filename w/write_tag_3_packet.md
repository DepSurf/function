# Function: <code>write_tag_3_packet</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81308360)
Location: fs/ecryptfs/keystore.c:2178
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81308360-ffffffff813089a7: write_tag_3_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8133c520)
Location: fs/ecryptfs/keystore.c:2197
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff8133c520-ffffffff8133cbd1: write_tag_3_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813522b0)
Location: fs/ecryptfs/keystore.c:2197
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff813522b0-ffffffff81352961: write_tag_3_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81366dd0)
Location: fs/ecryptfs/keystore.c:2197
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81366dd0-ffffffff8136748a: write_tag_3_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8138ba50)
Location: fs/ecryptfs/keystore.c:2187
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff8138ba50-ffffffff8138c113: write_tag_3_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2187
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff813ba920-ffffffff813baf7f: write_tag_3_packet (STB_LOCAL)
ffffffff813bccfb-ffffffff813bcd99: write_tag_3_packet.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2187
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff813d3ee0-ffffffff813d457f: write_tag_3_packet (STB_LOCAL)
ffffffff813d6380-ffffffff813d643d: write_tag_3_packet.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2173
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff813fe940-ffffffff813fef3c: write_tag_3_packet (STB_LOCAL)
ffffffff81400c33-ffffffff81400cf9: write_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2173
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81418830-ffffffff81418e2c: write_tag_3_packet (STB_LOCAL)
ffffffff8141ab23-ffffffff8141abe9: write_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2173
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81466a90-ffffffff814670b8: write_tag_3_packet (STB_LOCAL)
ffffffff814695a9-ffffffff8146967c: write_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2173
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81481c90-ffffffff814822b8: write_tag_3_packet (STB_LOCAL)
ffffffff81beead8-ffffffff81beebab: write_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2174
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81487700-ffffffff81487d25: write_tag_3_packet (STB_LOCAL)
ffffffff81be0b93-ffffffff81be0c64: write_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2174
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff814deec0-ffffffff814df52c: write_tag_3_packet (STB_LOCAL)
ffffffff81cd1330-ffffffff81cd1401: write_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2174
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff8156cef0-ffffffff8156d579: write_tag_3_packet (STB_LOCAL)
ffffffff81e844f7-ffffffff81e845bc: write_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81611680)
Location: fs/ecryptfs/keystore.c:2174
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81611680-ffffffff81611dd9: write_tag_3_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2174
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff816495d0-ffffffff81649d80: write_tag_3_packet (STB_LOCAL)
ffffffff820f2107-ffffffff820f2144: write_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2174
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81682aa0-ffffffff81683250: write_tag_3_packet (STB_LOCAL)
ffffffff821cf3e8-ffffffff821cf425: write_tag_3_packet.cold (STB_LOCAL)
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
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffff8000104fa090)
Location: fs/ecryptfs/keystore.c:2173
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffff8000104fa090-ffff8000104fa628: write_tag_3_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c06b77d8)
Location: fs/ecryptfs/keystore.c:2173
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
c06b77d8-c06b7db0: write_tag_3_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c00000000063c6a0)
Location: fs/ecryptfs/keystore.c:2173
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
c00000000063c6a0-c00000000063cdc8: write_tag_3_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffe000368818)
Location: fs/ecryptfs/keystore.c:2173
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffe000368818-ffffffe000368e64: write_tag_3_packet (STB_LOCAL)
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
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2173
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81410e10-ffffffff8141140c: write_tag_3_packet (STB_LOCAL)
ffffffff81413103-ffffffff814131c9: write_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2173
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81401890-ffffffff81401e8c: write_tag_3_packet (STB_LOCAL)
ffffffff81403b83-ffffffff81403c49: write_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2173
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff8140e190-ffffffff8140e78c: write_tag_3_packet (STB_LOCAL)
ffffffff81410483-ffffffff81410549: write_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int write_tag_3_packet(char *dest, size_t *remaining_bytes, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2173
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81423e00-ffffffff814243fc: write_tag_3_packet (STB_LOCAL)
ffffffff814260f3-ffffffff814261b9: write_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
