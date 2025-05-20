# Function: <code>xfrm_replay_check_legacy</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xfrm_replay_check_legacy(struct xfrm_state *x, struct sk_buff *skb, __be32 net_seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_replay.c (0)
Location: net/xfrm/xfrm_replay.c:121
Inline: False
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck
  - net/xfrm/xfrm_replay.c:xfrm_replay_check
```
**Symbols:**

```
ffffffff81be1c70-ffffffff81be1cff: xfrm_replay_check_legacy (STB_LOCAL)
ffffffff81d3ef68-ffffffff81d3ef86: xfrm_replay_check_legacy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xfrm_replay_check_legacy(struct xfrm_state *x, struct sk_buff *skb, __be32 net_seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_replay.c (0)
Location: net/xfrm/xfrm_replay.c:121
Inline: False
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck
  - net/xfrm/xfrm_replay.c:xfrm_replay_check
```
**Symbols:**

```
ffffffff81d78c70-ffffffff81d78d11: xfrm_replay_check_legacy (STB_LOCAL)
ffffffff81f0b8c3-ffffffff81f0b8e1: xfrm_replay_check_legacy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xfrm_replay_check_legacy(struct xfrm_state *x, struct sk_buff *skb, __be32 net_seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_replay.c (0)
Location: net/xfrm/xfrm_replay.c:121
Inline: False
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck
  - net/xfrm/xfrm_replay.c:xfrm_replay_check
```
**Symbols:**

```
ffffffff81f45280-ffffffff81f45321: xfrm_replay_check_legacy (STB_LOCAL)
ffffffff820b311c-ffffffff820b313a: xfrm_replay_check_legacy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xfrm_replay_check_legacy(struct xfrm_state *x, struct sk_buff *skb, __be32 net_seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_replay.c (0)
Location: net/xfrm/xfrm_replay.c:121
Inline: False
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck
  - net/xfrm/xfrm_replay.c:xfrm_replay_check
```
**Symbols:**

```
ffffffff81fa4a90-ffffffff81fa4b31: xfrm_replay_check_legacy (STB_LOCAL)
ffffffff8213431a-ffffffff82134338: xfrm_replay_check_legacy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xfrm_replay_check_legacy(struct xfrm_state *x, struct sk_buff *skb, __be32 net_seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_replay.c (0)
Location: net/xfrm/xfrm_replay.c:121
Inline: False
Direct callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck
  - net/xfrm/xfrm_replay.c:xfrm_replay_check
```
**Symbols:**

```
ffffffff82071de0-ffffffff82071e81: xfrm_replay_check_legacy (STB_LOCAL)
ffffffff82215ee3-ffffffff82215f01: xfrm_replay_check_legacy.cold (STB_LOCAL)
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
