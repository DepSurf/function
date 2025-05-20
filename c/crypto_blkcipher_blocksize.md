# Function: <code>crypto_blkcipher_blocksize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81307730)
Location: include/linux/crypto.h:1211
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff81308bac)
Location: include/linux/crypto.h:1211
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/crypto.h:1211
Inline: True
```
```
In crypto/blkcipher.c (ffffffff813a18fa)
Location: include/linux/crypto.h:1211
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt_block
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
In crypto/blkcipher.c (ffffffff813dde4c)
Location: include/linux/crypto.h:1168
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (ffffffff813f56fc)
Location: include/linux/crypto.h:1171
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (ffffffff8140199c)
Location: include/linux/crypto.h:1171
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (ffffffff81429fbc)
Location: include/linux/crypto.h:1219
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (ffffffff8145ccfc)
Location: include/linux/crypto.h:1232
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (ffffffff8147a58c)
Location: include/linux/crypto.h:1417
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (ffffffff814a85bc)
Location: include/linux/crypto.h:1414
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (ffffffff814c322c)
Location: include/linux/crypto.h:1414
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In crypto/blkcipher.c (ffff8000105bd9c0)
Location: include/linux/crypto.h:1414
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (c076b834)
Location: include/linux/crypto.h:1414
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (c000000000744e00)
Location: include/linux/crypto.h:1414
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (ffffffe000402f90)
Location: include/linux/crypto.h:1414
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (ffffffff814bb80c)
Location: include/linux/crypto.h:1414
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (ffffffff814ac22c)
Location: include/linux/crypto.h:1414
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (ffffffff814b789c)
Location: include/linux/crypto.h:1414
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
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
In crypto/blkcipher.c (ffffffff814d037c)
Location: include/linux/crypto.h:1414
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
</details>
</li>
</ul>

## Differences
