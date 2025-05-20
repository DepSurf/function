# Function: <code>neigh_fill_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81726ae0)
Location: net/core/neighbour.c:2148
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81726ae0-ffffffff81726daf: neigh_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81790600)
Location: net/core/neighbour.c:2146
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81790600-ffffffff817908cf: neigh_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817bdeb0)
Location: net/core/neighbour.c:2148
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff817bdeb0-ffffffff817be17f: neigh_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817dc910)
Location: net/core/neighbour.c:2198
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff817dc910-ffffffff817dcbe1: neigh_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818574e0)
Location: net/core/neighbour.c:2198
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff818574e0-ffffffff818577b1: neigh_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2217
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff818a2680-ffffffff818a2936: neigh_fill_info (STB_LOCAL)
ffffffff818a5716-ffffffff818a5722: neigh_fill_info.cold.57 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2404
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff818c5860-ffffffff818c5b4b: neigh_fill_info (STB_LOCAL)
ffffffff818c8ccd-ffffffff818c8cd9: neigh_fill_info.cold.66 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2425
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff819118b0-ffffffff81911b9e: neigh_fill_info (STB_LOCAL)
ffffffff8191588a-ffffffff819158b0: neigh_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2422
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81943f20-ffffffff8194420c: neigh_fill_info (STB_LOCAL)
ffffffff81947ea9-ffffffff81947eb5: neigh_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2426
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_table
```
**Symbols:**

```
ffffffff81a13f90-ffffffff81a14275: neigh_fill_info (STB_LOCAL)
ffffffff81a1808f-ffffffff81a1809b: neigh_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2428
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_table
```
**Symbols:**

```
ffffffff81a142b0-ffffffff81a1458e: neigh_fill_info (STB_LOCAL)
ffffffff81c315f7-ffffffff81c31603: neigh_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2432
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff819fac40-ffffffff819faf1d: neigh_fill_info (STB_LOCAL)
ffffffff81c23900-ffffffff81c2390c: neigh_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2432
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_table
```
**Symbols:**

```
ffffffff81aac880-ffffffff81aacb5d: neigh_fill_info (STB_LOCAL)
ffffffff81d36b39-ffffffff81d36b45: neigh_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2522
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_table
```
**Symbols:**

```
ffffffff81c257d0-ffffffff81c25b44: neigh_fill_info (STB_LOCAL)
ffffffff81f03436-ffffffff81f03442: neigh_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81dd7a10)
Location: net/core/neighbour.c:2571
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_table
```
**Symbols:**

```
ffffffff81dd7a10-ffffffff81dd7d90: neigh_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81e48820)
Location: net/core/neighbour.c:2550
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_table
```
**Symbols:**

```
ffffffff81e48820-ffffffff81e48af8: neigh_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81f073e0)
Location: net/core/neighbour.c:2562
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_table
```
**Symbols:**

```
ffffffff81f073e0-ffffffff81f076b8: neigh_fill_info (STB_LOCAL)
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
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be3d98)
Location: net/core/neighbour.c:2422
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffff800010be3d98-ffff800010be40d8: neigh_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0cfe2c0)
Location: net/core/neighbour.c:2422
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
c0cfe2c0-c0cfe588: neigh_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc71e0)
Location: net/core/neighbour.c:2422
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
c000000000cc71e0-c000000000cc7570: neigh_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe00076a826)
Location: net/core/neighbour.c:2422
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffe00076a826-ffffffe00076aa40: neigh_fill_info (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2422
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff818e3ef0-ffffffff818e41dc: neigh_fill_info (STB_LOCAL)
ffffffff818e7e79-ffffffff818e7e85: neigh_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2422
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff8189dd30-ffffffff8189e01c: neigh_fill_info (STB_LOCAL)
ffffffff818a1cb9-ffffffff818a1cc5: neigh_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2422
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81934f20-ffffffff8193520c: neigh_fill_info (STB_LOCAL)
ffffffff81938ea9-ffffffff81938eb5: neigh_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int neigh_fill_info(struct sk_buff *skb, struct neighbour *neigh, u32 pid, u32 seq, int type, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:2422
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
**Symbols:**

```
ffffffff81956630-ffffffff8195691c: neigh_fill_info (STB_LOCAL)
ffffffff8195a6b9-ffffffff8195a6c5: neigh_fill_info.cold (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
