# Function: <code>write_tag_1_packet</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8130a395)
Location: fs/ecryptfs/keystore.c:2023
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8133e5f2)
Location: fs/ecryptfs/keystore.c:2042
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81354382)
Location: fs/ecryptfs/keystore.c:2042
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81368ec1)
Location: fs/ecryptfs/keystore.c:2042
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8138dab1)
Location: fs/ecryptfs/keystore.c:2032
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813bc453)
Location: fs/ecryptfs/keystore.c:2032
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813d5ac3)
Location: fs/ecryptfs/keystore.c:2032
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81400304)
Location: fs/ecryptfs/keystore.c:2018
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8141a1f4)
Location: fs/ecryptfs/keystore.c:2018
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int write_tag_1_packet(char *dest, size_t *remaining_bytes, struct key *auth_tok_key, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2018
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81467a80-ffffffff81467cb3: write_tag_1_packet (STB_LOCAL)
ffffffff8146983d-ffffffff81469868: write_tag_1_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int write_tag_1_packet(char *dest, size_t *remaining_bytes, struct key *auth_tok_key, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2018
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81482f10-ffffffff81483134: write_tag_1_packet (STB_LOCAL)
ffffffff81beedca-ffffffff81beedf5: write_tag_1_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int write_tag_1_packet(char *dest, size_t *remaining_bytes, struct key *auth_tok_key, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2019
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81488790-ffffffff81488bc8: write_tag_1_packet (STB_LOCAL)
ffffffff81be0ddd-ffffffff81be0e9d: write_tag_1_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int write_tag_1_packet(char *dest, size_t *remaining_bytes, struct key *auth_tok_key, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2019
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff814dff90-ffffffff814e03c9: write_tag_1_packet (STB_LOCAL)
ffffffff81cd157a-ffffffff81cd1634: write_tag_1_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int write_tag_1_packet(char *dest, size_t *remaining_bytes, struct key *auth_tok_key, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2019
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff8156dca0-ffffffff8156e063: write_tag_1_packet (STB_LOCAL)
ffffffff81e84746-ffffffff81e84762: write_tag_1_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int write_tag_1_packet(char *dest, size_t *remaining_bytes, struct key *auth_tok_key, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81612430)
Location: fs/ecryptfs/keystore.c:2019
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff81612430-ffffffff8161281e: write_tag_1_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int write_tag_1_packet(char *dest, size_t *remaining_bytes, struct key *auth_tok_key, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2019
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff8164a3e0-ffffffff8164a830: write_tag_1_packet (STB_LOCAL)
ffffffff820f2167-ffffffff820f2192: write_tag_1_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int write_tag_1_packet(char *dest, size_t *remaining_bytes, struct key *auth_tok_key, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec, size_t *packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2019
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff816838b0-ffffffff81683d00: write_tag_1_packet (STB_LOCAL)
ffffffff821cf448-ffffffff821cf473: write_tag_1_packet.cold (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffff8000104fbe90)
Location: fs/ecryptfs/keystore.c:2018
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
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
In fs/ecryptfs/keystore.c (c06b9518)
Location: fs/ecryptfs/keystore.c:2018
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
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
In fs/ecryptfs/keystore.c (c00000000063eb6c)
Location: fs/ecryptfs/keystore.c:2018
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
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
In fs/ecryptfs/keystore.c (ffffffe00036a41a)
Location: fs/ecryptfs/keystore.c:2018
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff814127d4)
Location: fs/ecryptfs/keystore.c:2018
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff81403254)
Location: fs/ecryptfs/keystore.c:2018
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff8140fb54)
Location: fs/ecryptfs/keystore.c:2018
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff814257c4)
Location: fs/ecryptfs/keystore.c:2018
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
