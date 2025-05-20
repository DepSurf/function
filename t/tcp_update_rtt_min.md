# Function: <code>tcp_update_rtt_min</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_update_rtt_min(struct sock *sk, u32 rtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176ab20)
Location: net/ipv4/tcp_input.c:2897
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff8176ab20-ffffffff8176ac84: tcp_update_rtt_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_update_rtt_min(struct sock *sk, u32 rtt_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817d7520)
Location: net/ipv4/tcp_input.c:2899
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
**Symbols:**

```
ffffffff817d7520-ffffffff817d76ce: tcp_update_rtt_min (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff8180abe6)
Location: net/ipv4/tcp_input.c:2935
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
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
In net/ipv4/tcp_input.c (ffffffff8182a85e)
Location: net/ipv4/tcp_input.c:2913
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
In net/ipv4/tcp_input.c (ffffffff818aa401)
Location: net/ipv4/tcp_input.c:2858
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
In net/ipv4/tcp_input.c (ffffffff818ff6f4)
Location: net/ipv4/tcp_input.c:2889
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
In net/ipv4/tcp_input.c (ffffffff8192d488)
Location: net/ipv4/tcp_input.c:2879
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
In net/ipv4/tcp_input.c (ffffffff81990d8a)
Location: net/ipv4/tcp_input.c:2899
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
In net/ipv4/tcp_input.c (ffffffff819c796a)
Location: net/ipv4/tcp_input.c:2905
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab4999)
Location: net/ipv4/tcp_input.c:2889
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abfa59)
Location: net/ipv4/tcp_input.c:3003
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa9d69)
Location: net/ipv4/tcp_input.c:3010
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b66159)
Location: net/ipv4/tcp_input.c:3044
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf444b)
Location: net/ipv4/tcp_input.c:3060
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb8e1b)
Location: net/ipv4/tcp_input.c:3071
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1722b)
Location: net/ipv4/tcp_input.c:3070
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fdc6d4)
Location: net/ipv4/tcp_input.c:3119
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
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
In net/ipv4/tcp_input.c (ffff800010c79004)
Location: net/ipv4/tcp_input.c:2905
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
In net/ipv4/tcp_input.c (c0d8908c)
Location: net/ipv4/tcp_input.c:2905
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
In net/ipv4/tcp_input.c (c000000000d83e10)
Location: net/ipv4/tcp_input.c:2905
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
In net/ipv4/tcp_input.c (ffffffe0007dd594)
Location: net/ipv4/tcp_input.c:2905
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
In net/ipv4/tcp_input.c (ffffffff819677da)
Location: net/ipv4/tcp_input.c:2905
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
In net/ipv4/tcp_input.c (ffffffff819212ca)
Location: net/ipv4/tcp_input.c:2905
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
In net/ipv4/tcp_input.c (ffffffff819d1faa)
Location: net/ipv4/tcp_input.c:2905
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
In net/ipv4/tcp_input.c (ffffffff819dbb4a)
Location: net/ipv4/tcp_input.c:2905
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
</ul>
