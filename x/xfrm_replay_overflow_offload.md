# Function: <code>xfrm_replay_overflow_offload</code>

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
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8187f210)
Location: net/xfrm/xfrm_replay.c:563
Inline: False
```
**Symbols:**

```
ffffffff8187f210-ffffffff8187f34e: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81900330)
Location: net/xfrm/xfrm_replay.c:563
Inline: False
```
**Symbols:**

```
ffffffff81900330-ffffffff81900474: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81956e30)
Location: net/xfrm/xfrm_replay.c:565
Inline: False
```
**Symbols:**

```
ffffffff81956e30-ffffffff81956f84: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8198ba50)
Location: net/xfrm/xfrm_replay.c:565
Inline: False
```
**Symbols:**

```
ffffffff8198ba50-ffffffff8198bbb8: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff819f6fa0)
Location: net/xfrm/xfrm_replay.c:553
Inline: False
```
**Symbols:**

```
ffffffff819f6fa0-ffffffff819f712a: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81a2dbf0)
Location: net/xfrm/xfrm_replay.c:553
Inline: False
```
**Symbols:**

```
ffffffff81a2dbf0-ffffffff81a2dd7a: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81b21470)
Location: net/xfrm/xfrm_replay.c:553
Inline: False
```
**Symbols:**

```
ffffffff81b21470-ffffffff81b215e4: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81b2fe10)
Location: net/xfrm/xfrm_replay.c:555
Inline: False
```
**Symbols:**

```
ffffffff81b2fe10-ffffffff81b2ffaf: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81b1d9b0)
Location: net/xfrm/xfrm_replay.c:555
Inline: False
```
**Symbols:**

```
ffffffff81b1d9b0-ffffffff81b1db50: xfrm_replay_overflow_offload (STB_LOCAL)
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
In net/xfrm/xfrm_replay.c (ffffffff81be23c3)
Location: net/xfrm/xfrm_replay.c:612
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
In net/xfrm/xfrm_replay.c (ffffffff81d794d5)
Location: net/xfrm/xfrm_replay.c:612
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
In net/xfrm/xfrm_replay.c (ffffffff81f45f65)
Location: net/xfrm/xfrm_replay.c:612
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
In net/xfrm/xfrm_replay.c (ffffffff81fa5779)
Location: net/xfrm/xfrm_replay.c:612
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
In net/xfrm/xfrm_replay.c (ffffffff82072ac9)
Location: net/xfrm/xfrm_replay.c:612
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
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffff800010ceca90)
Location: net/xfrm/xfrm_replay.c:553
Inline: False
```
**Symbols:**

```
ffff800010ceca90-ffff800010cecc28: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (c0df490c)
Location: net/xfrm/xfrm_replay.c:553
Inline: False
```
**Symbols:**

```
c0df490c-c0df4aa8: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (c000000000e10cc0)
Location: net/xfrm/xfrm_replay.c:553
Inline: False
```
**Symbols:**

```
c000000000e10cc0-c000000000e10ee4: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffe00083a0aa)
Location: net/xfrm/xfrm_replay.c:553
Inline: False
```
**Symbols:**

```
ffffffe00083a0aa-ffffffe00083a1e4: xfrm_replay_overflow_offload (STB_LOCAL)
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
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff819cd280)
Location: net/xfrm/xfrm_replay.c:553
Inline: False
```
**Symbols:**

```
ffffffff819cd280-ffffffff819cd40a: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8198a070)
Location: net/xfrm/xfrm_replay.c:553
Inline: False
```
**Symbols:**

```
ffffffff8198a070-ffffffff8198a1fa: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81a37d00)
Location: net/xfrm/xfrm_replay.c:553
Inline: False
```
**Symbols:**

```
ffffffff81a37d00-ffffffff81a37e8a: xfrm_replay_overflow_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xfrm_replay_overflow_offload(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81a44320)
Location: net/xfrm/xfrm_replay.c:553
Inline: False
```
**Symbols:**

```
ffffffff81a44320-ffffffff81a444ab: xfrm_replay_overflow_offload (STB_LOCAL)
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
