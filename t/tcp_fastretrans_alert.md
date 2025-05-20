# Function: <code>tcp_fastretrans_alert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const int acked, const int prior_unsacked, bool is_dupack, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81770f20)
Location: net/ipv4/tcp_input.c:2759
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81770f20-ffffffff817719b4: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const int acked, bool is_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dce90)
Location: net/ipv4/tcp_input.c:2761
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff817dce90-ffffffff817dd9c5: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const int acked, bool is_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180cfb0)
Location: net/ipv4/tcp_input.c:2815
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8180cfb0-ffffffff8180db4b: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const int acked, bool is_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182d720)
Location: net/ipv4/tcp_input.c:2797
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8182d720-ffffffff8182e0a6: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, bool is_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818ac5d0)
Location: net/ipv4/tcp_input.c:2743
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff818ac5d0-ffffffff818acee5: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, bool is_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81901b90)
Location: net/ipv4/tcp_input.c:2774
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81901b90-ffffffff819024ce: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192fc70)
Location: net/ipv4/tcp_input.c:2765
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8192fc70-ffffffff81930549: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:2785
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819931d0-ffffffff81993b42: tcp_fastretrans_alert (STB_LOCAL)
ffffffff819980c2-ffffffff8199812c: tcp_fastretrans_alert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c9d20)
Location: net/ipv4/tcp_input.c:2791
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819c9d20-ffffffff819ca692: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab6b50)
Location: net/ipv4/tcp_input.c:2776
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ab6b50-ffffffff81ab7662: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac1df0)
Location: net/ipv4/tcp_input.c:2889
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ac1df0-ffffffff81ac291a: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aacee0)
Location: net/ipv4/tcp_input.c:2892
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81aacee0-ffffffff81aadaad: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b699d0)
Location: net/ipv4/tcp_input.c:2926
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81b699d0-ffffffff81b6a59d: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf8ba0)
Location: net/ipv4/tcp_input.c:2942
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81cf8ba0-ffffffff81cf9710: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebd6a0)
Location: net/ipv4/tcp_input.c:2953
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ebd6a0-ffffffff81ebe1e7: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1bb50)
Location: net/ipv4/tcp_input.c:2952
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81f1bb50-ffffffff81f1c68e: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fe0340)
Location: net/ipv4/tcp_input.c:2999
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81fe0340-ffffffff81fe0e63: tcp_fastretrans_alert (STB_LOCAL)
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
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7cc58)
Location: net/ipv4/tcp_input.c:2791
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffff800010c7cc58-ffff800010c7d388: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8bc14)
Location: net/ipv4/tcp_input.c:2791
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c0d8bc14-c0d8c430: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d86970)
Location: net/ipv4/tcp_input.c:2791
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c000000000d86970-c000000000d8734c: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007df486)
Location: net/ipv4/tcp_input.c:2791
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffe0007df486-ffffffe0007dfb12: tcp_fastretrans_alert (STB_LOCAL)
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
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81969b90)
Location: net/ipv4/tcp_input.c:2791
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81969b90-ffffffff8196a502: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81923680)
Location: net/ipv4/tcp_input.c:2791
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81923680-ffffffff81923ff2: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d4360)
Location: net/ipv4/tcp_input.c:2791
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819d4360-ffffffff819d4cd2: tcp_fastretrans_alert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock *sk, const u32 prior_snd_una, int num_dupack, int *ack_flag, int *rexmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819ddf40)
Location: net/ipv4/tcp_input.c:2791
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819ddf40-ffffffff819de8b2: tcp_fastretrans_alert (STB_LOCAL)
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
<code>int *ack_flag</code>
</li>
<li>
<b>Param added. </b>
<code>int *rexmit</code>
</li>
<li>
<b>Param removed. </b>
<code>const int prior_unsacked</code>
</li>
<li>
<b>Param removed. </b>
<code>int flag</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, acked, prior_unsacked, is_dupack, flag</code> ➡️ <code>sk, acked, is_dupack, ack_flag, rexmit</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const u32 prior_snd_una</code>
</li>
<li>
<b>Param removed. </b>
<code>const int acked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int num_dupack</code>
</li>
<li>
<b>Param removed. </b>
<code>bool is_dupack</code>
</li>
</ul>
</details>
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
