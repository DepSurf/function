# Function: <code>_copy_from_iter_full_nocache</code>

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
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81466420)
Location: lib/iov_iter.c:664
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81466420-ffffffff81466662: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81492540)
Location: lib/iov_iter.c:664
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81492540-ffffffff81492790: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c71d0)
Location: lib/iov_iter.c:794
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff814c71d0-ffffffff814c7419: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814dbd80)
Location: lib/iov_iter.c:838
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff814dbd80-ffffffff814dbfe1: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8150ad9d-ffffffff8150adb2: _copy_from_iter_full_nocache.cold (STB_LOCAL)
ffffffff81507700-ffffffff81507969: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81525820)
Location: lib/iov_iter.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81525820-ffffffff81525a97: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8158aec0)
Location: lib/iov_iter.c:860
Inline: False
```
**Symbols:**

```
ffffffff8158aec0-ffffffff8158b12e: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a6240)
Location: lib/iov_iter.c:867
Inline: False
```
**Symbols:**

```
ffffffff815a6240-ffffffff815a6486: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815b24c0)
Location: lib/iov_iter.c:910
Inline: False
```
**Symbols:**

```
ffffffff815b24c0-ffffffff815b2a41: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062f978)
Location: lib/iov_iter.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffff80001062f978-ffff80001062fd2c: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d638c)
Location: lib/iov_iter.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
c07d638c-c07d66d8: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d82a0)
Location: lib/iov_iter.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
c0000000007d82a0-c0000000007d87c0: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045ed6e)
Location: lib/iov_iter.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffe00045ed6e-ffffffe00045efce: _copy_from_iter_full_nocache (STB_GLOBAL)
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
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151de00)
Location: lib/iov_iter.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8151de00-ffffffff8151e077: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150e0f0)
Location: lib/iov_iter.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8150e0f0-ffffffff8150e367: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81519e90)
Location: lib/iov_iter.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81519e90-ffffffff8151a107: _copy_from_iter_full_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815336a0)
Location: lib/iov_iter.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff815336a0-ffffffff81533917: _copy_from_iter_full_nocache (STB_GLOBAL)
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
