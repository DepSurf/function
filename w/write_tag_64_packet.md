# Function: <code>write_tag_64_packet</code>

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
In fs/ecryptfs/keystore.c (ffffffff81307e07)
Location: fs/ecryptfs/keystore.c:157
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
In fs/ecryptfs/keystore.c (ffffffff8133bfb7)
Location: fs/ecryptfs/keystore.c:158
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
In fs/ecryptfs/keystore.c (ffffffff81351d47)
Location: fs/ecryptfs/keystore.c:158
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
In fs/ecryptfs/keystore.c (ffffffff81366880)
Location: fs/ecryptfs/keystore.c:158
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
In fs/ecryptfs/keystore.c (ffffffff8138b500)
Location: fs/ecryptfs/keystore.c:158
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
In fs/ecryptfs/keystore.c (ffffffff813ba3ad)
Location: fs/ecryptfs/keystore.c:158
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
In fs/ecryptfs/keystore.c (ffffffff813d397d)
Location: fs/ecryptfs/keystore.c:158
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
In fs/ecryptfs/keystore.c (ffffffff813fe41d)
Location: fs/ecryptfs/keystore.c:144
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
In fs/ecryptfs/keystore.c (ffffffff8141830d)
Location: fs/ecryptfs/keystore.c:144
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
int write_tag_64_packet(char *signature, struct ecryptfs_session_key *session_key, char **packet, size_t *packet_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81466560)
Location: fs/ecryptfs/keystore.c:144
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81466560-ffffffff8146666f: write_tag_64_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int write_tag_64_packet(char *signature, struct ecryptfs_session_key *session_key, char **packet, size_t *packet_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814819f0)
Location: fs/ecryptfs/keystore.c:144
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff814819f0-ffffffff81481aff: write_tag_64_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81487460)
Location: fs/ecryptfs/keystore.c:144
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81487460-ffffffff8148756f: write_tag_64_packet.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814dec00)
Location: fs/ecryptfs/keystore.c:144
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff814dec00-ffffffff814ded0f: write_tag_64_packet.constprop.0 (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffffffff8156cc00)
Location: fs/ecryptfs/keystore.c:144
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8156cc00-ffffffff8156cd1c: write_tag_64_packet.constprop.0 (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffffffff81610ff0)
Location: fs/ecryptfs/keystore.c:144
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81610ff0-ffffffff8161110c: write_tag_64_packet.constprop.0 (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffffffff81648ea0)
Location: fs/ecryptfs/keystore.c:144
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81648ea0-ffffffff81649000: write_tag_64_packet.constprop.0 (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffffffff81682370)
Location: fs/ecryptfs/keystore.c:144
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81682370-ffffffff816824d0: write_tag_64_packet.constprop.0 (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffff8000104f9c44)
Location: fs/ecryptfs/keystore.c:144
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
In fs/ecryptfs/keystore.c (c06b7408)
Location: fs/ecryptfs/keystore.c:144
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
In fs/ecryptfs/keystore.c (c00000000063c188)
Location: fs/ecryptfs/keystore.c:144
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
In fs/ecryptfs/keystore.c (ffffffe0003683f8)
Location: fs/ecryptfs/keystore.c:144
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
In fs/ecryptfs/keystore.c (ffffffff814108ed)
Location: fs/ecryptfs/keystore.c:144
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
In fs/ecryptfs/keystore.c (ffffffff8140136d)
Location: fs/ecryptfs/keystore.c:144
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
In fs/ecryptfs/keystore.c (ffffffff8140dc6d)
Location: fs/ecryptfs/keystore.c:144
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
In fs/ecryptfs/keystore.c (ffffffff814238dd)
Location: fs/ecryptfs/keystore.c:144
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
</ul>
