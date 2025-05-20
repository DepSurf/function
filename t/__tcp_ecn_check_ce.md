# Function: <code>__tcp_ecn_check_ce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct tcp_sock *tp, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176a6b0)
Location: net/ipv4/tcp_input.c:227
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff8176a6b0-ffffffff8176a7d6: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct tcp_sock *tp, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817d7130)
Location: net/ipv4/tcp_input.c:229
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff817d7130-ffffffff817d7256: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct tcp_sock *tp, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81807240)
Location: net/ipv4/tcp_input.c:250
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81807240-ffffffff81807366: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct tcp_sock *tp, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81827890)
Location: net/ipv4/tcp_input.c:249
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81827890-ffffffff818279b1: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct tcp_sock *tp, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a6f40)
Location: net/ipv4/tcp_input.c:235
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff818a6f40-ffffffff818a7067: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fc200)
Location: net/ipv4/tcp_input.c:265
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff818fc200-ffffffff818fc314: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192a240)
Location: net/ipv4/tcp_input.c:266
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff8192a240-ffffffff8192a354: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198d480)
Location: net/ipv4/tcp_input.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff8198d480-ffffffff8198d595: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c3de0)
Location: net/ipv4/tcp_input.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff819c3de0-ffffffff819c3ef5: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab2a90)
Location: net/ipv4/tcp_input.c:274
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81ab2a90-ffffffff81ab2bb4: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abd850)
Location: net/ipv4/tcp_input.c:337
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81abd850-ffffffff81abd974: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa8700)
Location: net/ipv4/tcp_input.c:337
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81aa8700-ffffffff81aa8830: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b64960)
Location: net/ipv4/tcp_input.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81b64960-ffffffff81b64a90: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf3760)
Location: net/ipv4/tcp_input.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81cf3760-ffffffff81cf38ba: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb7c80)
Location: net/ipv4/tcp_input.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81eb7c80-ffffffff81eb7dda: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f160e0)
Location: net/ipv4/tcp_input.c:337
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81f160e0-ffffffff81f16241: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fda730)
Location: net/ipv4/tcp_input.c:353
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81fda730-ffffffff81fda887: __tcp_ecn_check_ce (STB_LOCAL)
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
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c76a20)
Location: net/ipv4/tcp_input.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffff800010c76a20-ffff800010c76b58: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d84f74)
Location: net/ipv4/tcp_input.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
c0d84f74-c0d850ac: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d7e510)
Location: net/ipv4/tcp_input.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
c000000000d7e510-c000000000d7e6c8: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007d9990)
Location: net/ipv4/tcp_input.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffe0007d9990-ffffffe0007d9a8a: __tcp_ecn_check_ce (STB_LOCAL)
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
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81963c50)
Location: net/ipv4/tcp_input.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81963c50-ffffffff81963d65: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191d740)
Location: net/ipv4/tcp_input.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff8191d740-ffffffff8191d855: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819ce420)
Location: net/ipv4/tcp_input.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff819ce420-ffffffff819ce535: __tcp_ecn_check_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __tcp_ecn_check_ce(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d7fb0)
Location: net/ipv4/tcp_input.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff819d7fb0-ffffffff819d80c5: __tcp_ecn_check_ce (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sock *sk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct tcp_sock *tp</code>
</li>
</ul>
</details>
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
