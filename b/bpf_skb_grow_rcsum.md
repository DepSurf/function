# Function: <code>bpf_skb_grow_rcsum</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cb5cd)
Location: net/core/filter.c:2130
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
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
In net/core/filter.c (ffffffff817eade3)
Location: net/core/filter.c:2287
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
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
In net/core/filter.c (ffffffff818678be)
Location: net/core/filter.c:2352
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff *skb, unsigned int new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b56c0)
Location: net/core/filter.c:2894
Inline: False
Direct callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
**Symbols:**

```
ffffffff818b56c0-ffffffff818b578e: bpf_skb_grow_rcsum (STB_LOCAL)
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
In net/core/filter.c (ffffffff818dc54f)
Location: net/core/filter.c:3082
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In net/core/filter.c (ffffffff8192965f)
Location: net/core/filter.c:3217
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff *skb, unsigned int new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81955d10)
Location: net/core/filter.c:3219
Inline: False
Direct callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
**Symbols:**

```
ffffffff81955d10-ffffffff81955dd2: bpf_skb_grow_rcsum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff *skb, unsigned int new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2d580)
Location: net/core/filter.c:3261
Inline: False
Direct callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
**Symbols:**

```
ffffffff81a2d580-ffffffff81a2d641: bpf_skb_grow_rcsum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff *skb, unsigned int new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2ef40)
Location: net/core/filter.c:3668
Inline: False
Direct callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
**Symbols:**

```
ffffffff81a2ef40-ffffffff81a2f001: bpf_skb_grow_rcsum (STB_LOCAL)
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
In net/core/filter.c (ffffffff81a191e7)
Location: net/core/filter.c:3669
Inline: True
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
In net/core/filter.c (ffffffff81ac7497)
Location: net/core/filter.c:3638
Inline: True
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
In net/core/filter.c (ffffffff81c43d1e)
Location: net/core/filter.c:3639
Inline: True
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
In net/core/filter.c (ffffffff81df7f0e)
Location: net/core/filter.c:3649
Inline: True
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
In net/core/filter.c (ffffffff81e675f0)
Location: net/core/filter.c:3694
Inline: True
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
In net/core/filter.c (ffffffff81f267b0)
Location: net/core/filter.c:3728
Inline: True
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
In net/core/filter.c (ffff800010bfd11c)
Location: net/core/filter.c:3219
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In net/core/filter.c (c0d17718)
Location: net/core/filter.c:3219
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In net/core/filter.c (c000000000ce55e0)
Location: net/core/filter.c:3219
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In net/core/filter.c (ffffffe00077fb22)
Location: net/core/filter.c:3219
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff *skb, unsigned int new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f5ce0)
Location: net/core/filter.c:3219
Inline: False
Direct callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
**Symbols:**

```
ffffffff818f5ce0-ffffffff818f5da2: bpf_skb_grow_rcsum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff *skb, unsigned int new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818afb10)
Location: net/core/filter.c:3219
Inline: False
Direct callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
**Symbols:**

```
ffffffff818afb10-ffffffff818afbd2: bpf_skb_grow_rcsum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff *skb, unsigned int new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81946d10)
Location: net/core/filter.c:3219
Inline: False
Direct callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
**Symbols:**

```
ffffffff81946d10-ffffffff81946dd2: bpf_skb_grow_rcsum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff *skb, unsigned int new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81968620)
Location: net/core/filter.c:3219
Inline: False
Direct callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
**Symbols:**

```
ffffffff81968620-ffffffff819686e2: bpf_skb_grow_rcsum (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
