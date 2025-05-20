# Function: <code>tcp_rtt_estimator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_rtt_estimator(struct sock *sk, long int mrtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176ced0)
Location: net/ipv4/tcp_input.c:687
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff8176ced0-ffffffff8176d08e: tcp_rtt_estimator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_rtt_estimator(struct sock *sk, long int mrtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dac50)
Location: net/ipv4/tcp_input.c:689
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff817dac50-ffffffff817dade9: tcp_rtt_estimator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_rtt_estimator(struct sock *sk, long int mrtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180a790)
Location: net/ipv4/tcp_input.c:712
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff8180a790-ffffffff8180a929: tcp_rtt_estimator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182a88e)
Location: net/ipv4/tcp_input.c:719
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818aa432)
Location: net/ipv4/tcp_input.c:711
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818ff72f)
Location: net/ipv4/tcp_input.c:738
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192d4bd)
Location: net/ipv4/tcp_input.c:723
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81990dbf)
Location: net/ipv4/tcp_input.c:729
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c799f)
Location: net/ipv4/tcp_input.c:731
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_rtt_estimator(struct sock *sk, long int mrtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab4710)
Location: net/ipv4/tcp_input.c:733
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
**Symbols:**

```
ffffffff81ab4710-ffffffff81ab4965: tcp_rtt_estimator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_rtt_estimator(struct sock *sk, long int mrtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abf7d0)
Location: net/ipv4/tcp_input.c:797
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
**Symbols:**

```
ffffffff81abf7d0-ffffffff81abfa24: tcp_rtt_estimator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_rtt_estimator(struct sock *sk, long int mrtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa9ae0)
Location: net/ipv4/tcp_input.c:797
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
**Symbols:**

```
ffffffff81aa9ae0-ffffffff81aa9d34: tcp_rtt_estimator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_rtt_estimator(struct sock *sk, long int mrtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:820
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
**Symbols:**

```
ffffffff81b65e50-ffffffff81b6612b: tcp_rtt_estimator (STB_LOCAL)
ffffffff81d3a98c-ffffffff81d3aa00: tcp_rtt_estimator.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_rtt_estimator(struct sock *sk, long int mrtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:829
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
**Symbols:**

```
ffffffff81cf4100-ffffffff81cf441d: tcp_rtt_estimator (STB_LOCAL)
ffffffff81f0708d-ffffffff81f07107: tcp_rtt_estimator.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_rtt_estimator(struct sock *sk, long int mrtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:828
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
**Symbols:**

```
ffffffff81eb8ac0-ffffffff81eb8ddd: tcp_rtt_estimator (STB_LOCAL)
ffffffff820aeb3e-ffffffff820aebb8: tcp_rtt_estimator.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_rtt_estimator(struct sock *sk, long int mrtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:827
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
**Symbols:**

```
ffffffff81f16f60-ffffffff81f171e1: tcp_rtt_estimator (STB_LOCAL)
ffffffff8212ffdc-ffffffff8213000e: tcp_rtt_estimator.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_rtt_estimator(struct sock *sk, long int mrtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:861
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
**Symbols:**

```
ffffffff81fdc420-ffffffff81fdc692: tcp_rtt_estimator (STB_LOCAL)
ffffffff82211c89-ffffffff82211cbb: tcp_rtt_estimator.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7903c)
Location: net/ipv4/tcp_input.c:731
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d890d0)
Location: net/ipv4/tcp_input.c:731
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d83e4c)
Location: net/ipv4/tcp_input.c:731
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dd5c8)
Location: net/ipv4/tcp_input.c:731
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196780f)
Location: net/ipv4/tcp_input.c:731
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819212ff)
Location: net/ipv4/tcp_input.c:731
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d1fdf)
Location: net/ipv4/tcp_input.c:731
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dbb7f)
Location: net/ipv4/tcp_input.c:731
Inline: True
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
