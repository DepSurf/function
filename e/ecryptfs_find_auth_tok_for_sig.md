# Function: <code>ecryptfs_find_auth_tok_for_sig</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81308a80)
Location: fs/ecryptfs/keystore.c:559
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81308a80-ffffffff81308ad0: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8133ccb0)
Location: fs/ecryptfs/keystore.c:560
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff8133ccb0-ffffffff8133cd00: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81352a40)
Location: fs/ecryptfs/keystore.c:560
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81352a40-ffffffff81352a90: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81367560)
Location: fs/ecryptfs/keystore.c:560
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81367560-ffffffff813675b2: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8138c1f0)
Location: fs/ecryptfs/keystore.c:567
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff8138c1f0-ffffffff8138c242: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813bb040)
Location: fs/ecryptfs/keystore.c:567
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff813bb040-ffffffff813bb092: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813d4640)
Location: fs/ecryptfs/keystore.c:567
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff813d4640-ffffffff813d4692: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813feff0)
Location: fs/ecryptfs/keystore.c:553
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff813feff0-ffffffff813ff042: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81418ee0)
Location: fs/ecryptfs/keystore.c:553
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81418ee0-ffffffff81418f32: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
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
In fs/ecryptfs/keystore.c (ffffffff81468bc5)
Location: fs/ecryptfs/keystore.c:553
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
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
In fs/ecryptfs/keystore.c (ffffffff81484045)
Location: fs/ecryptfs/keystore.c:553
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
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
In fs/ecryptfs/keystore.c (ffffffff81489ac5)
Location: fs/ecryptfs/keystore.c:554
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
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
In fs/ecryptfs/keystore.c (ffffffff814e12c5)
Location: fs/ecryptfs/keystore.c:554
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
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
In fs/ecryptfs/keystore.c (ffffffff8156f475)
Location: fs/ecryptfs/keystore.c:554
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
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
In fs/ecryptfs/keystore.c (ffffffff81614372)
Location: fs/ecryptfs/keystore.c:554
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
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
In fs/ecryptfs/keystore.c (ffffffff8164c404)
Location: fs/ecryptfs/keystore.c:554
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
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
In fs/ecryptfs/keystore.c (ffffffff81685934)
Location: fs/ecryptfs/keystore.c:554
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffff8000104fa718)
Location: fs/ecryptfs/keystore.c:553
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffff8000104fa718-ffff8000104fa79c: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c06b7e88)
Location: fs/ecryptfs/keystore.c:553
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
c06b7e88-c06b7ee0: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c00000000063cf30)
Location: fs/ecryptfs/keystore.c:553
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
c00000000063cf30-c00000000063cfe0: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffe000368f2e)
Location: fs/ecryptfs/keystore.c:553
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffe000368f2e-ffffffe000368fa0: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814114c0)
Location: fs/ecryptfs/keystore.c:553
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff814114c0-ffffffff81411512: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81401f40)
Location: fs/ecryptfs/keystore.c:553
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81401f40-ffffffff81401f92: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8140e840)
Location: fs/ecryptfs/keystore.c:553
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff8140e840-ffffffff8140e892: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_find_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814244b0)
Location: fs/ecryptfs/keystore.c:553
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff814244b0-ffffffff81424502: ecryptfs_find_auth_tok_for_sig (STB_LOCAL)
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
