# Function: <code>tcp_simple_retransmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81770d10)
Location: net/ipv4/tcp_input.c:2594
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced
```
**Symbols:**

```
ffffffff81770d10-ffffffff81770f1d: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dcc80)
Location: net/ipv4/tcp_input.c:2592
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced
```
**Symbols:**

```
ffffffff817dcc80-ffffffff817dce83: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180cda0)
Location: net/ipv4/tcp_input.c:2646
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff8180cda0-ffffffff8180cfa3: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182d000)
Location: net/ipv4/tcp_input.c:2610
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff8182d000-ffffffff8182d1e8: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818abf10)
Location: net/ipv4/tcp_input.c:2555
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff818abf10-ffffffff818ac087: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81901440)
Location: net/ipv4/tcp_input.c:2582
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81901440-ffffffff819015c2: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192f530)
Location: net/ipv4/tcp_input.c:2573
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff8192f530-ffffffff8192f6af: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:2593
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff8199809c-ffffffff819980af: tcp_simple_retransmit.cold (STB_LOCAL)
ffffffff81992a60-ffffffff81992bee: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c95a0)
Location: net/ipv4/tcp_input.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff819c95a0-ffffffff819c9735: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab5780)
Location: net/ipv4/tcp_input.c:2584
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81ab5780-ffffffff81ab5915: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac09d0)
Location: net/ipv4/tcp_input.c:2687
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81ac09d0-ffffffff81ac0b6e: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aab770)
Location: net/ipv4/tcp_input.c:2687
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81aab770-ffffffff81aab90e: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b67bb0)
Location: net/ipv4/tcp_input.c:2721
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81b67bb0-ffffffff81b67d4e: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf6cb0)
Location: net/ipv4/tcp_input.c:2737
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81cf6cb0-ffffffff81cf6e40: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebb700)
Location: net/ipv4/tcp_input.c:2748
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81ebb700-ffffffff81ebb890: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f19b80)
Location: net/ipv4/tcp_input.c:2747
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81f19b80-ffffffff81f19d10: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fde350)
Location: net/ipv4/tcp_input.c:2786
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81fde350-ffffffff81fde4e0: tcp_simple_retransmit (STB_GLOBAL)
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
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7c4d8)
Location: net/ipv4/tcp_input.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffff800010c7c4d8-ffff800010c7c650: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8b440)
Location: net/ipv4/tcp_input.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
c0d8b440-c0d8b5cc: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d86010)
Location: net/ipv4/tcp_input.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
c000000000d86010-c000000000d86218: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dedc8)
Location: net/ipv4/tcp_input.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffe0007dedc8-ffffffe0007def26: tcp_simple_retransmit (STB_GLOBAL)
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
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81969410)
Location: net/ipv4/tcp_input.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81969410-ffffffff819695a5: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81922f00)
Location: net/ipv4/tcp_input.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81922f00-ffffffff81923095: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d3be0)
Location: net/ipv4/tcp_input.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff819d3be0-ffffffff819d3d75: tcp_simple_retransmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_simple_retransmit(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dd7c0)
Location: net/ipv4/tcp_input.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff819dd7c0-ffffffff819dd955: tcp_simple_retransmit (STB_GLOBAL)
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
