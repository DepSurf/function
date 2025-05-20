# Function: <code>_copy_from_iter_nocache</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81467c20)
Location: lib/iov_iter.c:623
Inline: False
```
**Symbols:**

```
ffffffff81467c20-ffffffff81467f0f: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81493ed0)
Location: lib/iov_iter.c:623
Inline: False
```
**Symbols:**

```
ffffffff81493ed0-ffffffff8149419d: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c91e0)
Location: lib/iov_iter.c:739
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
```
**Symbols:**

```
ffffffff814c91e0-ffffffff814c94a6: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814dd970)
Location: lib/iov_iter.c:783
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffffffff814dd970-ffffffff814ddc73: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:784
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffffffff8150ae0c-ffffffff8150ae22: _copy_from_iter_nocache.cold (STB_LOCAL)
ffffffff81508c00-ffffffff81508f87: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81527560)
Location: lib/iov_iter.c:784
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffffffff81527560-ffffffff815278ee: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8158a160)
Location: lib/iov_iter.c:805
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffffffff8158a160-ffffffff8158a4af: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a6ec0)
Location: lib/iov_iter.c:812
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffffffff815a6ec0-ffffffff815a7192: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815aecd0)
Location: lib/iov_iter.c:851
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffffffff815aecd0-ffffffff815af3ab: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816161d0)
Location: lib/iov_iter.c:731
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffffffff816161d0-ffffffff81616749: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:783
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
**Symbols:**

```
ffffffff81e930c8-ffffffff81e93118: _copy_from_iter_nocache.cold (STB_LOCAL)
ffffffff816e45c0-ffffffff816e4c3b: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:643
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
**Symbols:**

```
ffffffff82078104-ffffffff8207814f: _copy_from_iter_nocache.cold (STB_LOCAL)
ffffffff817d2f90-ffffffff817d34b3: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:399
Inline: False
Direct callers:
  - kernel/trace/trace_events_user.c:user_event_perf
  - kernel/trace/trace_events_user.c:user_event_ftrace
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
**Symbols:**

```
ffffffff820f849a-ffffffff820f84e0: _copy_from_iter_nocache.cold (STB_LOCAL)
ffffffff81811150-ffffffff81811636: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:271
Inline: False
Direct callers:
  - kernel/trace/trace_events_user.c:user_event_perf
  - kernel/trace/trace_events_user.c:user_event_ftrace
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff821d621d-ffffffff821d6232: _copy_from_iter_nocache.cold (STB_LOCAL)
ffffffff81856830-ffffffff81856d56: _copy_from_iter_nocache (STB_GLOBAL)
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
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff800010631cd0)
Location: lib/iov_iter.c:784
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffff800010631cd0-ffff800010632114: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d7e48)
Location: lib/iov_iter.c:784
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
c07d7e48-c07d82a0: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d77f0)
Location: lib/iov_iter.c:784
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
c0000000007d77f0-c0000000007d7dfc: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe000460048)
Location: lib/iov_iter.c:784
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffffffe000460048-ffffffe000460330: _copy_from_iter_nocache (STB_GLOBAL)
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
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151fb40)
Location: lib/iov_iter.c:784
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffffffff8151fb40-ffffffff8151fece: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150fe30)
Location: lib/iov_iter.c:784
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffffffff8150fe30-ffffffff815101be: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151bbd0)
Location: lib/iov_iter.c:784
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffffffff8151bbd0-ffffffff8151bf5e: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t _copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81535420)
Location: lib/iov_iter.c:784
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
**Symbols:**

```
ffffffff81535420-ffffffff815357ae: _copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
