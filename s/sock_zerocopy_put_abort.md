# Function: <code>sock_zerocopy_put_abort</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81833f10)
Location: net/core/skbuff.c:1091
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81833f10-ffffffff81833f37: sock_zerocopy_put_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187e3a0)
Location: net/core/skbuff.c:1092
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8187e3a0-ffffffff8187e3c6: sock_zerocopy_put_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189ef60)
Location: net/core/skbuff.c:1094
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8189ef60-ffffffff8189ef8d: sock_zerocopy_put_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e9790)
Location: net/core/skbuff.c:1256
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff818e9790-ffffffff818e97bb: sock_zerocopy_put_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191b900)
Location: net/core/skbuff.c:1256
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8191b900-ffffffff8191b92b: sock_zerocopy_put_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed830)
Location: net/core/skbuff.c:1255
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff819ed830-ffffffff819ed85b: sock_zerocopy_put_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed4f0)
Location: net/core/skbuff.c:1266
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff819ed4f0-ffffffff819ed51b: sock_zerocopy_put_abort (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb5e90)
Location: net/core/skbuff.c:1256
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffff800010bb5e90-ffff800010bb5f18: sock_zerocopy_put_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd2e44)
Location: net/core/skbuff.c:1256
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv6/ip6_output.c:__ip6_append_data
```
**Symbols:**

```
c0cd2e44-c0cd2e9c: sock_zerocopy_put_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8d3c0)
Location: net/core/skbuff.c:1256
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
c000000000c8d3c0-c000000000c8d408: sock_zerocopy_put_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000745d3a)
Location: net/core/skbuff.c:1256
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffe000745d3a-ffffffe000745da4: sock_zerocopy_put_abort (STB_GLOBAL)
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
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bb900)
Location: net/core/skbuff.c:1256
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff818bb900-ffffffff818bb92b: sock_zerocopy_put_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81875840)
Location: net/core/skbuff.c:1256
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81875840-ffffffff8187586b: sock_zerocopy_put_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190c900)
Location: net/core/skbuff.c:1256
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8190c900-ffffffff8190c92b: sock_zerocopy_put_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sock_zerocopy_put_abort(struct ubuf_info *uarg, bool have_uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192da40)
Location: net/core/skbuff.c:1256
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8192da40-ffffffff8192da6b: sock_zerocopy_put_abort (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool have_uref</code>
</li>
</ul>
</details>
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
