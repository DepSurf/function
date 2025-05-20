# Function: <code>__bpf_trace_sock_rcvqueue_full</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c3610)
Location: include/trace/events/sock.h:62
Inline: True
```
**Symbols:**

```
ffffffff818c3610-ffffffff818c361b: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818ec4f0)
Location: include/trace/events/sock.h:70
Inline: True
```
**Symbols:**

```
ffffffff818ec4f0-ffffffff818ec4fb: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8193c410)
Location: include/trace/events/sock.h:70
Inline: False
```
**Symbols:**

```
ffffffff8193c410-ffffffff8193c41b: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8196f2a0)
Location: include/trace/events/sock.h:70
Inline: False
```
**Symbols:**

```
ffffffff8196f2a0-ffffffff8196f2ab: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/sock.h:71
Inline: False
```
**Symbols:**

```
ffffffff81a44120-ffffffff81a4412b: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/sock.h:71
Inline: False
```
**Symbols:**

```
ffffffff81a47e90-ffffffff81a47e9b: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/sock.h:71
Inline: False
```
**Symbols:**

```
ffffffff81a2cde0-ffffffff81a2cdeb: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/sock.h:71
Inline: False
```
**Symbols:**

```
ffffffff81ae2390-ffffffff81ae239b: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/sock.h:71
Inline: False
```
**Symbols:**

```
ffffffff81c68e00-ffffffff81c68e15: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/sock.h:71
Inline: False
```
**Symbols:**

```
ffffffff81e20530-ffffffff81e20545: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/sock.h:71
Inline: False
```
**Symbols:**

```
ffffffff81e95ed0-ffffffff81e95ee5: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/sock.h:71
Inline: False
```
**Symbols:**

```
ffffffff81f58450-ffffffff81f58465: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c14d68)
Location: include/trace/events/sock.h:70
Inline: True
```
**Symbols:**

```
ffff800010c14d68-ffff800010c14d7c: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d2d630)
Location: include/trace/events/sock.h:70
Inline: False
```
**Symbols:**

```
c0d2d630-c0d2d658: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d03f60)
Location: include/trace/events/sock.h:70
Inline: False
```
**Symbols:**

```
c000000000d03f60-c000000000d03f8c: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8190f270)
Location: include/trace/events/sock.h:70
Inline: False
```
**Symbols:**

```
ffffffff8190f270-ffffffff8190f27b: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c9030)
Location: include/trace/events/sock.h:70
Inline: False
```
**Symbols:**

```
ffffffff818c9030-ffffffff818c903b: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819602a0)
Location: include/trace/events/sock.h:70
Inline: False
```
**Symbols:**

```
ffffffff819602a0-ffffffff819602ab: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_sock_rcvqueue_full(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81982510)
Location: include/trace/events/sock.h:70
Inline: False
```
**Symbols:**

```
ffffffff81982510-ffffffff8198251b: __bpf_trace_sock_rcvqueue_full (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
