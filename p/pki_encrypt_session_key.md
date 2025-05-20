# Function: <code>pki_encrypt_session_key</code>

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
In fs/ecryptfs/keystore.c (ffffffff8130a3fd)
Location: fs/ecryptfs/keystore.c:1965
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
In fs/ecryptfs/keystore.c (ffffffff8133e668)
Location: fs/ecryptfs/keystore.c:1984
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
In fs/ecryptfs/keystore.c (ffffffff813543f8)
Location: fs/ecryptfs/keystore.c:1984
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
In fs/ecryptfs/keystore.c (ffffffff813690df)
Location: fs/ecryptfs/keystore.c:1984
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
In fs/ecryptfs/keystore.c (ffffffff8138dccf)
Location: fs/ecryptfs/keystore.c:1974
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
In fs/ecryptfs/keystore.c (ffffffff813bc4a1)
Location: fs/ecryptfs/keystore.c:1974
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
In fs/ecryptfs/keystore.c (ffffffff813d5b11)
Location: fs/ecryptfs/keystore.c:1974
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
In fs/ecryptfs/keystore.c (ffffffff81400352)
Location: fs/ecryptfs/keystore.c:1960
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
In fs/ecryptfs/keystore.c (ffffffff8141a242)
Location: fs/ecryptfs/keystore.c:1960
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
int pki_encrypt_session_key(struct key *auth_tok_key, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1960
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
**Symbols:**

```
ffffffff81467890-ffffffff81467a77: pki_encrypt_session_key (STB_LOCAL)
ffffffff81469794-ffffffff8146983d: pki_encrypt_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pki_encrypt_session_key(struct key *auth_tok_key, struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_key_record *key_rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1960
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
**Symbols:**

```
ffffffff81482d20-ffffffff81482f07: pki_encrypt_session_key (STB_LOCAL)
ffffffff81beed21-ffffffff81beedca: pki_encrypt_session_key.cold (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffffffff8148884b)
Location: fs/ecryptfs/keystore.c:1961
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
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
In fs/ecryptfs/keystore.c (ffffffff814e0053)
Location: fs/ecryptfs/keystore.c:1961
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
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
In fs/ecryptfs/keystore.c (ffffffff8156dd50)
Location: fs/ecryptfs/keystore.c:1961
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff816125f8)
Location: fs/ecryptfs/keystore.c:1961
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8164a59a)
Location: fs/ecryptfs/keystore.c:1961
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81683a6a)
Location: fs/ecryptfs/keystore.c:1961
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
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
In fs/ecryptfs/keystore.c (ffff8000104fbed8)
Location: fs/ecryptfs/keystore.c:1960
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
In fs/ecryptfs/keystore.c (c06b9558)
Location: fs/ecryptfs/keystore.c:1960
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
In fs/ecryptfs/keystore.c (c00000000063ebac)
Location: fs/ecryptfs/keystore.c:1960
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
Location: fs/ecryptfs/keystore.c:1960
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
In fs/ecryptfs/keystore.c (ffffffff81412822)
Location: fs/ecryptfs/keystore.c:1960
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
In fs/ecryptfs/keystore.c (ffffffff814032a2)
Location: fs/ecryptfs/keystore.c:1960
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
In fs/ecryptfs/keystore.c (ffffffff8140fba2)
Location: fs/ecryptfs/keystore.c:1960
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
In fs/ecryptfs/keystore.c (ffffffff81425812)
Location: fs/ecryptfs/keystore.c:1960
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
</ul>
