# Function: <code>xfrm_replay_overflow_offload_esn</code>

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
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8187f5b0)
Location: net/xfrm/xfrm_replay.c:640
Inline: False
```
**Symbols:**

```
ffffffff8187f5b0-ffffffff8187f6f3: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff819006e0)
Location: net/xfrm/xfrm_replay.c:640
Inline: False
```
**Symbols:**

```
ffffffff819006e0-ffffffff81900825: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81957200)
Location: net/xfrm/xfrm_replay.c:642
Inline: False
```
**Symbols:**

```
ffffffff81957200-ffffffff81957361: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8198be40)
Location: net/xfrm/xfrm_replay.c:642
Inline: False
```
**Symbols:**

```
ffffffff8198be40-ffffffff8198bfb7: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff819f73c0)
Location: net/xfrm/xfrm_replay.c:630
Inline: False
```
**Symbols:**

```
ffffffff819f73c0-ffffffff819f753e: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81a2e010)
Location: net/xfrm/xfrm_replay.c:630
Inline: False
```
**Symbols:**

```
ffffffff81a2e010-ffffffff81a2e18e: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81b20f40)
Location: net/xfrm/xfrm_replay.c:630
Inline: False
```
**Symbols:**

```
ffffffff81b20f40-ffffffff81b2108f: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81b2f910)
Location: net/xfrm/xfrm_replay.c:634
Inline: False
```
**Symbols:**

```
ffffffff81b2f910-ffffffff81b2fa6f: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81b1d610)
Location: net/xfrm/xfrm_replay.c:634
Inline: False
```
**Symbols:**

```
ffffffff81b1d610-ffffffff81b1d798: xfrm_replay_overflow_offload_esn (STB_LOCAL)
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
In net/xfrm/xfrm_replay.c (ffffffff81be2567)
Location: net/xfrm/xfrm_replay.c:691
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
In net/xfrm/xfrm_replay.c (ffffffff81d79688)
Location: net/xfrm/xfrm_replay.c:691
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
In net/xfrm/xfrm_replay.c (ffffffff81f46118)
Location: net/xfrm/xfrm_replay.c:691
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
In net/xfrm/xfrm_replay.c (ffffffff81fa585a)
Location: net/xfrm/xfrm_replay.c:691
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
In net/xfrm/xfrm_replay.c (ffffffff82072baa)
Location: net/xfrm/xfrm_replay.c:691
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffff800010cecfd0)
Location: net/xfrm/xfrm_replay.c:630
Inline: False
```
**Symbols:**

```
ffff800010cecfd0-ffff800010ced184: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (c0df4d9c)
Location: net/xfrm/xfrm_replay.c:630
Inline: False
```
**Symbols:**

```
c0df4d9c-c0df4f5c: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (c000000000e11360)
Location: net/xfrm/xfrm_replay.c:630
Inline: False
```
**Symbols:**

```
c000000000e11360-c000000000e115a0: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffe00083a51c)
Location: net/xfrm/xfrm_replay.c:630
Inline: False
```
**Symbols:**

```
ffffffe00083a51c-ffffffe00083a656: xfrm_replay_overflow_offload_esn (STB_LOCAL)
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
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff819cd6a0)
Location: net/xfrm/xfrm_replay.c:630
Inline: False
```
**Symbols:**

```
ffffffff819cd6a0-ffffffff819cd81e: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8198a490)
Location: net/xfrm/xfrm_replay.c:630
Inline: False
```
**Symbols:**

```
ffffffff8198a490-ffffffff8198a60e: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81a38120)
Location: net/xfrm/xfrm_replay.c:630
Inline: False
```
**Symbols:**

```
ffffffff81a38120-ffffffff81a3829e: xfrm_replay_overflow_offload_esn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload_esn(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81a44180)
Location: net/xfrm/xfrm_replay.c:630
Inline: False
```
**Symbols:**

```
ffffffff81a44180-ffffffff81a44316: xfrm_replay_overflow_offload_esn (STB_LOCAL)
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
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
