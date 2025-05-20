# Function: <code>tcp_measure_rcv_mss</code>

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
In net/ipv4/tcp_input.c (ffffffff8176b5c6)
Location: net/ipv4/tcp_input.c:132
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff817dba46)
Location: net/ipv4/tcp_input.c:134
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff8180baa6)
Location: net/ipv4/tcp_input.c:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff8182b926)
Location: net/ipv4/tcp_input.c:149
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff818aa076)
Location: net/ipv4/tcp_input.c:135
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff818ff258)
Location: net/ipv4/tcp_input.c:155
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff8192e268)
Location: net/ipv4/tcp_input.c:156
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff81990a08)
Location: net/ipv4/tcp_input.c:162
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff819c75e8)
Location: net/ipv4/tcp_input.c:162
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void tcp_measure_rcv_mss(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:163
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81aafd00-ffffffff81aafe05: tcp_measure_rcv_mss (STB_LOCAL)
ffffffff81abac77-ffffffff81abac94: tcp_measure_rcv_mss.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void tcp_measure_rcv_mss(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:226
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
**Symbols:**

```
ffffffff81abab50-ffffffff81abac5a: tcp_measure_rcv_mss (STB_LOCAL)
ffffffff81c3264f-ffffffff81c3266c: tcp_measure_rcv_mss.cold (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff81aa8b08)
Location: net/ipv4/tcp_input.c:226
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff81b6554a)
Location: net/ipv4/tcp_input.c:227
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff81cf537a)
Location: net/ipv4/tcp_input.c:227
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff81eb9dba)
Location: net/ipv4/tcp_input.c:227
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff81f181ca)
Location: net/ipv4/tcp_input.c:227
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff81fdad1a)
Location: net/ipv4/tcp_input.c:221
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffff800010c782a0)
Location: net/ipv4/tcp_input.c:162
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (c0d87b70)
Location: net/ipv4/tcp_input.c:162
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (c000000000d839b0)
Location: net/ipv4/tcp_input.c:162
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffe0007dd2a4)
Location: net/ipv4/tcp_input.c:162
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff81967458)
Location: net/ipv4/tcp_input.c:162
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff81920f48)
Location: net/ipv4/tcp_input.c:162
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff819d1c28)
Location: net/ipv4/tcp_input.c:162
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
In net/ipv4/tcp_input.c (ffffffff819db7b8)
Location: net/ipv4/tcp_input.c:162
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
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
