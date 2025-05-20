# Function: <code>perf_trace_tcp_probe</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c3ed0)
Location: include/trace/events/tcp.h:226
Inline: False
```
**Symbols:**

```
ffffffff818c3ed0-ffffffff818c4198: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818ecf60)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
ffffffff818ecf60-ffffffff818ed225: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8193d500)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
ffffffff8193d500-ffffffff8193d7dc: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81970390)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
ffffffff81970390-ffffffff8197066c: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a441e0)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
ffffffff81a441e0-ffffffff81a444c3: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a47f50)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
ffffffff81a47f50-ffffffff81a48233: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a2cea0)
Location: include/trace/events/tcp.h:238
Inline: False
```
**Symbols:**

```
ffffffff81a2cea0-ffffffff81a2d18e: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/tcp.h:238
Inline: False
```
**Symbols:**

```
ffffffff81ae2470-ffffffff81ae2761: perf_trace_tcp_probe (STB_LOCAL)
ffffffff81d37e38-ffffffff81d37e60: perf_trace_tcp_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/tcp.h:238
Inline: False
```
**Symbols:**

```
ffffffff81c66040-ffffffff81c66357: perf_trace_tcp_probe (STB_LOCAL)
ffffffff81f04851-ffffffff81f04879: perf_trace_tcp_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/tcp.h:238
Inline: False
```
**Symbols:**

```
ffffffff81e1cda0-ffffffff81e1d0b4: perf_trace_tcp_probe (STB_LOCAL)
ffffffff820acae4-ffffffff820acb0c: perf_trace_tcp_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/tcp.h:238
Inline: False
```
**Symbols:**

```
ffffffff81e916a0-ffffffff81e919b6: perf_trace_tcp_probe (STB_LOCAL)
ffffffff8212e1e1-ffffffff8212e202: perf_trace_tcp_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/tcp.h:238
Inline: False
```
**Symbols:**

```
ffffffff81f53a60-ffffffff81f53d76: perf_trace_tcp_probe (STB_LOCAL)
ffffffff8220ffc0-ffffffff8220ffe1: perf_trace_tcp_probe.cold (STB_LOCAL)
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
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c19270)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
ffff800010c19270-ffff800010c194ac: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d2e870)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
c0d2e870-c0d2eac8: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d05740)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
c000000000d05740-c000000000d05a38: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffe00079234c)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
ffffffe00079234c-ffffffe000792532: perf_trace_tcp_probe (STB_LOCAL)
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
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81910360)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
ffffffff81910360-ffffffff8191063c: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818ca120)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
ffffffff818ca120-ffffffff818ca3fc: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81961390)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
ffffffff81961390-ffffffff8196166c: perf_trace_tcp_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_tcp_probe(void *__data, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81983600)
Location: include/trace/events/tcp.h:229
Inline: False
```
**Symbols:**

```
ffffffff81983600-ffffffff819838dc: perf_trace_tcp_probe (STB_LOCAL)
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
