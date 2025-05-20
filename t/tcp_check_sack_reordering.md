# Function: <code>tcp_check_sack_reordering</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a86b0)
Location: net/ipv4/tcp_input.c:859
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff818a86b0-ffffffff818a874d: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fd990)
Location: net/ipv4/tcp_input.c:886
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff818fd990-ffffffff818fda27: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192ba80)
Location: net/ipv4/tcp_input.c:872
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff8192ba80-ffffffff8192bb17: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198ed30)
Location: net/ipv4/tcp_input.c:882
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff8198ed30-ffffffff8198edc9: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c5c90)
Location: net/ipv4/tcp_input.c:884
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff819c5c90-ffffffff819c5d29: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab0dd0)
Location: net/ipv4/tcp_input.c:886
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81ab0dd0-ffffffff81ab0e69: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abbe20)
Location: net/ipv4/tcp_input.c:992
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81abbe20-ffffffff81abbeb9: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa6df0)
Location: net/ipv4/tcp_input.c:992
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81aa6df0-ffffffff81aa6e8c: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b633f0)
Location: net/ipv4/tcp_input.c:1024
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81b633f0-ffffffff81b6348c: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf2090)
Location: net/ipv4/tcp_input.c:1033
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81cf2090-ffffffff81cf214a: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb6700)
Location: net/ipv4/tcp_input.c:1032
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81eb6700-ffffffff81eb67ba: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f14b20)
Location: net/ipv4/tcp_input.c:1031
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81f14b20-ffffffff81f14bda: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd9050)
Location: net/ipv4/tcp_input.c:1065
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81fd9050-ffffffff81fd910a: tcp_check_sack_reordering (STB_LOCAL)
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
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c78950)
Location: net/ipv4/tcp_input.c:884
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffff800010c78950-ffff800010c78a34: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d86fe8)
Location: net/ipv4/tcp_input.c:884
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
c0d86fe8-c0d870b8: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d811c0)
Location: net/ipv4/tcp_input.c:884
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
c000000000d811c0-c000000000d812e4: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007db87a)
Location: net/ipv4/tcp_input.c:884
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffe0007db87a-ffffffe0007db946: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81965b00)
Location: net/ipv4/tcp_input.c:884
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81965b00-ffffffff81965b99: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191f5f0)
Location: net/ipv4/tcp_input.c:884
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff8191f5f0-ffffffff8191f689: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d02d0)
Location: net/ipv4/tcp_input.c:884
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff819d02d0-ffffffff819d0369: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_check_sack_reordering(struct sock *sk, const u32 low_seq, const int ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d9e60)
Location: net/ipv4/tcp_input.c:884
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff819d9e60-ffffffff819d9ef9: tcp_check_sack_reordering (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
