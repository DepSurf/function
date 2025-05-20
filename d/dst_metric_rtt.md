# Function: <code>dst_metric_rtt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176d07f)
Location: include/net/dst.h:228
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d35e)
Location: include/net/dst.h:228
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817822a0)
Location: include/net/dst.h:228
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dadce)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea9fb)
Location: include/net/dst.h:225
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ef759)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180a90e)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181af9b)
Location: include/net/dst.h:225
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181ffa9)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182a9a3)
Location: include/net/dst.h:229
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b763)
Location: include/net/dst.h:229
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184071d)
Location: include/net/dst.h:229
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818aa547)
Location: include/net/dst.h:231
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bfe91)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818ff947)
Location: include/net/dst.h:214
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915a56)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192d6e4)
Location: include/net/dst.h:214
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81944206)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819910b6)
Location: include/net/dst.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a87c9)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c7b05)
Location: include/net/dst.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df49d)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab4908)
Location: include/net/dst.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acca55)
Location: include/net/dst.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abf986)
Location: include/net/dst.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad89c2)
Location: include/net/dst.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa9c96)
Location: include/net/dst.h:205
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac38e1)
Location: include/net/dst.h:205
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b6608d)
Location: include/net/dst.h:205
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b81e62)
Location: include/net/dst.h:205
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf431a)
Location: include/net/dst.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d122d3)
Location: include/net/dst.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb8cda)
Location: include/net/dst.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed80c3)
Location: include/net/dst.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f171c0)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2ad57)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f37185)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fdc671)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81fed9bc)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_delack_max
```
```
In net/ipv4/tcp_timer.c (ffffffff81fefa07)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffd25d)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c79174)
Location: include/net/dst.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92d9c)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d893d8)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_metrics.c (c0da1778)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d83fe0)
Location: include/net/dst.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (c000000000da3030)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dd6d2)
Location: include/net/dst.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f254e)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81967975)
Location: include/net/dst.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f30d)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81921465)
Location: include/net/dst.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938dcd)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d2145)
Location: include/net/dst.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9add)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dbce5)
Location: include/net/dst.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f388c)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
</details>
</li>
</ul>

## Differences
