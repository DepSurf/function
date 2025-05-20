# Function: <code>udp_set_dev_scratch</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void udp_set_dev_scratch(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81848080)
Location: net/ipv4/udp.c:1168
Inline: False
Direct callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff81848080-ffffffff81848105: udp_set_dev_scratch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void udp_set_dev_scratch(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c7ae0)
Location: net/ipv4/udp.c:1172
Inline: False
Direct callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff818c7ae0-ffffffff818c7b5e: udp_set_dev_scratch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void udp_set_dev_scratch(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191ca40)
Location: net/ipv4/udp.c:1242
Inline: False
Direct callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff8191ca40-ffffffff8191cabe: udp_set_dev_scratch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void udp_set_dev_scratch(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194afc0)
Location: net/ipv4/udp.c:1310
Inline: False
Direct callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff8194afc0-ffffffff8194b04d: udp_set_dev_scratch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void udp_set_dev_scratch(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819af620)
Location: net/ipv4/udp.c:1297
Inline: False
Direct callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff819af620-ffffffff819af6ad: udp_set_dev_scratch (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff819e7f57)
Location: net/ipv4/udp.c:1321
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffff81ad5e67)
Location: net/ipv4/udp.c:1327
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffff81ae2447)
Location: net/ipv4/udp.c:1377
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffff81acd367)
Location: net/ipv4/udp.c:1396
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffff81b8bd27)
Location: net/ipv4/udp.c:1397
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffff81d189fa)
Location: net/ipv4/udp.c:1397
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffff81ee188a)
Location: net/ipv4/udp.c:1408
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffff81f412ba)
Location: net/ipv4/udp.c:1380
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffff82006f0a)
Location: net/ipv4/udp.c:1355
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffff800010c9c468)
Location: net/ipv4/udp.c:1321
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (c0da7644)
Location: net/ipv4/udp.c:1321
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (c000000000dae920)
Location: net/ipv4/udp.c:1321
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffe0007fa4ca)
Location: net/ipv4/udp.c:1321
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffff81987dc7)
Location: net/ipv4/udp.c:1321
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffff81941887)
Location: net/ipv4/udp.c:1321
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffff819f2597)
Location: net/ipv4/udp.c:1321
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/ipv4/udp.c (ffffffff819fc3e7)
Location: net/ipv4/udp.c:1321
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
