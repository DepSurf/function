# Function: <code>crypto_shash_driver_name</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/crc-t10dif.c (ffffffff815b6162)
Location: include/crypto/hash.h:738
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_transform_show
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
In lib/crc-t10dif.c (ffffffff815c0f92)
Location: include/crypto/hash.h:742
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_transform_show
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
In lib/crc-t10dif.c (ffffffff81628dff)
Location: include/crypto/hash.h:742
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_transform_show
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
In lib/crc-t10dif.c (ffffffff816f9c26)
Location: include/crypto/hash.h:742
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_transform_show
```
```
In lib/crc64-rocksoft.c (ffffffff816fa1f6)
Location: include/crypto/hash.h:742
Inline: True
Inline callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft_transform_show
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
In lib/crc-t10dif.c (ffffffff817ec576)
Location: include/crypto/hash.h:744
Inline: True
```
```
In lib/crc64-rocksoft.c (ffffffff817ecc26)
Location: include/crypto/hash.h:744
Inline: True
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
In fs/verity/hash_algs.c (ffffffff8153c1b4)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In lib/crc-t10dif.c (ffffffff8182c6c6)
Location: include/crypto/hash.h:796
Inline: True
```
```
In lib/crc64-rocksoft.c (ffffffff8182cdd6)
Location: include/crypto/hash.h:796
Inline: True
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
In fs/verity/hash_algs.c (ffffffff81571494)
Location: include/crypto/hash.h:728
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In lib/crc-t10dif.c (ffffffff8187e256)
Location: include/crypto/hash.h:728
Inline: True
```
```
In lib/crc64-rocksoft.c (ffffffff8187e966)
Location: include/crypto/hash.h:728
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/libcrc32c.c (ffffffff8152a750)
Location: include/crypto/hash.h:717
Inline: True
Inline callers:
  - lib/libcrc32c.c:crc32c_impl
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
