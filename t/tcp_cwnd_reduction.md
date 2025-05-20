# Function: <code>tcp_cwnd_reduction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, const int prior_unsacked, int fast_rexmit, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176ad10)
Location: net/ipv4/tcp_input.c:2472
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff8176ad10-ffffffff8176adee: tcp_cwnd_reduction (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff817de0ac)
Location: net/ipv4/tcp_input.c:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffff8180e43b)
Location: net/ipv4/tcp_input.c:2524
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182d540)
Location: net/ipv4/tcp_input.c:2489
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff8182d540-ffffffff8182d5ee: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818ac3e0)
Location: net/ipv4/tcp_input.c:2434
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff818ac3e0-ffffffff818ac48f: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81901980)
Location: net/ipv4/tcp_input.c:2461
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81901980-ffffffff81901a44: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192fa60)
Location: net/ipv4/tcp_input.c:2452
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff8192fa60-ffffffff8192fb24: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81992fc0)
Location: net/ipv4/tcp_input.c:2472
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81992fc0-ffffffff81993084: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c9b10)
Location: net/ipv4/tcp_input.c:2478
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff819c9b10-ffffffff819c9bd4: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab6950)
Location: net/ipv4/tcp_input.c:2463
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81ab6950-ffffffff81ab6a16: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int newly_lost, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac1be0)
Location: net/ipv4/tcp_input.c:2567
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81ac1be0-ffffffff81ac1cb6: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int newly_lost, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aaccd0)
Location: net/ipv4/tcp_input.c:2567
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81aaccd0-ffffffff81aacda6: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int newly_lost, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b697c0)
Location: net/ipv4/tcp_input.c:2601
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81b697c0-ffffffff81b69896: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int newly_lost, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf8980)
Location: net/ipv4/tcp_input.c:2614
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81cf8980-ffffffff81cf8a7c: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int newly_lost, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebd460)
Location: net/ipv4/tcp_input.c:2625
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81ebd460-ffffffff81ebd55c: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int newly_lost, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1b8e0)
Location: net/ipv4/tcp_input.c:2624
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81f1b8e0-ffffffff81f1b9dc: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int newly_lost, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fe00c0)
Location: net/ipv4/tcp_input.c:2663
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81fe00c0-ffffffff81fe01bc: tcp_cwnd_reduction (STB_GLOBAL)
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
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7ca28)
Location: net/ipv4/tcp_input.c:2478
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffff800010c7ca28-ffff800010c7cb40: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8b98c)
Location: net/ipv4/tcp_input.c:2478
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
c0d8b98c-c0d8baf4: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d866b0)
Location: net/ipv4/tcp_input.c:2478
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
c000000000d866b0-c000000000d867c8: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007df27e)
Location: net/ipv4/tcp_input.c:2478
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffe0007df27e-ffffffe0007df362: tcp_cwnd_reduction (STB_GLOBAL)
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
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81969980)
Location: net/ipv4/tcp_input.c:2478
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81969980-ffffffff81969a44: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81923470)
Location: net/ipv4/tcp_input.c:2478
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81923470-ffffffff81923534: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d4150)
Location: net/ipv4/tcp_input.c:2478
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff819d4150-ffffffff819d4214: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock *sk, int newly_acked_sacked, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819ddd30)
Location: net/ipv4/tcp_input.c:2478
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff819ddd30-ffffffff819dddf4: tcp_cwnd_reduction (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int newly_lost</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, newly_acked_sacked, flag</code> ➡️ <code>sk, newly_acked_sacked, newly_lost, flag</code>
</li>
</ul>
</details>
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
