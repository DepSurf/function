# Function: <code>ecryptfs_keyring_auth_tok_for_sig</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813089b0)
Location: fs/ecryptfs/keystore.c:1627
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff813089b0-ffffffff81308a71: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8133cbe0)
Location: fs/ecryptfs/keystore.c:1632
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff8133cbe0-ffffffff8133cca1: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81352970)
Location: fs/ecryptfs/keystore.c:1632
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff81352970-ffffffff81352a31: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81367490)
Location: fs/ecryptfs/keystore.c:1632
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff81367490-ffffffff81367551: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8138c120)
Location: fs/ecryptfs/keystore.c:1622
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff8138c120-ffffffff8138c1e1: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1622
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff813bcd99-ffffffff813bcdbc: ecryptfs_keyring_auth_tok_for_sig.cold.19 (STB_LOCAL)
ffffffff813baf80-ffffffff813bb034: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1622
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff813d643d-ffffffff813d6460: ecryptfs_keyring_auth_tok_for_sig.cold.19 (STB_LOCAL)
ffffffff813d4580-ffffffff813d4634: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1608
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
```
**Symbols:**

```
ffffffff81400cf9-ffffffff81400d1c: ecryptfs_keyring_auth_tok_for_sig.cold (STB_LOCAL)
ffffffff813fef40-ffffffff813fefec: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1608
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
```
**Symbols:**

```
ffffffff8141abe9-ffffffff8141ac0c: ecryptfs_keyring_auth_tok_for_sig.cold (STB_LOCAL)
ffffffff81418e30-ffffffff81418edc: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1608
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff814699e8-ffffffff81469a0b: ecryptfs_keyring_auth_tok_for_sig.cold (STB_LOCAL)
ffffffff81468000-ffffffff814680bd: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1608
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81beef75-ffffffff81beef98: ecryptfs_keyring_auth_tok_for_sig.cold (STB_LOCAL)
ffffffff81483480-ffffffff8148353d: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1609
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81be101a-ffffffff81be103d: ecryptfs_keyring_auth_tok_for_sig.cold (STB_LOCAL)
ffffffff81488f10-ffffffff81488fcd: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1609
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81cd17b1-ffffffff81cd17d4: ecryptfs_keyring_auth_tok_for_sig.cold (STB_LOCAL)
ffffffff814e0710-ffffffff814e07cd: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1609
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81e848ce-ffffffff81e848ef: ecryptfs_keyring_auth_tok_for_sig.cold (STB_LOCAL)
ffffffff8156e8a0-ffffffff8156e975: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81613310)
Location: fs/ecryptfs/keystore.c:1609
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81613310-ffffffff81613403: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8164b360)
Location: fs/ecryptfs/keystore.c:1609
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff8164b360-ffffffff8164b453: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81684830)
Location: fs/ecryptfs/keystore.c:1609
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81684830-ffffffff81684923: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
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
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffff8000104fa628)
Location: fs/ecryptfs/keystore.c:1608
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
```
**Symbols:**

```
ffff8000104fa628-ffff8000104fa714: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c06b7db0)
Location: fs/ecryptfs/keystore.c:1608
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
```
**Symbols:**

```
c06b7db0-c06b7e88: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c00000000063cdd0)
Location: fs/ecryptfs/keystore.c:1608
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
```
**Symbols:**

```
c00000000063cdd0-c00000000063cf24: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffe000368e64)
Location: fs/ecryptfs/keystore.c:1608
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
```
**Symbols:**

```
ffffffe000368e64-ffffffe000368f2e: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
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
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1608
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
```
**Symbols:**

```
ffffffff814131c9-ffffffff814131ec: ecryptfs_keyring_auth_tok_for_sig.cold (STB_LOCAL)
ffffffff81411410-ffffffff814114bc: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1608
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
```
**Symbols:**

```
ffffffff81403c49-ffffffff81403c6c: ecryptfs_keyring_auth_tok_for_sig.cold (STB_LOCAL)
ffffffff81401e90-ffffffff81401f3c: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1608
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
```
**Symbols:**

```
ffffffff81410549-ffffffff8141056c: ecryptfs_keyring_auth_tok_for_sig.cold (STB_LOCAL)
ffffffff8140e790-ffffffff8140e83c: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_keyring_auth_tok_for_sig(struct key **auth_tok_key, struct ecryptfs_auth_tok **auth_tok, char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1608
Inline: False
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_parse_options
```
**Symbols:**

```
ffffffff814261b9-ffffffff814261dc: ecryptfs_keyring_auth_tok_for_sig.cold (STB_LOCAL)
ffffffff81424400-ffffffff814244ac: ecryptfs_keyring_auth_tok_for_sig (STB_GLOBAL)
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
