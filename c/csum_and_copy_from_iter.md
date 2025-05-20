# Function: <code>csum_and_copy_from_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fcf30)
Location: lib/iov_iter.c:663
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff813fcf30-ffffffff813fd3ea: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81443b90)
Location: lib/iov_iter.c:631
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff81443b90-ffffffff81444039: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81461c70)
Location: lib/iov_iter.c:1053
Inline: False
```
**Symbols:**

```
ffffffff81461c70-ffffffff8146216f: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81468360)
Location: lib/iov_iter.c:1177
Inline: False
```
**Symbols:**

```
ffffffff81468360-ffffffff814687bf: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81494600)
Location: lib/iov_iter.c:1179
Inline: False
```
**Symbols:**

```
ffffffff81494600-ffffffff81494a6e: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c9a40)
Location: lib/iov_iter.c:1309
Inline: False
```
**Symbols:**

```
ffffffff814c9a40-ffffffff814c9ea9: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814ddf90)
Location: lib/iov_iter.c:1387
Inline: False
```
**Symbols:**

```
ffffffff814ddf90-ffffffff814de462: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1404
Inline: False
```
**Symbols:**

```
ffffffff8150ae4a-ffffffff8150ae60: csum_and_copy_from_iter.cold (STB_LOCAL)
ffffffff81509b60-ffffffff8150a062: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81527c80)
Location: lib/iov_iter.c:1404
Inline: False
```
**Symbols:**

```
ffffffff81527c80-ffffffff81528187: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8158bfe0)
Location: lib/iov_iter.c:1439
Inline: False
```
**Symbols:**

```
ffffffff8158bfe0-ffffffff8158c502: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a8920)
Location: lib/iov_iter.c:1446
Inline: False
```
**Symbols:**

```
ffffffff815a8920-ffffffff815a8d2b: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815b0440)
Location: lib/iov_iter.c:1697
Inline: False
```
**Symbols:**

```
ffffffff815b0440-ffffffff815b0bf6: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81617450)
Location: lib/iov_iter.c:1645
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff81617450-ffffffff81617ae8: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1694
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff81e9306c-ffffffff81e930c8: csum_and_copy_from_iter.cold (STB_LOCAL)
ffffffff816e3fa0-ffffffff816e45c0: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1541
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff82078212-ffffffff8207827b: csum_and_copy_from_iter.cold (STB_LOCAL)
ffffffff817d44c0-ffffffff817d4a39: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1171
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff820f85f3-ffffffff820f8639: csum_and_copy_from_iter.cold (STB_LOCAL)
ffffffff81812440-ffffffff818129e2: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff800010632118)
Location: lib/iov_iter.c:1404
Inline: False
```
**Symbols:**

```
ffff800010632118-ffff80001063269c: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d82a0)
Location: lib/iov_iter.c:1404
Inline: False
```
**Symbols:**

```
c07d82a0-c07d8844: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d57c0)
Location: lib/iov_iter.c:1404
Inline: False
```
**Symbols:**

```
c0000000007d57c0-c0000000007d5df4: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe0004607d2)
Location: lib/iov_iter.c:1404
Inline: False
```
**Symbols:**

```
ffffffe0004607d2-ffffffe000460c40: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81520260)
Location: lib/iov_iter.c:1404
Inline: False
```
**Symbols:**

```
ffffffff81520260-ffffffff81520767: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81510550)
Location: lib/iov_iter.c:1404
Inline: False
```
**Symbols:**

```
ffffffff81510550-ffffffff81510a57: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151c2f0)
Location: lib/iov_iter.c:1404
Inline: False
```
**Symbols:**

```
ffffffff8151c2f0-ffffffff8151c7f7: csum_and_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t csum_and_copy_from_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81535b40)
Location: lib/iov_iter.c:1404
Inline: False
```
**Symbols:**

```
ffffffff81535b40-ffffffff8153605e: csum_and_copy_from_iter (STB_GLOBAL)
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
