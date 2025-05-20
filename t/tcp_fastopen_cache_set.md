# Function: <code>tcp_fastopen_cache_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff817825a0)
Location: net/ipv4/tcp_metrics.c:712
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff817825a0-ffffffff817826be: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff817efa60)
Location: net/ipv4/tcp_metrics.c:713
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff817efa60-ffffffff817efb7e: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81820470)
Location: net/ipv4/tcp_metrics.c:712
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81820470-ffffffff8182058c: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81840990)
Location: net/ipv4/tcp_metrics.c:577
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81840990-ffffffff81840a97: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff818c0100)
Location: net/ipv4/tcp_metrics.c:574
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff818c0100-ffffffff818c0207: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81915c50)
Location: net/ipv4/tcp_metrics.c:571
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81915c50-ffffffff81915d56: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81944400)
Location: net/ipv4/tcp_metrics.c:571
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81944400-ffffffff81944506: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819a89c0)
Location: net/ipv4/tcp_metrics.c:561
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff819a89c0-ffffffff819a8ace: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819df6a0)
Location: net/ipv4/tcp_metrics.c:561
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff819df6a0-ffffffff819df7ae: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81accb10)
Location: net/ipv4/tcp_metrics.c:566
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
```
**Symbols:**

```
ffffffff81accb10-ffffffff81accc14: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81ad8b10)
Location: net/ipv4/tcp_metrics.c:566
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
```
**Symbols:**

```
ffffffff81ad8b10-ffffffff81ad8c19: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81ac3b80)
Location: net/ipv4/tcp_metrics.c:566
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
```
**Symbols:**

```
ffffffff81ac3b80-ffffffff81ac3c88: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_metrics.c (0)
Location: net/ipv4/tcp_metrics.c:566
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
```
**Symbols:**

```
ffffffff81d3be2e-ffffffff81d3be43: tcp_fastopen_cache_set.cold (STB_LOCAL)
ffffffff81b82240-ffffffff81b8235c: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_metrics.c (0)
Location: net/ipv4/tcp_metrics.c:567
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
```
**Symbols:**

```
ffffffff81f0864b-ffffffff81f08660: tcp_fastopen_cache_set.cold (STB_LOCAL)
ffffffff81d12700-ffffffff81d1285a: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_metrics.c (0)
Location: net/ipv4/tcp_metrics.c:567
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
```
**Symbols:**

```
ffffffff820b00ec-ffffffff820b0101: tcp_fastopen_cache_set.cold (STB_LOCAL)
ffffffff81ed8520-ffffffff81ed867a: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_metrics.c (0)
Location: net/ipv4/tcp_metrics.c:585
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
```
**Symbols:**

```
ffffffff82131384-ffffffff82131399: tcp_fastopen_cache_set.cold (STB_LOCAL)
ffffffff81f37630-ffffffff81f3778a: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_metrics.c (0)
Location: net/ipv4/tcp_metrics.c:584
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
```
**Symbols:**

```
ffffffff82212cc8-ffffffff82212cdd: tcp_fastopen_cache_set.cold (STB_LOCAL)
ffffffff81ffd700-ffffffff81ffd85a: tcp_fastopen_cache_set (STB_GLOBAL)
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
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffff800010c93038)
Location: net/ipv4/tcp_metrics.c:561
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffff800010c93038-ffff800010c931e8: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (c0da1a24)
Location: net/ipv4/tcp_metrics.c:561
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
c0da1a24-c0da1b34: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (c000000000da3390)
Location: net/ipv4/tcp_metrics.c:561
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
c000000000da3390-c000000000da3540: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffe0007f2778)
Location: net/ipv4/tcp_metrics.c:561
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffe0007f2778-ffffffe0007f2892: tcp_fastopen_cache_set (STB_GLOBAL)
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
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff8197f510)
Location: net/ipv4/tcp_metrics.c:561
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff8197f510-ffffffff8197f61e: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81938fd0)
Location: net/ipv4/tcp_metrics.c:561
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81938fd0-ffffffff819390de: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819e9ce0)
Location: net/ipv4/tcp_metrics.c:561
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff819e9ce0-ffffffff819e9dee: tcp_fastopen_cache_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_fastopen_cache_set(struct sock *sk, u16 mss, struct tcp_fastopen_cookie *cookie, bool syn_lost, u16 try_exp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819f3ad0)
Location: net/ipv4/tcp_metrics.c:561
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff819f3ad0-ffffffff819f3c19: tcp_fastopen_cache_set (STB_GLOBAL)
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
