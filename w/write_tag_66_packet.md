# Function: <code>write_tag_66_packet</code>

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
In fs/ecryptfs/keystore.c (ffffffff8130a41b)
Location: fs/ecryptfs/keystore.c:298
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
In fs/ecryptfs/keystore.c (ffffffff8133e682)
Location: fs/ecryptfs/keystore.c:299
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
In fs/ecryptfs/keystore.c (ffffffff81354412)
Location: fs/ecryptfs/keystore.c:299
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
In fs/ecryptfs/keystore.c (ffffffff813690fd)
Location: fs/ecryptfs/keystore.c:299
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
In fs/ecryptfs/keystore.c (ffffffff8138dced)
Location: fs/ecryptfs/keystore.c:299
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
In fs/ecryptfs/keystore.c (ffffffff813bc4bc)
Location: fs/ecryptfs/keystore.c:299
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
In fs/ecryptfs/keystore.c (ffffffff813d5b2c)
Location: fs/ecryptfs/keystore.c:299
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
In fs/ecryptfs/keystore.c (ffffffff8140036d)
Location: fs/ecryptfs/keystore.c:285
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
In fs/ecryptfs/keystore.c (ffffffff8141a25d)
Location: fs/ecryptfs/keystore.c:285
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int write_tag_66_packet(char *signature, u8 cipher_code, struct ecryptfs_crypt_stat *crypt_stat, char **packet, size_t *packet_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81466670)
Location: fs/ecryptfs/keystore.c:285
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
```
**Symbols:**

```
ffffffff81466670-ffffffff814667f5: write_tag_66_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int write_tag_66_packet(char *signature, u8 cipher_code, struct ecryptfs_crypt_stat *crypt_stat, char **packet, size_t *packet_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81481b00)
Location: fs/ecryptfs/keystore.c:285
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
```
**Symbols:**

```
ffffffff81481b00-ffffffff81481c85: write_tag_66_packet (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffffffff81487570)
Location: fs/ecryptfs/keystore.c:285
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
**Symbols:**

```
ffffffff81487570-ffffffff814876f5: write_tag_66_packet.constprop.0 (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffffffff814ded10)
Location: fs/ecryptfs/keystore.c:285
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
**Symbols:**

```
ffffffff814ded10-ffffffff814deebc: write_tag_66_packet.constprop.0 (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffffffff8156cd20)
Location: fs/ecryptfs/keystore.c:285
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
**Symbols:**

```
ffffffff8156cd20-ffffffff8156ceeb: write_tag_66_packet.constprop.0 (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffffffff81611120)
Location: fs/ecryptfs/keystore.c:285
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
**Symbols:**

```
ffffffff81611120-ffffffff816112eb: write_tag_66_packet.constprop.0 (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffffffff81649010)
Location: fs/ecryptfs/keystore.c:285
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
**Symbols:**

```
ffffffff81649010-ffffffff81649240: write_tag_66_packet.constprop.0 (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffffffff816824e0)
Location: fs/ecryptfs/keystore.c:285
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
**Symbols:**

```
ffffffff816824e0-ffffffff81682710: write_tag_66_packet.constprop.0 (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffff8000104fbeec)
Location: fs/ecryptfs/keystore.c:285
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
In fs/ecryptfs/keystore.c (c06b9588)
Location: fs/ecryptfs/keystore.c:285
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
In fs/ecryptfs/keystore.c (c00000000063ebcc)
Location: fs/ecryptfs/keystore.c:285
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
In fs/ecryptfs/keystore.c (ffffffe00036a422)
Location: fs/ecryptfs/keystore.c:285
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
In fs/ecryptfs/keystore.c (ffffffff8141283d)
Location: fs/ecryptfs/keystore.c:285
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
In fs/ecryptfs/keystore.c (ffffffff814032bd)
Location: fs/ecryptfs/keystore.c:285
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
In fs/ecryptfs/keystore.c (ffffffff8140fbbd)
Location: fs/ecryptfs/keystore.c:285
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
In fs/ecryptfs/keystore.c (ffffffff8142582d)
Location: fs/ecryptfs/keystore.c:285
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
