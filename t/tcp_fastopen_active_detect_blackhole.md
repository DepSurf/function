# Function: <code>tcp_fastopen_active_detect_blackhole</code>

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
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81916a80)
Location: net/ipv4/tcp_fastopen.c:521
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81916a80-ffffffff81916ae6: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81945230)
Location: net/ipv4/tcp_fastopen.c:521
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81945230-ffffffff81945296: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819a9850)
Location: net/ipv4/tcp_fastopen.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff819a9850-ffffffff819a98b5: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819e0510)
Location: net/ipv4/tcp_fastopen.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff819e0510-ffffffff819e0575: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81acdae0)
Location: net/ipv4/tcp_fastopen.c:574
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81acdae0-ffffffff81acdb45: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ad9b40)
Location: net/ipv4/tcp_fastopen.c:574
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81ad9b40-ffffffff81ad9ba5: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4b90)
Location: net/ipv4/tcp_fastopen.c:594
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81ac4b90-ffffffff81ac4bff: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81b83340)
Location: net/ipv4/tcp_fastopen.c:582
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81b83340-ffffffff81b833af: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81d13940)
Location: net/ipv4/tcp_fastopen.c:577
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81d13940-ffffffff81d139bb: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ed9910)
Location: net/ipv4/tcp_fastopen.c:578
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81ed9910-ffffffff81ed998b: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81f389f0)
Location: net/ipv4/tcp_fastopen.c:580
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81f389f0-ffffffff81f38a6b: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ffead0)
Location: net/ipv4/tcp_fastopen.c:580
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
**Symbols:**

```
ffffffff81ffead0-ffffffff81ffeb4b: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
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
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffff800010c94150)
Location: net/ipv4/tcp_fastopen.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffff800010c94150-ffff800010c941d0: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c0da29a4)
Location: net/ipv4/tcp_fastopen.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
c0da29a4-c0da2a1c: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c000000000da48c0)
Location: net/ipv4/tcp_fastopen.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
c000000000da48c0-c000000000da496c: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffe0007f36cc)
Location: net/ipv4/tcp_fastopen.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffe0007f36cc-ffffffe0007f378c: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
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
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81980380)
Location: net/ipv4/tcp_fastopen.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81980380-ffffffff819803e5: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81939e40)
Location: net/ipv4/tcp_fastopen.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81939e40-ffffffff81939ea5: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819eab50)
Location: net/ipv4/tcp_fastopen.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff819eab50-ffffffff819eabb5: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_fastopen_active_detect_blackhole(struct sock *sk, bool expired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819f49d0)
Location: net/ipv4/tcp_fastopen.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff819f49d0-ffffffff819f4a35: tcp_fastopen_active_detect_blackhole (STB_GLOBAL)
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
