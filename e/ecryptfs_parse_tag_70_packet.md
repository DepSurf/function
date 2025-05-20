# Function: <code>ecryptfs_parse_tag_70_packet</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81309200)
Location: fs/ecryptfs/keystore.c:913
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81309200-ffffffff813097d1: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8133d410)
Location: fs/ecryptfs/keystore.c:908
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff8133d410-ffffffff8133da5b: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813531a0)
Location: fs/ecryptfs/keystore.c:908
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff813531a0-ffffffff813537eb: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81367cd0)
Location: fs/ecryptfs/keystore.c:908
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81367cd0-ffffffff81368336: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8138c910)
Location: fs/ecryptfs/keystore.c:906
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff8138c910-ffffffff8138cf1d: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:906
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff813bcf49-ffffffff813bd128: ecryptfs_parse_tag_70_packet.cold.21 (STB_LOCAL)
ffffffff813bb600-ffffffff813bba83: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:906
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff813d65cc-ffffffff813d678d: ecryptfs_parse_tag_70_packet.cold.21 (STB_LOCAL)
ffffffff813d4c30-ffffffff813d5110: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:891
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81400ed4-ffffffff814010fb: ecryptfs_parse_tag_70_packet.cold (STB_LOCAL)
ffffffff813ff550-ffffffff813ff973: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:891
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff8141adc4-ffffffff8141afeb: ecryptfs_parse_tag_70_packet.cold (STB_LOCAL)
ffffffff81419440-ffffffff81419863: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:891
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81469bc1-ffffffff81469dcd: ecryptfs_parse_tag_70_packet.cold (STB_LOCAL)
ffffffff81468650-ffffffff81468ace: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:891
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81bef14e-ffffffff81bef35a: ecryptfs_parse_tag_70_packet.cold (STB_LOCAL)
ffffffff81483ad0-ffffffff81483f4c: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:892
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81be11f3-ffffffff81be13fc: ecryptfs_parse_tag_70_packet.cold (STB_LOCAL)
ffffffff81489550-ffffffff814899c4: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:892
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81cd198a-ffffffff81cd1b93: ecryptfs_parse_tag_70_packet.cold (STB_LOCAL)
ffffffff814e0d50-ffffffff814e11c4: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:892
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81e84a9e-ffffffff81e84cc7: ecryptfs_parse_tag_70_packet.cold (STB_LOCAL)
ffffffff8156eef0-ffffffff8156f34e: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81613420)
Location: fs/ecryptfs/keystore.c:892
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81613420-ffffffff81613aa8: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8164b470)
Location: fs/ecryptfs/keystore.c:892
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff8164b470-ffffffff8164bb0f: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81684940)
Location: fs/ecryptfs/keystore.c:892
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81684940-ffffffff8168500e: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
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
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffff8000104fadd8)
Location: fs/ecryptfs/keystore.c:891
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffff8000104fadd8-ffff8000104fb3c4: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c06b84e4)
Location: fs/ecryptfs/keystore.c:891
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
c06b84e4-c06b8a8c: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c00000000063d720)
Location: fs/ecryptfs/keystore.c:891
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
c00000000063d720-c00000000063de18: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffe000369508)
Location: fs/ecryptfs/keystore.c:891
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffe000369508-ffffffe000369a3c: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
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
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:891
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff814133a4-ffffffff814135cb: ecryptfs_parse_tag_70_packet.cold (STB_LOCAL)
ffffffff81411a20-ffffffff81411e43: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:891
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81403e24-ffffffff8140404b: ecryptfs_parse_tag_70_packet.cold (STB_LOCAL)
ffffffff814024a0-ffffffff814028c3: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:891
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81410724-ffffffff8141094b: ecryptfs_parse_tag_70_packet.cold (STB_LOCAL)
ffffffff8140eda0-ffffffff8140f1c3: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_parse_tag_70_packet(char **filename, size_t *filename_size, size_t *packet_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, char *data, size_t max_packet_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:891
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
```
**Symbols:**

```
ffffffff81426394-ffffffff814265bb: ecryptfs_parse_tag_70_packet.cold (STB_LOCAL)
ffffffff81424a10-ffffffff81424e33: ecryptfs_parse_tag_70_packet (STB_GLOBAL)
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
