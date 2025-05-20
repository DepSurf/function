# Function: <code>audit_get_sk</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811367ae)
Location: kernel/audit.c:259
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff8114313e)
Location: kernel/audit.c:259
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff81151aaa)
Location: kernel/audit.c:302
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff8115e760)
Location: kernel/audit.c:298
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff8116ad7d)
Location: kernel/audit.c:285
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff81176c28)
Location: kernel/audit.c:285
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff811866a6)
Location: kernel/audit.c:286
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff8118384b)
Location: kernel/audit.c:291
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff811848bb)
Location: kernel/audit.c:291
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff811acd2b)
Location: kernel/audit.c:291
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff811de93c)
Location: kernel/audit.c:293
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff812244fc)
Location: kernel/audit.c:293
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff8123aacc)
Location: kernel/audit.c:293
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff812547bc)
Location: kernel/audit.c:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffff8000101ebbe0)
Location: kernel/audit.c:285
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (c042b7f0)
Location: kernel/audit.c:285
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (c00000000025d220)
Location: kernel/audit.c:285
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffe000160326)
Location: kernel/audit.c:285
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff8116f248)
Location: kernel/audit.c:285
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff811623e8)
Location: kernel/audit.c:285
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
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
In kernel/audit.c (ffffffff8116d018)
Location: kernel/audit.c:285
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct sock *audit_get_sk(const struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81178075)
Location: kernel/audit.c:285
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81178030-ffffffff8117806b: audit_get_sk (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
</ul>
