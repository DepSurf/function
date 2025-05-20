# Function: <code>skb_queue_splice</code>

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
In net/xfrm/xfrm_policy.c (ffffffff817b3a54)
Location: include/linux/skbuff.h:1511
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In net/xfrm/xfrm_policy.c (ffffffff81821264)
Location: include/linux/skbuff.h:1612
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In net/xfrm/xfrm_policy.c (ffffffff81852a74)
Location: include/linux/skbuff.h:1627
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In net/xfrm/xfrm_policy.c (ffffffff81876734)
Location: include/linux/skbuff.h:1620
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff816fdd71)
Location: include/linux/skbuff.h:1702
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f6504)
Location: include/linux/skbuff.h:1702
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff8173d458)
Location: include/linux/skbuff.h:1713
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194cc44)
Location: include/linux/skbuff.h:1713
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff817603d8)
Location: include/linux/skbuff.h:1791
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197f754)
Location: include/linux/skbuff.h:1791
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff8179da39)
Location: include/linux/skbuff.h:1881
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e941c)
Location: include/linux/skbuff.h:1881
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff817c1739)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2044c)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff8188e5f5)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b10d2c)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff8189cb85)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1f45c)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff8187f7a5)
Location: include/linux/skbuff.h:1955
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0d11c)
Location: include/linux/skbuff.h:1955
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff81910915)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd033c)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff81a60e96)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d66565)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff81bec056)
Location: include/linux/skbuff.h:2193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f315d5)
Location: include/linux/skbuff.h:2193
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff81c44506)
Location: include/linux/skbuff.h:2229
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f920c5)
Location: include/linux/skbuff.h:2229
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff81cf9df6)
Location: include/linux/skbuff.h:2236
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205fe35)
Location: include/linux/skbuff.h:2236
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffff8000109dc678)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdc768)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (c0ac1e08)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (c0de59e0)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (c000000000a9d48c)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (c000000000dff0cc)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffe0006271fa)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffe000829c5c)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff81786209)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bfadc)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff81765b59)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c8cc)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff817b65b9)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2a55c)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff817cfa28)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a35aec)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
</details>
</li>
</ul>

## Differences
