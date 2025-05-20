# Function: <code>tcp_clean_rtx_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, int prior_fackets, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176d090)
Location: net/ipv4/tcp_input.c:3097
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8176d090-ffffffff8176dac6: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, int prior_fackets, u32 prior_snd_una, int *acked, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dadf0)
Location: net/ipv4/tcp_input.c:3102
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff817dadf0-ffffffff817db8ca: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, int prior_fackets, u32 prior_snd_una, int *acked, struct tcp_sacktag_state *sack, struct skb_mstamp *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180a930)
Location: net/ipv4/tcp_input.c:3102
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8180a930-ffffffff8180b3fe: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, int prior_fackets, u32 prior_snd_una, int *acked, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182aaa0)
Location: net/ipv4/tcp_input.c:3066
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8182aaa0-ffffffff8182b30e: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818aa650)
Location: net/ipv4/tcp_input.c:3014
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff818aa650-ffffffff818aaf12: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818ff960)
Location: net/ipv4/tcp_input.c:3052
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff818ff960-ffffffff819002e1: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192d700)
Location: net/ipv4/tcp_input.c:3044
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8192d700-ffffffff8192e0d6: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3064
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81991160-ffffffff81991b57: tcp_clean_rtx_queue (STB_LOCAL)
ffffffff8199801c-ffffffff81998068: tcp_clean_rtx_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c7d30)
Location: net/ipv4/tcp_input.c:3070
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819c7d30-ffffffff819c8759: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab4aa0)
Location: net/ipv4/tcp_input.c:3054
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ab4aa0-ffffffff81ab5503: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack, bool ece_ack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abfb90)
Location: net/ipv4/tcp_input.c:3170
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81abfb90-ffffffff81ac061f: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa9ea0)
Location: net/ipv4/tcp_input.c:3177
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81aa9ea0-ffffffff81aaa915: tcp_clean_rtx_queue.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b66290)
Location: net/ipv4/tcp_input.c:3211
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81b66290-ffffffff81b66d05: tcp_clean_rtx_queue.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf45a0)
Location: net/ipv4/tcp_input.c:3227
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81cf45a0-ffffffff81cf5050: tcp_clean_rtx_queue.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb8f80)
Location: net/ipv4/tcp_input.c:3238
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81eb8f80-ffffffff81eb9a62: tcp_clean_rtx_queue.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f17390)
Location: net/ipv4/tcp_input.c:3237
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81f17390-ffffffff81f17e76: tcp_clean_rtx_queue.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fdc870)
Location: net/ipv4/tcp_input.c:3279
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81fdc870-ffffffff81fdd387: tcp_clean_rtx_queue.constprop.0 (STB_LOCAL)
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
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7b7e0)
Location: net/ipv4/tcp_input.c:3070
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffff800010c7b7e0-ffff800010c7c108: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d89448)
Location: net/ipv4/tcp_input.c:3070
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c0d89448-c0d89f58: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d84300)
Location: net/ipv4/tcp_input.c:3070
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c000000000d84300-c000000000d84ed0: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dd8c6)
Location: net/ipv4/tcp_input.c:3070
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffe0007dd8c6-ffffffe0007de0e0: tcp_clean_rtx_queue (STB_LOCAL)
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
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81967ba0)
Location: net/ipv4/tcp_input.c:3070
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81967ba0-ffffffff819685c9: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81921690)
Location: net/ipv4/tcp_input.c:3070
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81921690-ffffffff819220b9: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d2370)
Location: net/ipv4/tcp_input.c:3070
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819d2370-ffffffff819d2d99: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_clean_rtx_queue(struct sock *sk, u32 prior_fack, u32 prior_snd_una, struct tcp_sacktag_state *sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dbf10)
Location: net/ipv4/tcp_input.c:3070
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819dbf10-ffffffff819dc939: tcp_clean_rtx_queue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *acked</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, prior_fackets, prior_snd_una, sack</code> ➡️ <code>sk, prior_fackets, prior_snd_una, acked, sack</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct skb_mstamp *now</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct skb_mstamp *now</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 prior_fack</code>
</li>
<li>
<b>Param removed. </b>
<code>int prior_fackets</code>
</li>
<li>
<b>Param removed. </b>
<code>int *acked</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, prior_fackets, prior_snd_una, acked, sack</code> ➡️ <code>sk, prior_fack, prior_snd_una, sack</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool ece_ack</code>
</li>
</ul>
</details>
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
