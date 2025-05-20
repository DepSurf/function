# Function: <code>sock_zerocopy_realloc</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81833730)
Location: net/core/skbuff.c:971
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81833730-ffffffff81833808: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187dbb0)
Location: net/core/skbuff.c:972
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8187dbb0-ffffffff8187dc6f: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189e780)
Location: net/core/skbuff.c:974
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8189e780-ffffffff8189e83f: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e9000)
Location: net/core/skbuff.c:1132
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff818e9000-ffffffff818e90c1: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191b160)
Location: net/core/skbuff.c:1132
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8191b160-ffffffff8191b221: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819edec0)
Location: net/core/skbuff.c:1131
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff819edec0-ffffffff819edff4: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819edb60)
Location: net/core/skbuff.c:1142
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff819edb60-ffffffff819edc94: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb55e0)
Location: net/core/skbuff.c:1132
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffff800010bb55e0-ffff800010bb5704: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd2690)
Location: net/core/skbuff.c:1132
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
```
**Symbols:**

```
c0cd2690-c0cd27b4: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8c740)
Location: net/core/skbuff.c:1132
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
c000000000c8c740-c000000000c8c8e8: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe0007455da)
Location: net/core/skbuff.c:1132
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffe0007455da-ffffffe0007456a4: sock_zerocopy_realloc (STB_GLOBAL)
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
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bb160)
Location: net/core/skbuff.c:1132
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff818bb160-ffffffff818bb221: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818750a0)
Location: net/core/skbuff.c:1132
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff818750a0-ffffffff81875161: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190c160)
Location: net/core/skbuff.c:1132
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8190c160-ffffffff8190c221: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ubuf_info *sock_zerocopy_realloc(struct sock *sk, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192d290)
Location: net/core/skbuff.c:1132
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8192d290-ffffffff8192d351: sock_zerocopy_realloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
