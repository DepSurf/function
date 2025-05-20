# Function: <code>tcp_sendmsg_fastopen</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817699a5)
Location: net/ipv4/tcp.c:1064
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
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
In net/ipv4/tcp.c (ffffffff817d67f9)
Location: net/ipv4/tcp.c:1054
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
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
In net/ipv4/tcp.c (ffffffff81806813)
Location: net/ipv4/tcp.c:1078
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
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
In net/ipv4/tcp.c (ffffffff81826c71)
Location: net/ipv4/tcp.c:1102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
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
In net/ipv4/tcp.c (ffffffff818a4f4d)
Location: net/ipv4/tcp.c:1137
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (ffffffff818facde)
Location: net/ipv4/tcp.c:1130
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (ffffffff81928c21)
Location: net/ipv4/tcp.c:1129
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (ffffffff8198bb2d)
Location: net/ipv4/tcp.c:1130
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (ffffffff819c240d)
Location: net/ipv4/tcp.c:1131
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aad9e6)
Location: net/ipv4/tcp.c:1138
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab4dca)
Location: net/ipv4/tcp.c:1157
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (ffffffff81aa0010)
Location: net/ipv4/tcp.c:1156
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (ffffffff81b5bdc9)
Location: net/ipv4/tcp.c:1153
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ceaed7)
Location: net/ipv4/tcp.c:1165
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_sendmsg_fastopen(struct sock *sk, struct msghdr *msg, int *copied, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eae390)
Location: net/ipv4/tcp.c:1167
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81eae390-ffffffff81eae572: tcp_sendmsg_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_sendmsg_fastopen(struct sock *sk, struct msghdr *msg, int *copied, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f0c420)
Location: net/ipv4/tcp.c:985
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81f0c420-ffffffff81f0c602: tcp_sendmsg_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_sendmsg_fastopen(struct sock *sk, struct msghdr *msg, int *copied, size_t size, struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd04e0)
Location: net/ipv4/tcp.c:991
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81fd04e0-ffffffff81fd06e5: tcp_sendmsg_fastopen (STB_GLOBAL)
```
</details>
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
In net/ipv4/tcp.c (ffff800010c751c4)
Location: net/ipv4/tcp.c:1131
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (c0d83880)
Location: net/ipv4/tcp.c:1131
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (c000000000d7c720)
Location: net/ipv4/tcp.c:1131
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (ffffffe0007d84c4)
Location: net/ipv4/tcp.c:1131
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (ffffffff8196227d)
Location: net/ipv4/tcp.c:1131
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (ffffffff8191bd6d)
Location: net/ipv4/tcp.c:1131
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (ffffffff819cca4d)
Location: net/ipv4/tcp.c:1131
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/ipv4/tcp.c (ffffffff819d65dd)
Location: net/ipv4/tcp.c:1131
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
