# Function: <code>xfrm_replay_overflow_esn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xfrm_replay_overflow_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff817bc930)
Location: net/xfrm/xfrm_replay.c:405
Inline: False
```
**Symbols:**

```
ffffffff817bc930-ffffffff817bc9ce: xfrm_replay_overflow_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xfrm_replay_overflow_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81829850)
Location: net/xfrm/xfrm_replay.c:405
Inline: False
```
**Symbols:**

```
ffffffff81829850-ffffffff818298ee: xfrm_replay_overflow_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xfrm_replay_overflow_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8185b220)
Location: net/xfrm/xfrm_replay.c:405
Inline: False
```
**Symbols:**

```
ffffffff8185b220-ffffffff8185b2be: xfrm_replay_overflow_esn (STB_LOCAL)
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
In net/xfrm/xfrm_replay.c (ffffffff8187f5ef)
Location: net/xfrm/xfrm_replay.c:406
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (ffffffff8190071f)
Location: net/xfrm/xfrm_replay.c:406
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (ffffffff819572fb)
Location: net/xfrm/xfrm_replay.c:406
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (ffffffff8198bf51)
Location: net/xfrm/xfrm_replay.c:406
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (ffffffff819f74da)
Location: net/xfrm/xfrm_replay.c:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (ffffffff81a2e12a)
Location: net/xfrm/xfrm_replay.c:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm_replay_overflow_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81b20d30)
Location: net/xfrm/xfrm_replay.c:394
Inline: False
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
```
**Symbols:**

```
ffffffff81b20d30-ffffffff81b20dd9: xfrm_replay_overflow_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm_replay_overflow_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81b2f660)
Location: net/xfrm/xfrm_replay.c:396
Inline: False
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
```
**Symbols:**

```
ffffffff81b2f660-ffffffff81b2f714: xfrm_replay_overflow_esn (STB_LOCAL)
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
In net/xfrm/xfrm_replay.c (ffffffff81b1d739)
Location: net/xfrm/xfrm_replay.c:396
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (ffffffff81be265e)
Location: net/xfrm/xfrm_replay.c:422
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
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
In net/xfrm/xfrm_replay.c (ffffffff81d7978b)
Location: net/xfrm/xfrm_replay.c:422
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
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
In net/xfrm/xfrm_replay.c (ffffffff81f4621e)
Location: net/xfrm/xfrm_replay.c:422
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
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
In net/xfrm/xfrm_replay.c (ffffffff81fa5b6b)
Location: net/xfrm/xfrm_replay.c:422
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
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
In net/xfrm/xfrm_replay.c (ffffffff82072ebb)
Location: net/xfrm/xfrm_replay.c:422
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
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
In net/xfrm/xfrm_replay.c (ffff800010ced108)
Location: net/xfrm/xfrm_replay.c:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (c0df4e9c)
Location: net/xfrm/xfrm_replay.c:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (c000000000e11500)
Location: net/xfrm/xfrm_replay.c:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (ffffffe00083a5fe)
Location: net/xfrm/xfrm_replay.c:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (ffffffff819cd7ba)
Location: net/xfrm/xfrm_replay.c:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (ffffffff8198a5aa)
Location: net/xfrm/xfrm_replay.c:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (ffffffff81a3823a)
Location: net/xfrm/xfrm_replay.c:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
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
In net/xfrm/xfrm_replay.c (ffffffff81a442ae)
Location: net/xfrm/xfrm_replay.c:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
