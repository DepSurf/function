# Function: <code>skb_queue_splice_init</code>

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
In net/xfrm/xfrm_policy.c (ffffffff817b39e1)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
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
In net/xfrm/xfrm_policy.c (ffffffff81822f30)
Location: include/linux/skbuff.h:1628
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
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
In net/xfrm/xfrm_policy.c (ffffffff81854873)
Location: include/linux/skbuff.h:1643
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
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
In net/xfrm/xfrm_policy.c (ffffffff81878334)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
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
In net/xfrm/xfrm_policy.c (ffffffff818f8c44)
Location: include/linux/skbuff.h:1718
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff818feb22)
Location: include/linux/skbuff.h:1718
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
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
In net/xfrm/xfrm_policy.c (ffffffff8194f678)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff819556a8)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819584a3)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In net/xfrm/xfrm_policy.c (ffffffff81982cb2)
Location: include/linux/skbuff.h:1807
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a2b8)
Location: include/linux/skbuff.h:1807
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff8198d0a3)
Location: include/linux/skbuff.h:1807
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In net/xfrm/xfrm_policy.c (ffffffff819ec99f)
Location: include/linux/skbuff.h:1897
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4528)
Location: include/linux/skbuff.h:1897
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819f8913)
Location: include/linux/skbuff.h:1897
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In net/xfrm/xfrm_policy.c (ffffffff81a239af)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b1c8)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f573)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In net/xfrm/xfrm_policy.c (ffffffff81b158cc)
Location: include/linux/skbuff.h:1934
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d848)
Location: include/linux/skbuff.h:1934
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b22183)
Location: include/linux/skbuff.h:1934
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b231f8)
Location: include/linux/skbuff.h:1934
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
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
In net/xfrm/xfrm_policy.c (ffffffff81b23d27)
Location: include/linux/skbuff.h:1955
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c118)
Location: include/linux/skbuff.h:1955
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30b83)
Location: include/linux/skbuff.h:1955
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b31be8)
Location: include/linux/skbuff.h:1955
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
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
In net/xfrm/xfrm_policy.c (ffffffff81b11927)
Location: include/linux/skbuff.h:1971
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19d78)
Location: include/linux/skbuff.h:1971
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e8b3)
Location: include/linux/skbuff.h:1971
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b1f91a)
Location: include/linux/skbuff.h:1971
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
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
In net/xfrm/xfrm_policy.c (ffffffff81bd5417)
Location: include/linux/skbuff.h:2000
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde318)
Location: include/linux/skbuff.h:2000
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81be33f3)
Location: include/linux/skbuff.h:2000
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81be45ba)
Location: include/linux/skbuff.h:2000
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
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
In net/xfrm/xfrm_policy.c (ffffffff81d6bc27)
Location: include/linux/skbuff.h:2351
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81d7510f)
Location: include/linux/skbuff.h:2351
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a623)
Location: include/linux/skbuff.h:2351
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81d7ba21)
Location: include/linux/skbuff.h:2351
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
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
In net/xfrm/xfrm_policy.c (ffffffff81f36f67)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81f412d4)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81f47533)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81f48ad1)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
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
In net/xfrm/xfrm_policy.c (ffffffff81f968ed)
Location: include/linux/skbuff.h:2245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa0b64)
Location: include/linux/skbuff.h:2245
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa7003)
Location: include/linux/skbuff.h:2245
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81fa8941)
Location: include/linux/skbuff.h:2245
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
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
In net/core/skbuff.c (ffffffff81ed9417)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_purge_reason
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063cec)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff8206dec4)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff820742b3)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff82075c31)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
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
In net/xfrm/xfrm_policy.c (ffff800010ce0b34)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9a48)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffff800010cee734)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In net/xfrm/xfrm_policy.c (c0de9eb4)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (c0df1b48)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (c0df6568)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In net/xfrm/xfrm_policy.c (c000000000e02e94)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (c000000000e0d380)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (c000000000e133ac)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In net/xfrm/xfrm_policy.c (ffffffe00082f7ec)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffe0008378d4)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b8a4)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In net/xfrm/xfrm_policy.c (ffffffff819c303f)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff819ca858)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819cec03)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In net/xfrm/xfrm_policy.c (ffffffff8197fe2f)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81987648)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b9c3)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In net/xfrm/xfrm_policy.c (ffffffff81a2dabf)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81a352d8)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a39683)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In net/xfrm/xfrm_policy.c (ffffffff81a3927d)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40bf8)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a450b3)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
</details>
</li>
</ul>

## Differences
