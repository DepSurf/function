# Function: <code>tcp_rack_advance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, const struct skb_mstamp *xmit_time, u8 sacked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81783050)
Location: net/ipv4/tcp_recovery.c:82
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff81783050-ffffffff817830f7: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, const struct skb_mstamp *xmit_time, u8 sacked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff817f05e0)
Location: net/ipv4/tcp_recovery.c:82
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
**Symbols:**

```
ffffffff817f05e0-ffffffff817f068c: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, const struct skb_mstamp *xmit_time, u8 sacked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81821350)
Location: net/ipv4/tcp_recovery.c:82
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
**Symbols:**

```
ffffffff81821350-ffffffff818213fc: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81841cc0)
Location: net/ipv4/tcp_recovery.c:126
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
**Symbols:**

```
ffffffff81841cc0-ffffffff81841d2e: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff818c1500)
Location: net/ipv4/tcp_recovery.c:115
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff818c1500-ffffffff818c1562: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81917090)
Location: net/ipv4/tcp_recovery.c:134
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff81917090-ffffffff819170f2: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819458a0)
Location: net/ipv4/tcp_recovery.c:135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff819458a0-ffffffff81945902: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819a9ea0)
Location: net/ipv4/tcp_recovery.c:135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff819a9ea0-ffffffff819a9f02: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819e0b60)
Location: net/ipv4/tcp_recovery.c:135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff819e0b60-ffffffff819e0bc2: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ace150)
Location: net/ipv4/tcp_recovery.c:135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
**Symbols:**

```
ffffffff81ace150-ffffffff81ace1b2: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ada150)
Location: net/ipv4/tcp_recovery.c:122
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
**Symbols:**

```
ffffffff81ada150-ffffffff81ada1b2: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ac51b0)
Location: net/ipv4/tcp_recovery.c:122
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
**Symbols:**

```
ffffffff81ac51b0-ffffffff81ac5214: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81b839c0)
Location: net/ipv4/tcp_recovery.c:122
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
**Symbols:**

```
ffffffff81b839c0-ffffffff81b83a24: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81d140b0)
Location: net/ipv4/tcp_recovery.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
**Symbols:**

```
ffffffff81d140b0-ffffffff81d14136: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81eda100)
Location: net/ipv4/tcp_recovery.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
**Symbols:**

```
ffffffff81eda100-ffffffff81eda186: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81f391e0)
Location: net/ipv4/tcp_recovery.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
**Symbols:**

```
ffffffff81f391e0-ffffffff81f39266: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81fff2d0)
Location: net/ipv4/tcp_recovery.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
**Symbols:**

```
ffffffff81fff2d0-ffffffff81fff356: tcp_rack_advance (STB_GLOBAL)
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
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffff800010c94970)
Location: net/ipv4/tcp_recovery.c:135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffff800010c94970-ffff800010c94a04: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (c0da3214)
Location: net/ipv4/tcp_recovery.c:135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
**Symbols:**

```
c0da3214-c0da32ac: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (c000000000da51f0)
Location: net/ipv4/tcp_recovery.c:135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
c000000000da51f0-c000000000da5268: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffe0007f3d28)
Location: net/ipv4/tcp_recovery.c:135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffe0007f3d28-ffffffe0007f3dac: tcp_rack_advance (STB_GLOBAL)
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
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819809d0)
Location: net/ipv4/tcp_recovery.c:135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff819809d0-ffffffff81980a32: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff8193a490)
Location: net/ipv4/tcp_recovery.c:135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff8193a490-ffffffff8193a4f2: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819eb1a0)
Location: net/ipv4/tcp_recovery.c:135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff819eb1a0-ffffffff819eb202: tcp_rack_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock *tp, u8 sacked, u32 end_seq, u64 xmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819f5020)
Location: net/ipv4/tcp_recovery.c:135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff819f5020-ffffffff819f5082: tcp_rack_advance (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 end_seq</code>
</li>
<li>
<b>Param reordered. </b>
<code>tp, xmit_time, sacked</code> ➡️ <code>tp, sacked, end_seq, xmit_time</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct skb_mstamp *xmit_time</code> ➡️ <code>u64 xmit_time</code>
</li>
</ul>
</details>
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
