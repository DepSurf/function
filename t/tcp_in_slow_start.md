# Function: <code>tcp_in_slow_start</code>

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
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:1004
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff817801f5)
Location: include/net/tcp.h:1004
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff8178206b)
Location: include/net/tcp.h:1004
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff817ac633)
Location: include/net/tcp.h:1004
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:1023
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff817ed6d5)
Location: include/net/tcp.h:1023
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ef543)
Location: include/net/tcp.h:1023
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff818199ca)
Location: include/net/tcp.h:1023
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:1078
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff8181dfe5)
Location: include/net/tcp.h:1078
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181fd93)
Location: include/net/tcp.h:1078
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff8184b28a)
Location: include/net/tcp.h:1078
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:1113
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff8183e745)
Location: include/net/tcp.h:1113
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184052c)
Location: include/net/tcp.h:1113
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff8186ed18)
Location: include/net/tcp.h:1113
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:1104
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff818bdf95)
Location: include/net/tcp.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bfcbe)
Location: include/net/tcp.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff818ef6a8)
Location: include/net/tcp.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff81908da9)
Location: include/net/tcp.h:1121
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff81913bb5)
Location: include/net/tcp.h:1121
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915853)
Location: include/net/tcp.h:1121
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff81946008)
Location: include/net/tcp.h:1121
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff81936ff7)
Location: include/net/tcp.h:1161
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff81942365)
Location: include/net/tcp.h:1161
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff81944003)
Location: include/net/tcp.h:1161
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff819761a8)
Location: include/net/tcp.h:1161
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff8199c60f)
Location: include/net/tcp.h:1163
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff819a6955)
Location: include/net/tcp.h:1163
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a85f2)
Location: include/net/tcp.h:1163
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff819dfd29)
Location: include/net/tcp.h:1163
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff819d30c1)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff819dd625)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df2c2)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a16d19)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff81abbd2f)
Location: include/net/tcp.h:1204
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_cong.c (ffffffff81acab45)
Location: include/net/tcp.h:1204
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc867)
Location: include/net/tcp.h:1204
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff81b07fbe)
Location: include/net/tcp.h:1204
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff81ac715c)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad6ad5)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad8841)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff81b1639e)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff81ab6470)
Location: include/net/tcp.h:1201
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac1b15)
Location: include/net/tcp.h:1201
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac374f)
Location: include/net/tcp.h:1201
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff81b0417e)
Location: include/net/tcp.h:1201
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff81b73477)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff81b7f835)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b81c5f)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff81bc64be)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff81d02bc6)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0f775)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d120a6)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff81d5b7fe)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff81ec3514)
Location: include/net/tcp.h:1236
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed53aa)
Location: include/net/tcp.h:1236
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed7e86)
Location: include/net/tcp.h:1236
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff81f25cbe)
Location: include/net/tcp.h:1236
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff81f21770)
Location: include/net/tcp.h:1234
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_cong.c (ffffffff81f34022)
Location: include/net/tcp.h:1234
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f36f2d)
Location: include/net/tcp.h:1234
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff81f85cad)
Location: include/net/tcp.h:1234
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff81fe5703)
Location: include/net/tcp.h:1271
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffa1a2)
Location: include/net/tcp.h:1271
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffd01d)
Location: include/net/tcp.h:1271
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff8204c37d)
Location: include/net/tcp.h:1271
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffff800010c85c5c)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffff800010c9095c)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92bd0)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffff800010cd2e98)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (c0d94ec0)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (c0d9f6f0)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (c0da15b4)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (c0ddca24)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (c000000000d91ebc)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (c000000000d9fa58)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (c000000000da2d90)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (c000000000df1044)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffe0007e73e0)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f0788)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f23ba)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffe000823c42)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff81972f31)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff8197d495)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f132)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff819b63a9)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff8192ca01)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff81936f55)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938bf2)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff81973199)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff819dd701)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff819e7c65)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9902)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a20e29)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_output.c (ffffffff819e7381)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff819f1935)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f36b1)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a2c189)
Location: include/net/tcp.h:1184
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
</details>
</li>
</ul>

## Differences
