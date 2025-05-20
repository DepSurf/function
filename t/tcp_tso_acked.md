# Function: <code>tcp_tso_acked</code>

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
In net/ipv4/tcp_input.c (ffffffff8176d4dd)
Location: net/ipv4/tcp_input.c:3058
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffff817db28d)
Location: net/ipv4/tcp_input.c:3063
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffff8180adbf)
Location: net/ipv4/tcp_input.c:3063
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffff8182b0aa)
Location: net/ipv4/tcp_input.c:3027
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffff818aacf6)
Location: net/ipv4/tcp_input.c:2972
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffff818ffe7f)
Location: net/ipv4/tcp_input.c:3010
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffff8192dc69)
Location: net/ipv4/tcp_input.c:3002
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffff81991794)
Location: net/ipv4/tcp_input.c:3022
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffff819c8378)
Location: net/ipv4/tcp_input.c:3028
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 tcp_tso_acked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aafe10)
Location: net/ipv4/tcp_input.c:3012
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff81aafe10-ffffffff81aafe66: tcp_tso_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 tcp_tso_acked(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abac60)
Location: net/ipv4/tcp_input.c:3128
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff81abac60-ffffffff81abacb6: tcp_tso_acked (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff81aaa521)
Location: net/ipv4/tcp_input.c:3135
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81b66911)
Location: net/ipv4/tcp_input.c:3169
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81cf48b0)
Location: net/ipv4/tcp_input.c:3185
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81eb929b)
Location: net/ipv4/tcp_input.c:3196
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81f176ab)
Location: net/ipv4/tcp_input.c:3195
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81fdcbb2)
Location: net/ipv4/tcp_input.c:3237
Inline: True
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
In net/ipv4/tcp_input.c (ffff800010c7be14)
Location: net/ipv4/tcp_input.c:3028
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (c0d89aec)
Location: net/ipv4/tcp_input.c:3028
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (c000000000d84a90)
Location: net/ipv4/tcp_input.c:3028
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffe0007dddc6)
Location: net/ipv4/tcp_input.c:3028
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffff819681e8)
Location: net/ipv4/tcp_input.c:3028
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffff81921cd8)
Location: net/ipv4/tcp_input.c:3028
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffff819d29b8)
Location: net/ipv4/tcp_input.c:3028
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
In net/ipv4/tcp_input.c (ffffffff819dc558)
Location: net/ipv4/tcp_input.c:3028
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
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
</ul>
