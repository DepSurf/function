# Function: <code>skb_gro_receive_list</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_gro_receive_list(struct sk_buff *p, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f2790)
Location: net/core/skbuff.c:3708
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
**Symbols:**

```
ffffffff819f2790-ffffffff819f2813: skb_gro_receive_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_gro_receive_list(struct sk_buff *p, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f2780)
Location: net/core/skbuff.c:3776
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
**Symbols:**

```
ffffffff819f2780-ffffffff819f2803: skb_gro_receive_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_gro_receive_list(struct sk_buff *p, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d89b0)
Location: net/core/skbuff.c:3861
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
**Symbols:**

```
ffffffff819d89b0-ffffffff819d8a37: skb_gro_receive_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_gro_receive_list(struct sk_buff *p, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a88940)
Location: net/core/skbuff.c:3921
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
**Symbols:**

```
ffffffff81a88940-ffffffff81a889cf: skb_gro_receive_list (STB_GLOBAL)
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
In net/ipv4/udp_offload.c (ffffffff81d206ba)
Location: net/ipv4/udp_offload.c:428
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
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
In net/ipv4/udp_offload.c (ffffffff81ee790a)
Location: net/ipv4/udp_offload.c:429
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
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
In net/ipv4/udp_offload.c (ffffffff81f47186)
Location: net/ipv4/udp_offload.c:436
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
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
In net/ipv4/udp_offload.c (ffffffff8200d2c6)
Location: net/ipv4/udp_offload.c:436
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
