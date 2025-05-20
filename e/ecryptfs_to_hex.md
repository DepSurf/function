# Function: <code>ecryptfs_to_hex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ecryptfs_to_hex(char *dst, char *src, size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81305470)
Location: fs/ecryptfs/crypto.c:50
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81305470-ffffffff813054c4: ecryptfs_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ecryptfs_to_hex(char *dst, char *src, size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81339710)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81339710-ffffffff8133976c: ecryptfs_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ecryptfs_to_hex(char *dst, char *src, size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8134f4b0)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff8134f4b0-ffffffff8134f50c: ecryptfs_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ecryptfs_to_hex(char *dst, char *src, size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81363f50)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81363f50-ffffffff81363fad: ecryptfs_to_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8138d286)
Location: fs/ecryptfs/ecryptfs_kernel.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff8138e96a)
Location: fs/ecryptfs/ecryptfs_kernel.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813bbdf0)
Location: fs/ecryptfs/ecryptfs_kernel.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff813bd9a3)
Location: fs/ecryptfs/ecryptfs_kernel.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813d5470)
Location: fs/ecryptfs/ecryptfs_kernel.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff813d6fe3)
Location: fs/ecryptfs/ecryptfs_kernel.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813ffcdd)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff814019a3)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81419bcd)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff8141b893)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81468df8)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff8146a353)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81484278)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff81484dc3)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81489d06)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff8148a873)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814e1506)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff814e2073)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8156f6b5)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff815702c9)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81614634)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff816151c9)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8164c694)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff8164d259)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81685bc4)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff81686789)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffff8000104fb680)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffff8000104fccfc)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c06b8c44)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (c06ba360)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c00000000063e160)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (c00000000063fe20)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffe000369c7c)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffe00036b3b6)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814121ad)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff81413e73)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81402c2d)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff814048f3)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8140f52d)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff814111f3)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8142519d)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In fs/ecryptfs/debug.c (ffffffff81426e63)
Location: fs/ecryptfs/ecryptfs_kernel.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
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
</ul>
