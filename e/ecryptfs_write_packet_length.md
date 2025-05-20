# Function: <code>ecryptfs_write_packet_length</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81307d40)
Location: fs/ecryptfs/keystore.c:135
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff81307d40-ffffffff81307da6: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8133e6a8)
Location: fs/ecryptfs/keystore.c:136
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff8133bef0-ffffffff8133bf56: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81354438)
Location: fs/ecryptfs/keystore.c:136
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff81351c80-ffffffff81351ce6: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81369129)
Location: fs/ecryptfs/keystore.c:136
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff813667b0-ffffffff81366816: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8138dd19)
Location: fs/ecryptfs/keystore.c:136
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff8138b430-ffffffff8138b496: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813bc4d5)
Location: fs/ecryptfs/keystore.c:136
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff813ba2f0-ffffffff813ba356: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813d5b45)
Location: fs/ecryptfs/keystore.c:136
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff813d38c0-ffffffff813d3926: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81400386)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff813fe360-ffffffff813fe3c6: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8141a276)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff81418250-ffffffff814182b6: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81466ee4)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:write_tag_66_packet
  - fs/ecryptfs/keystore.c:write_tag_66_packet
  - fs/ecryptfs/keystore.c:write_tag_64_packet
  - fs/ecryptfs/keystore.c:write_tag_64_packet
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff81467f90-ffffffff81467ff6: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814820e4)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:write_tag_66_packet
  - fs/ecryptfs/keystore.c:write_tag_66_packet
  - fs/ecryptfs/keystore.c:write_tag_64_packet
  - fs/ecryptfs/keystore.c:write_tag_64_packet
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff81483410-ffffffff81483476: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81487b48)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff81488ea0-ffffffff81488f06: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814df312)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff814e06a0-ffffffff814e0706: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8156d379)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff8156e810-ffffffff8156e896: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81611a1f)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff81613270-ffffffff816132f6: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81649991)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff8164b2c0-ffffffff8164b344: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81682e61)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff81684790-ffffffff81684814: ecryptfs_write_packet_length (STB_GLOBAL)
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
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffff8000104fbf00)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffff8000104f9b50-ffff8000104f9c00: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c06b9598)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
c06b7338-c06b73bc: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c00000000063ebe0)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
c00000000063c090-c00000000063c12c: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffe00036a560)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffe00036832a-ffffffe0003683ba: ecryptfs_write_packet_length (STB_GLOBAL)
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
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81412856)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff81410830-ffffffff81410896: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814032d6)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff814012b0-ffffffff81401316: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8140fbd6)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff8140dbb0-ffffffff8140dc16: ecryptfs_write_packet_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_write_packet_length(char *dest, size_t size, size_t *packet_size_length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81425846)
Location: fs/ecryptfs/keystore.c:122
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
**Symbols:**

```
ffffffff81423820-ffffffff81423886: ecryptfs_write_packet_length (STB_GLOBAL)
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
