# Function: <code>tcp_sack_new_ofo_skb</code>

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
In net/ipv4/tcp_input.c (ffffffff81770920)
Location: net/ipv4/tcp_input.c:4161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff817df69a)
Location: net/ipv4/tcp_input.c:4219
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff8180fab2)
Location: net/ipv4/tcp_input.c:4235
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff8182f928)
Location: net/ipv4/tcp_input.c:4194
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff818af21b)
Location: net/ipv4/tcp_input.c:4164
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff81904666)
Location: net/ipv4/tcp_input.c:4245
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff8193280b)
Location: net/ipv4/tcp_input.c:4256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff81995c02)
Location: net/ipv4/tcp_input.c:4273
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
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
In net/ipv4/tcp_input.c (ffffffff819cc77c)
Location: net/ipv4/tcp_input.c:4323
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
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
In net/ipv4/tcp_input.c (ffffffff81ab35cf)
Location: net/ipv4/tcp_input.c:4346
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
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
In net/ipv4/tcp_input.c (ffffffff81abf28f)
Location: net/ipv4/tcp_input.c:4485
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_sack_new_ofo_skb(struct sock *sk, u32 seq, u32 end_seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa73d0)
Location: net/ipv4/tcp_input.c:4495
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81aa73d0-ffffffff81aa75eb: tcp_sack_new_ofo_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_sack_new_ofo_skb(struct sock *sk, u32 seq, u32 end_seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b63800)
Location: net/ipv4/tcp_input.c:4529
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81b63800-ffffffff81b63a1b: tcp_sack_new_ofo_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_sack_new_ofo_skb(struct sock *sk, u32 seq, u32 end_seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf2310)
Location: net/ipv4/tcp_input.c:4547
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81cf2310-ffffffff81cf2535: tcp_sack_new_ofo_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_sack_new_ofo_skb(struct sock *sk, u32 seq, u32 end_seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb6d00)
Location: net/ipv4/tcp_input.c:4560
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81eb6d00-ffffffff81eb6f25: tcp_sack_new_ofo_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_sack_new_ofo_skb(struct sock *sk, u32 seq, u32 end_seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f15120)
Location: net/ipv4/tcp_input.c:4565
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81f15120-ffffffff81f15341: tcp_sack_new_ofo_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_sack_new_ofo_skb(struct sock *sk, u32 seq, u32 end_seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd9780)
Location: net/ipv4/tcp_input.c:4696
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81fd9780-ffffffff81fd99a1: tcp_sack_new_ofo_skb (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffff800010c7f3f4)
Location: net/ipv4/tcp_input.c:4323
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
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
In net/ipv4/tcp_input.c (c0d8e4b0)
Location: net/ipv4/tcp_input.c:4323
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
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
In net/ipv4/tcp_input.c (c000000000d89b1c)
Location: net/ipv4/tcp_input.c:4323
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
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
In net/ipv4/tcp_input.c (ffffffe0007e15ae)
Location: net/ipv4/tcp_input.c:4323
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
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
In net/ipv4/tcp_input.c (ffffffff8196c5ec)
Location: net/ipv4/tcp_input.c:4323
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
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
In net/ipv4/tcp_input.c (ffffffff819260dc)
Location: net/ipv4/tcp_input.c:4323
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
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
In net/ipv4/tcp_input.c (ffffffff819d6dbc)
Location: net/ipv4/tcp_input.c:4323
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
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
In net/ipv4/tcp_input.c (ffffffff819e09dc)
Location: net/ipv4/tcp_input.c:4323
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
