# Function: <code>parse_tag_3_packet</code>

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
In fs/ecryptfs/keystore.c (ffffffff8130981b)
Location: fs/ecryptfs/keystore.c:1374
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff8133da9a)
Location: fs/ecryptfs/keystore.c:1379
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff8135382a)
Location: fs/ecryptfs/keystore.c:1379
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff81368468)
Location: fs/ecryptfs/keystore.c:1379
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff8138d048)
Location: fs/ecryptfs/keystore.c:1369
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff813bbbb8)
Location: fs/ecryptfs/keystore.c:1369
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff813d5238)
Location: fs/ecryptfs/keystore.c:1369
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff813ffaa8)
Location: fs/ecryptfs/keystore.c:1355
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff81419998)
Location: fs/ecryptfs/keystore.c:1355
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int parse_tag_3_packet(struct ecryptfs_crypt_stat *crypt_stat, unsigned char *data, struct list_head *auth_tok_list, struct ecryptfs_auth_tok **new_auth_tok, size_t *packet_size, size_t max_packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1355
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81467150-ffffffff814673e3: parse_tag_3_packet (STB_LOCAL)
ffffffff8146967c-ffffffff81469756: parse_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int parse_tag_3_packet(struct ecryptfs_crypt_stat *crypt_stat, unsigned char *data, struct list_head *auth_tok_list, struct ecryptfs_auth_tok **new_auth_tok, size_t *packet_size, size_t max_packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1355
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff814825e0-ffffffff81482873: parse_tag_3_packet (STB_LOCAL)
ffffffff81beec09-ffffffff81beece3: parse_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int parse_tag_3_packet(struct ecryptfs_crypt_stat *crypt_stat, unsigned char *data, struct list_head *auth_tok_list, struct ecryptfs_auth_tok **new_auth_tok, size_t *packet_size, size_t max_packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1356
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81488050-ffffffff814882e4: parse_tag_3_packet (STB_LOCAL)
ffffffff81be0cc2-ffffffff81be0d9c: parse_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int parse_tag_3_packet(struct ecryptfs_crypt_stat *crypt_stat, unsigned char *data, struct list_head *auth_tok_list, struct ecryptfs_auth_tok **new_auth_tok, size_t *packet_size, size_t max_packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1356
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff814df850-ffffffff814dfae4: parse_tag_3_packet (STB_LOCAL)
ffffffff81cd145f-ffffffff81cd1539: parse_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int parse_tag_3_packet(struct ecryptfs_crypt_stat *crypt_stat, unsigned char *data, struct list_head *auth_tok_list, struct ecryptfs_auth_tok **new_auth_tok, size_t *packet_size, size_t max_packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1356
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff8156d8e0-ffffffff8156dba1: parse_tag_3_packet (STB_LOCAL)
ffffffff81e84618-ffffffff81e846c1: parse_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int parse_tag_3_packet(struct ecryptfs_crypt_stat *crypt_stat, unsigned char *data, struct list_head *auth_tok_list, struct ecryptfs_auth_tok **new_auth_tok, size_t *packet_size, size_t max_packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1356
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81611ea0-ffffffff81612284: parse_tag_3_packet (STB_LOCAL)
ffffffff820724f3-ffffffff82072516: parse_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int parse_tag_3_packet(struct ecryptfs_crypt_stat *crypt_stat, unsigned char *data, struct list_head *auth_tok_list, struct ecryptfs_auth_tok **new_auth_tok, size_t *packet_size, size_t max_packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1356
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81649e50-ffffffff8164a234: parse_tag_3_packet (STB_LOCAL)
ffffffff820f2144-ffffffff820f2167: parse_tag_3_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int parse_tag_3_packet(struct ecryptfs_crypt_stat *crypt_stat, unsigned char *data, struct list_head *auth_tok_list, struct ecryptfs_auth_tok **new_auth_tok, size_t *packet_size, size_t max_packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1356
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81683320-ffffffff81683704: parse_tag_3_packet (STB_LOCAL)
ffffffff821cf425-ffffffff821cf448: parse_tag_3_packet.cold (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffff8000104fb71c)
Location: fs/ecryptfs/keystore.c:1355
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (c06b8d60)
Location: fs/ecryptfs/keystore.c:1355
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (c00000000063e204)
Location: fs/ecryptfs/keystore.c:1355
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffe000369a6e)
Location: fs/ecryptfs/keystore.c:1355
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff81411f78)
Location: fs/ecryptfs/keystore.c:1355
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff814029f8)
Location: fs/ecryptfs/keystore.c:1355
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff8140f2f8)
Location: fs/ecryptfs/keystore.c:1355
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
In fs/ecryptfs/keystore.c (ffffffff81424f68)
Location: fs/ecryptfs/keystore.c:1355
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
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
