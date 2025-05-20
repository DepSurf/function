# Function: <code>tcp_ack_update_rtt</code>

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
In net/ipv4/tcp_input.c (ffffffff8176d337)
Location: net/ipv4/tcp_input.c:2939
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (ffffffff817db0d6)
Location: net/ipv4/tcp_input.c:2944
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (ffffffff8180abc6)
Location: net/ipv4/tcp_input.c:2944
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182a840)
Location: net/ipv4/tcp_input.c:2922
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff8182a840-ffffffff8182aaa0: tcp_ack_update_rtt.isra.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818aa3e0)
Location: net/ipv4/tcp_input.c:2867
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff818aa3e0-ffffffff818aa644: tcp_ack_update_rtt.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818ff6d0)
Location: net/ipv4/tcp_input.c:2905
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff818ff6d0-ffffffff818ff95e: tcp_ack_update_rtt.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192d460)
Location: net/ipv4/tcp_input.c:2895
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff8192d460-ffffffff8192d6fb: tcp_ack_update_rtt.isra.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81990d50)
Location: net/ipv4/tcp_input.c:2915
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff81990d50-ffffffff81991159: tcp_ack_update_rtt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c7930)
Location: net/ipv4/tcp_input.c:2921
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff819c7930-ffffffff819c7d27: tcp_ack_update_rtt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tcp_ack_update_rtt(struct sock *sk, const int flag, long int seq_rtt_us, long int sack_rtt_us, long int ca_rtt_us, struct rate_sample *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab4970)
Location: net/ipv4/tcp_input.c:2905
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff81ab4970-ffffffff81ab4a92: tcp_ack_update_rtt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcp_ack_update_rtt(struct sock *sk, const int flag, long int seq_rtt_us, long int sack_rtt_us, long int ca_rtt_us, struct rate_sample *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abfa30)
Location: net/ipv4/tcp_input.c:3019
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff81abfa30-ffffffff81abfb8f: tcp_ack_update_rtt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_ack_update_rtt(struct sock *sk, const int flag, long int seq_rtt_us, long int sack_rtt_us, long int ca_rtt_us, struct rate_sample *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa9d40)
Location: net/ipv4/tcp_input.c:3026
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff81aa9d40-ffffffff81aa9e94: tcp_ack_update_rtt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tcp_ack_update_rtt(struct sock *sk, const int flag, long int seq_rtt_us, long int sack_rtt_us, long int ca_rtt_us, struct rate_sample *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b66130)
Location: net/ipv4/tcp_input.c:3060
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff81b66130-ffffffff81b66284: tcp_ack_update_rtt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tcp_ack_update_rtt(struct sock *sk, const int flag, long int seq_rtt_us, long int sack_rtt_us, long int ca_rtt_us, struct rate_sample *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf4420)
Location: net/ipv4/tcp_input.c:3076
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff81cf4420-ffffffff81cf4592: tcp_ack_update_rtt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcp_ack_update_rtt(struct sock *sk, const int flag, long int seq_rtt_us, long int sack_rtt_us, long int ca_rtt_us, struct rate_sample *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb8df0)
Location: net/ipv4/tcp_input.c:3087
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff81eb8df0-ffffffff81eb8f62: tcp_ack_update_rtt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcp_ack_update_rtt(struct sock *sk, const int flag, long int seq_rtt_us, long int sack_rtt_us, long int ca_rtt_us, struct rate_sample *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f17200)
Location: net/ipv4/tcp_input.c:3086
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff81f17200-ffffffff81f17372: tcp_ack_update_rtt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcp_ack_update_rtt(struct sock *sk, const int flag, long int seq_rtt_us, long int sack_rtt_us, long int ca_rtt_us, struct rate_sample *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fdc6b0)
Location: net/ipv4/tcp_input.c:3135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff81fdc6b0-ffffffff81fdc85d: tcp_ack_update_rtt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c78fb0)
Location: net/ipv4/tcp_input.c:2921
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffff800010c78fb0-ffff800010c79380: tcp_ack_update_rtt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tcp_ack_update_rtt(struct sock *sk, const int flag, long int seq_rtt_us, long int sack_rtt_us, long int ca_rtt_us, struct rate_sample *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d89044)
Location: net/ipv4/tcp_input.c:2921
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
c0d89044-c0d89448: tcp_ack_update_rtt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d83dc0)
Location: net/ipv4/tcp_input.c:2921
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
c000000000d83dc0-c000000000d84300: tcp_ack_update_rtt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dd560)
Location: net/ipv4/tcp_input.c:2921
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffe0007dd560-ffffffe0007dd8c6: tcp_ack_update_rtt.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819677a0)
Location: net/ipv4/tcp_input.c:2921
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff819677a0-ffffffff81967b97: tcp_ack_update_rtt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81921290)
Location: net/ipv4/tcp_input.c:2921
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff81921290-ffffffff81921687: tcp_ack_update_rtt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d1f70)
Location: net/ipv4/tcp_input.c:2921
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff819d1f70-ffffffff819d2367: tcp_ack_update_rtt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dbb10)
Location: net/ipv4/tcp_input.c:2921
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff819dbb10-ffffffff819dbf07: tcp_ack_update_rtt.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
