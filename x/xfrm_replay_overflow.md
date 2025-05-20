# Function: <code>xfrm_replay_overflow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xfrm_replay_overflow(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff817bd140)
Location: net/xfrm/xfrm_replay.c:95
Inline: True
```
**Symbols:**

```
ffffffff817bd140-ffffffff817bd1ca: xfrm_replay_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xfrm_replay_overflow(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8182a280)
Location: net/xfrm/xfrm_replay.c:95
Inline: True
```
**Symbols:**

```
ffffffff8182a280-ffffffff8182a30a: xfrm_replay_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xfrm_replay_overflow(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8185bc50)
Location: net/xfrm/xfrm_replay.c:95
Inline: True
```
**Symbols:**

```
ffffffff8185bc50-ffffffff8185bcda: xfrm_replay_overflow (STB_LOCAL)
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
In net/xfrm/xfrm_replay.c (ffffffff8187f243)
Location: net/xfrm/xfrm_replay.c:96
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffff81900363)
Location: net/xfrm/xfrm_replay.c:96
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffff81956ee2)
Location: net/xfrm/xfrm_replay.c:96
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffff8198bb0b)
Location: net/xfrm/xfrm_replay.c:96
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffff819f7098)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffff81a2dce8)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffff81b21595)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffff81b2ff44)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffff81b1dae5)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xfrm_replay_overflow(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81be2380)
Location: net/xfrm/xfrm_replay.c:740
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
**Symbols:**

```
ffffffff81be2380-ffffffff81be2786: xfrm_replay_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xfrm_replay_overflow(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81d79490)
Location: net/xfrm/xfrm_replay.c:740
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
**Symbols:**

```
ffffffff81d79490-ffffffff81d798b3: xfrm_replay_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xfrm_replay_overflow(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81f45f20)
Location: net/xfrm/xfrm_replay.c:740
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
**Symbols:**

```
ffffffff81f45f20-ffffffff81f46346: xfrm_replay_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xfrm_replay_overflow(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81fa5740)
Location: net/xfrm/xfrm_replay.c:740
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
**Symbols:**

```
ffffffff81fa5740-ffffffff81fa5c61: xfrm_replay_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xfrm_replay_overflow(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff82072a90)
Location: net/xfrm/xfrm_replay.c:740
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
**Symbols:**

```
ffffffff82072a90-ffffffff82072fb1: xfrm_replay_overflow (STB_GLOBAL)
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
In net/xfrm/xfrm_replay.c (ffff800010cecb6c)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (c0df4a10)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (c000000000e10db0)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffe00083a16e)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffff819cd378)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffff8198a168)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffff81a37df8)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
In net/xfrm/xfrm_replay.c (ffffffff81a44402)
Location: net/xfrm/xfrm_replay.c:84
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
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
