# Function: <code>hash_get_stat</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:569
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/hash.h:569
Inline: True
```
```
In crypto/shash.c (ffffffff81746c35)
Location: include/crypto/hash.h:569
Inline: True
Inline callers:
  - crypto/shash.c:hash_prepare_alg
```
```
In crypto/gcm.c (0)
Location: include/crypto/hash.h:569
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/crypto/hash.h:569
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/crypto/hash.h:569
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/crypto/hash.h:569
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/crypto/hash.h:569
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
In crypto/ahash.c (0)
Location: crypto/hash.h:15
Inline: True
```
```
In crypto/shash.c (ffffffff81788ac5)
Location: crypto/hash.h:15
Inline: True
Inline callers:
  - crypto/shash.c:hash_prepare_alg
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
