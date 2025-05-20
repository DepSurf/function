# Function: <code>skb_attempt_defer_free</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void skb_attempt_defer_free(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bffca0)
Location: net/core/skbuff.c:6495
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
**Symbols:**

```
ffffffff81bffca0-ffffffff81bffde4: skb_attempt_defer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void skb_attempt_defer_free(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81daf030)
Location: net/core/skbuff.c:6696
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
**Symbols:**

```
ffffffff81daf030-ffffffff81daf179: skb_attempt_defer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void skb_attempt_defer_free(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1f220)
Location: net/core/skbuff.c:6741
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
**Symbols:**

```
ffffffff81e1f220-ffffffff81e1f368: skb_attempt_defer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void skb_attempt_defer_free(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81edc880)
Location: net/core/skbuff.c:6888
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
**Symbols:**

```
ffffffff81edc880-ffffffff81edc9c8: skb_attempt_defer_free (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
