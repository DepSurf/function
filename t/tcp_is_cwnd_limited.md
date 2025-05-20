# Function: <code>tcp_is_cwnd_limited</code>

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
In net/ipv4/tcp_output.c (ffffffff817769df)
Location: include/net/tcp.h:1080
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff817801f5)
Location: include/net/tcp.h:1080
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff817ac633)
Location: include/net/tcp.h:1080
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
In net/ipv4/tcp_output.c (ffffffff817e3952)
Location: include/net/tcp.h:1088
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff817ed6d5)
Location: include/net/tcp.h:1088
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff81819b93)
Location: include/net/tcp.h:1088
Inline: True
Inline callers:
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
In net/ipv4/tcp_output.c (ffffffff81813fc4)
Location: include/net/tcp.h:1143
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff8181dfe5)
Location: include/net/tcp.h:1143
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff8184b453)
Location: include/net/tcp.h:1143
Inline: True
Inline callers:
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
In net/ipv4/tcp_output.c (ffffffff8183422c)
Location: include/net/tcp.h:1178
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff8183e745)
Location: include/net/tcp.h:1178
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff8186eec3)
Location: include/net/tcp.h:1178
Inline: True
Inline callers:
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
In net/ipv4/tcp_output.c (ffffffff818b3645)
Location: include/net/tcp.h:1169
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff818bdf95)
Location: include/net/tcp.h:1169
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff818ef853)
Location: include/net/tcp.h:1169
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1186
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff81913bb5)
Location: include/net/tcp.h:1186
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff819461a5)
Location: include/net/tcp.h:1186
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1226
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff81942365)
Location: include/net/tcp.h:1226
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff81976345)
Location: include/net/tcp.h:1226
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1228
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff819a6955)
Location: include/net/tcp.h:1228
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff819e0025)
Location: include/net/tcp.h:1228
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff819dd625)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a16eb5)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1269
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_cong.c (ffffffff81acab45)
Location: include/net/tcp.h:1269
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff81b08245)
Location: include/net/tcp.h:1269
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad6ad5)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff81b16625)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1266
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac1b15)
Location: include/net/tcp.h:1266
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff81b04405)
Location: include/net/tcp.h:1266
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1259
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff81b7f835)
Location: include/net/tcp.h:1259
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff81bc67f5)
Location: include/net/tcp.h:1259
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1288
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0f775)
Location: include/net/tcp.h:1288
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff81d5bb75)
Location: include/net/tcp.h:1288
Inline: True
Inline callers:
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
In net/ipv4/tcp_output.c (ffffffff81ec3510)
Location: include/net/tcp.h:1301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed5395)
Location: include/net/tcp.h:1301
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffffffff81f26055)
Location: include/net/tcp.h:1301
Inline: True
Inline callers:
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
In net/ipv4/tcp_output.c (ffffffff81f2176c)
Location: include/net/tcp.h:1299
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_cong.c (ffffffff81f34005)
Location: include/net/tcp.h:1299
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff81f85955)
Location: include/net/tcp.h:1299
Inline: True
Inline callers:
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
In net/ipv4/tcp_output.c (ffffffff81fe56ff)
Location: include/net/tcp.h:1336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffa185)
Location: include/net/tcp.h:1336
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff8204c025)
Location: include/net/tcp.h:1336
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffff800010c9095c)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffff800010cd290c)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (c0d9f6f0)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (c0ddcc84)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (c000000000d9fa58)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (c000000000df130c)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
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
In net/ipv4/tcp_output.c (ffffffe0007e73d4)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f0788)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffe000823e38)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff8197d495)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff819b6545)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff81936f55)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff81973335)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff819e7c65)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a20fc5)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
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
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_cong.c (ffffffff819f1935)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a2c315)
Location: include/net/tcp.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
</details>
</li>
</ul>

## Differences
