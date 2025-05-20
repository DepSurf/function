# Function: <code>csum_and_copy_from_iter_full</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81461120)
Location: lib/iov_iter.c:1095
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff81461120-ffffffff81461566: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81466670)
Location: lib/iov_iter.c:1219
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff81466670-ffffffff81466a65: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81492790)
Location: lib/iov_iter.c:1221
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff81492790-ffffffff81492b66: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c7420)
Location: lib/iov_iter.c:1351
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff814c7420-ffffffff814c7808: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814dbff0)
Location: lib/iov_iter.c:1427
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff814dbff0-ffffffff814dc3f3: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff8150adb2-ffffffff8150adc7: csum_and_copy_from_iter_full.cold (STB_LOCAL)
ffffffff81507970-ffffffff81507d72: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81525aa0)
Location: lib/iov_iter.c:1444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff81525aa0-ffffffff81525e9f: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8158b130)
Location: lib/iov_iter.c:1479
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff8158b130-ffffffff8158b540: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a85d0)
Location: lib/iov_iter.c:1485
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff815a85d0-ffffffff815a891c: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815b2a50)
Location: lib/iov_iter.c:1743
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff815b2a50-ffffffff815b30ce: csum_and_copy_from_iter_full (STB_GLOBAL)
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
In net/ipv4/ip_output.c (ffffffff81b4ba45)
Location: include/linux/uio.h:294
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81b5a227)
Location: include/linux/uio.h:294
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81baf5c5)
Location: include/linux/uio.h:294
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
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
In net/ipv4/ip_output.c (ffffffff81cd912f)
Location: include/linux/uio.h:302
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81ce8579)
Location: include/linux/uio.h:302
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/ping.c (ffffffff81d42958)
Location: include/linux/uio.h:302
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
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
In net/ipv4/ip_output.c (ffffffff81e9984f)
Location: include/linux/uio.h:326
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81eabec9)
Location: include/linux/uio.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/ping.c (ffffffff81f0bab0)
Location: include/linux/uio.h:326
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
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
In net/ipv4/ip_output.c (ffffffff81ef8152)
Location: include/linux/uio.h:347
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81f0a689)
Location: include/linux/uio.h:347
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/ping.c (ffffffff81f6b680)
Location: include/linux/uio.h:347
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:7038
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff8220ddbe-ffffffff8220dde3: csum_and_copy_from_iter_full.cold (STB_LOCAL)
ffffffff81ece1d0-ffffffff81ece919: csum_and_copy_from_iter_full (STB_GLOBAL)
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
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062fff8)
Location: lib/iov_iter.c:1444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffff80001062fff8-ffff80001063046c: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d698c)
Location: lib/iov_iter.c:1444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
c07d698c-c07d6ddc: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d3950)
Location: lib/iov_iter.c:1444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
c0000000007d3950-c0000000007d3eec: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045f206)
Location: lib/iov_iter.c:1444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffe00045f206-ffffffe00045f5a4: csum_and_copy_from_iter_full (STB_GLOBAL)
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
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151e080)
Location: lib/iov_iter.c:1444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff8151e080-ffffffff8151e47f: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150e370)
Location: lib/iov_iter.c:1444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff8150e370-ffffffff8150e76f: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151a110)
Location: lib/iov_iter.c:1444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff8151a110-ffffffff8151a50f: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81533920)
Location: lib/iov_iter.c:1444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv4/ping.c:ping_getfrag
```
**Symbols:**

```
ffffffff81533920-ffffffff81533d3d: csum_and_copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
