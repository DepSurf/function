# Function: <code>udp_gro_receive_segment</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8194f1c0)
Location: net/ipv4/udp_offload.c:348
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
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
In net/ipv4/udp_offload.c (ffffffff819b39bd)
Location: net/ipv4/udp_offload.c:349
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
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
In net/ipv4/udp_offload.c (ffffffff819ea6ed)
Location: net/ipv4/udp_offload.c:349
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive_segment(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ad8000)
Location: net/ipv4/udp_offload.c:366
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff81ad8000-ffffffff81ad81c4: udp_gro_receive_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive_segment(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ae5560)
Location: net/ipv4/udp_offload.c:428
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff81ae5560-ffffffff81ae5799: udp_gro_receive_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive_segment(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ad0840)
Location: net/ipv4/udp_offload.c:428
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff81ad0840-ffffffff81ad0a72: udp_gro_receive_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive_segment(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81b8f260)
Location: net/ipv4/udp_offload.c:428
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff81b8f260-ffffffff81b8f492: udp_gro_receive_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive_segment(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81d20510)
Location: net/ipv4/udp_offload.c:456
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff81d20510-ffffffff81d207a9: udp_gro_receive_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive_segment(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ee7760)
Location: net/ipv4/udp_offload.c:457
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff81ee7760-ffffffff81ee79f9: udp_gro_receive_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive_segment(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81f46fe0)
Location: net/ipv4/udp_offload.c:464
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff81f46fe0-ffffffff81f47275: udp_gro_receive_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive_segment(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8200d120)
Location: net/ipv4/udp_offload.c:464
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff8200d120-ffffffff8200d3b5: udp_gro_receive_segment (STB_LOCAL)
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
In net/ipv4/udp_offload.c (ffff800010ca02cc)
Location: net/ipv4/udp_offload.c:349
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
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
In net/ipv4/udp_offload.c (c0dad200)
Location: net/ipv4/udp_offload.c:349
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
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
In net/ipv4/udp_offload.c (c000000000db3b28)
Location: net/ipv4/udp_offload.c:349
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
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
In net/ipv4/udp_offload.c (ffffffe0007fc9d2)
Location: net/ipv4/udp_offload.c:349
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
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
In net/ipv4/udp_offload.c (ffffffff8198a55d)
Location: net/ipv4/udp_offload.c:349
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
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
In net/ipv4/udp_offload.c (ffffffff8194401d)
Location: net/ipv4/udp_offload.c:349
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
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
In net/ipv4/udp_offload.c (ffffffff819f4d2d)
Location: net/ipv4/udp_offload.c:349
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
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
In net/ipv4/udp_offload.c (ffffffff819fef12)
Location: net/ipv4/udp_offload.c:349
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
