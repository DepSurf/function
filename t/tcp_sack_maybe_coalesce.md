# Function: <code>tcp_sack_maybe_coalesce</code>

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
In net/ipv4/tcp_input.c (ffffffff817709bd)
Location: net/ipv4/tcp_input.c:4136
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
In net/ipv4/tcp_input.c (ffffffff817df746)
Location: net/ipv4/tcp_input.c:4194
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
In net/ipv4/tcp_input.c (ffffffff8180fb5b)
Location: net/ipv4/tcp_input.c:4210
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
In net/ipv4/tcp_input.c (ffffffff8182fb4e)
Location: net/ipv4/tcp_input.c:4169
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
In net/ipv4/tcp_input.c (ffffffff818af40b)
Location: net/ipv4/tcp_input.c:4139
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
In net/ipv4/tcp_input.c (ffffffff81904aa4)
Location: net/ipv4/tcp_input.c:4220
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
In net/ipv4/tcp_input.c (ffffffff81932c62)
Location: net/ipv4/tcp_input.c:4231
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
In net/ipv4/tcp_input.c (ffffffff81995ca7)
Location: net/ipv4/tcp_input.c:4248
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
In net/ipv4/tcp_input.c (ffffffff819cc821)
Location: net/ipv4/tcp_input.c:4298
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_sack_maybe_coalesce(struct tcp_sock *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab1210)
Location: net/ipv4/tcp_input.c:4294
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81ab1210-ffffffff81ab12c6: tcp_sack_maybe_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_sack_maybe_coalesce(struct tcp_sock *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abc260)
Location: net/ipv4/tcp_input.c:4432
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81abc260-ffffffff81abc316: tcp_sack_maybe_coalesce (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff81aa7494)
Location: net/ipv4/tcp_input.c:4442
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
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
In net/ipv4/tcp_input.c (ffffffff81b638c4)
Location: net/ipv4/tcp_input.c:4476
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
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
In net/ipv4/tcp_input.c (ffffffff81cf23cd)
Location: net/ipv4/tcp_input.c:4494
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
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
In net/ipv4/tcp_input.c (ffffffff81eb6dbd)
Location: net/ipv4/tcp_input.c:4507
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
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
In net/ipv4/tcp_input.c (ffffffff81f151d9)
Location: net/ipv4/tcp_input.c:4512
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
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
In net/ipv4/tcp_input.c (ffffffff81fd9839)
Location: net/ipv4/tcp_input.c:4643
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
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
In net/ipv4/tcp_input.c (ffff800010c7f490)
Location: net/ipv4/tcp_input.c:4298
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
In net/ipv4/tcp_input.c (c0d8e570)
Location: net/ipv4/tcp_input.c:4298
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
In net/ipv4/tcp_input.c (c000000000d89c04)
Location: net/ipv4/tcp_input.c:4298
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
In net/ipv4/tcp_input.c (ffffffe0007e164e)
Location: net/ipv4/tcp_input.c:4298
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
In net/ipv4/tcp_input.c (ffffffff8196c691)
Location: net/ipv4/tcp_input.c:4298
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
In net/ipv4/tcp_input.c (ffffffff81926181)
Location: net/ipv4/tcp_input.c:4298
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
In net/ipv4/tcp_input.c (ffffffff819d6e61)
Location: net/ipv4/tcp_input.c:4298
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
In net/ipv4/tcp_input.c (ffffffff819e0a81)
Location: net/ipv4/tcp_input.c:4298
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
