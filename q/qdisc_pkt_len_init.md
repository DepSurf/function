# Function: <code>qdisc_pkt_len_init</code>

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
In net/core/dev.c (ffffffff8171ce33)
Location: net/core/dev.c:2840
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff81785582)
Location: net/core/dev.c:3039
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff817b2b92)
Location: net/core/dev.c:3037
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff817d03a2)
Location: net/core/dev.c:3117
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff81849d0f)
Location: net/core/dev.c:3144
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff81893f0b)
Location: net/core/dev.c:3171
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff818b48fb)
Location: net/core/dev.c:3415
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff8190122f)
Location: net/core/dev.c:3417
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff8193355f)
Location: net/core/dev.c:3335
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void qdisc_pkt_len_init(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a00ce0)
Location: net/core/dev.c:3693
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81a00ce0-ffffffff81a00e4c: qdisc_pkt_len_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void qdisc_pkt_len_init(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a010f0)
Location: net/core/dev.c:3723
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81a010f0-ffffffff81a0125c: qdisc_pkt_len_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void qdisc_pkt_len_init(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e7950)
Location: net/core/dev.c:3802
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff819e7950-ffffffff819e7ac9: qdisc_pkt_len_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void qdisc_pkt_len_init(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a98070)
Location: net/core/dev.c:3732
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81a98070-ffffffff81a981e9: qdisc_pkt_len_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void qdisc_pkt_len_init(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0fd20)
Location: net/core/dev.c:3738
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81c0fd20-ffffffff81c0fec9: qdisc_pkt_len_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void qdisc_pkt_len_init(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbf760)
Location: net/core/dev.c:3725
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81dbf760-ffffffff81dbf909: qdisc_pkt_len_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void qdisc_pkt_len_init(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2f410)
Location: net/core/dev.c:3685
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81e2f410-ffffffff81e2f5aa: qdisc_pkt_len_init (STB_LOCAL)
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
In net/core/dev.c (ffffffff81ef969f)
Location: net/core/dev.c:3695
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffff800010bd1668)
Location: net/core/dev.c:3335
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (c0cec2a4)
Location: net/core/dev.c:3335
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (c000000000cafa10)
Location: net/core/dev.c:3335
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffe00075bb24)
Location: net/core/dev.c:3335
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff818d355f)
Location: net/core/dev.c:3335
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff8188d3ef)
Location: net/core/dev.c:3335
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff8192455f)
Location: net/core/dev.c:3335
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff819459ef)
Location: net/core/dev.c:3335
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
</ul>
