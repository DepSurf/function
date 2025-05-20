# Function: <code>parse_tag_67_packet</code>

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
In fs/ecryptfs/keystore.c (ffffffff8130a53c)
Location: fs/ecryptfs/keystore.c:359
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
In fs/ecryptfs/keystore.c (ffffffff8133e7a5)
Location: fs/ecryptfs/keystore.c:360
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
In fs/ecryptfs/keystore.c (ffffffff81354535)
Location: fs/ecryptfs/keystore.c:360
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
In fs/ecryptfs/keystore.c (ffffffff81369231)
Location: fs/ecryptfs/keystore.c:360
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
In fs/ecryptfs/keystore.c (ffffffff8138de21)
Location: fs/ecryptfs/keystore.c:360
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
In fs/ecryptfs/keystore.c (ffffffff813bc5df)
Location: fs/ecryptfs/keystore.c:360
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
In fs/ecryptfs/keystore.c (ffffffff813d5c4f)
Location: fs/ecryptfs/keystore.c:360
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
In fs/ecryptfs/keystore.c (ffffffff8140048e)
Location: fs/ecryptfs/keystore.c:346
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
In fs/ecryptfs/keystore.c (ffffffff8141a37e)
Location: fs/ecryptfs/keystore.c:346
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81467950)
Location: fs/ecryptfs/keystore.c:346
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81482de0)
Location: fs/ecryptfs/keystore.c:346
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
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
In fs/ecryptfs/keystore.c (ffffffff814888d6)
Location: fs/ecryptfs/keystore.c:346
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
In fs/ecryptfs/keystore.c (ffffffff814e00da)
Location: fs/ecryptfs/keystore.c:346
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int parse_tag_67_packet(struct ecryptfs_key_record *key_rec, struct ecryptfs_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:346
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
**Symbols:**

```
ffffffff8156dbb0-ffffffff8156dc9c: parse_tag_67_packet (STB_LOCAL)
ffffffff81e846c1-ffffffff81e84746: parse_tag_67_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_tag_67_packet(struct ecryptfs_key_record *key_rec, struct ecryptfs_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff816122a0)
Location: fs/ecryptfs/keystore.c:346
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
**Symbols:**

```
ffffffff816122a0-ffffffff81612412: parse_tag_67_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_tag_67_packet(struct ecryptfs_key_record *key_rec, struct ecryptfs_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8164a250)
Location: fs/ecryptfs/keystore.c:346
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
**Symbols:**

```
ffffffff8164a250-ffffffff8164a3c2: parse_tag_67_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_tag_67_packet(struct ecryptfs_key_record *key_rec, struct ecryptfs_message *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81683720)
Location: fs/ecryptfs/keystore.c:346
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
```
**Symbols:**

```
ffffffff81683720-ffffffff81683892: parse_tag_67_packet (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffff8000104fbfe0)
Location: fs/ecryptfs/keystore.c:346
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
In fs/ecryptfs/keystore.c (c06b96a4)
Location: fs/ecryptfs/keystore.c:346
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
In fs/ecryptfs/keystore.c (c00000000063ece4)
Location: fs/ecryptfs/keystore.c:346
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
In fs/ecryptfs/keystore.c (ffffffe00036a63c)
Location: fs/ecryptfs/keystore.c:346
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
In fs/ecryptfs/keystore.c (ffffffff8141295e)
Location: fs/ecryptfs/keystore.c:346
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
In fs/ecryptfs/keystore.c (ffffffff814033de)
Location: fs/ecryptfs/keystore.c:346
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
In fs/ecryptfs/keystore.c (ffffffff8140fcde)
Location: fs/ecryptfs/keystore.c:346
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
In fs/ecryptfs/keystore.c (ffffffff8142594e)
Location: fs/ecryptfs/keystore.c:346
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
