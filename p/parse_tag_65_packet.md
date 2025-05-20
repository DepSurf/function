# Function: <code>parse_tag_65_packet</code>

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
In fs/ecryptfs/keystore.c (ffffffff81307eb8)
Location: fs/ecryptfs/keystore.c:212
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffff8133c069)
Location: fs/ecryptfs/keystore.c:213
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffff81351df9)
Location: fs/ecryptfs/keystore.c:213
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffff81366929)
Location: fs/ecryptfs/keystore.c:213
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffff8138b5a9)
Location: fs/ecryptfs/keystore.c:213
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffff813ba45d)
Location: fs/ecryptfs/keystore.c:213
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffff813d3a2d)
Location: fs/ecryptfs/keystore.c:213
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffff813fe4cd)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffff814183bd)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_tag_65_packet(struct ecryptfs_session_key *session_key, u8 *cipher_code, struct ecryptfs_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814673f0)
Location: fs/ecryptfs/keystore.c:199
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff814673f0-ffffffff81467693: parse_tag_65_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_tag_65_packet(struct ecryptfs_session_key *session_key, u8 *cipher_code, struct ecryptfs_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81482880)
Location: fs/ecryptfs/keystore.c:199
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81482880-ffffffff81482b23: parse_tag_65_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_tag_65_packet(struct ecryptfs_session_key *session_key, u8 *cipher_code, struct ecryptfs_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814882f0)
Location: fs/ecryptfs/keystore.c:199
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff814882f0-ffffffff81488591: parse_tag_65_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_tag_65_packet(struct ecryptfs_session_key *session_key, u8 *cipher_code, struct ecryptfs_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814dfaf0)
Location: fs/ecryptfs/keystore.c:199
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff814dfaf0-ffffffff814dfd91: parse_tag_65_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8156e380)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8156e380-ffffffff8156e60d: parse_tag_65_packet.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81612d20)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81612d20-ffffffff81612fad: parse_tag_65_packet.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8164aa20)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8164aa20-ffffffff8164acc6: parse_tag_65_packet.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81683ef0)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81683ef0-ffffffff81684196: parse_tag_65_packet.constprop.0 (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffff8000104f9cdc)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (c06b74b8)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (c00000000063c24c)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffe000368498)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffff8141099d)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffff8140141d)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffff8140dd1d)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
In fs/ecryptfs/keystore.c (ffffffff8142398d)
Location: fs/ecryptfs/keystore.c:199
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
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
</ul>
