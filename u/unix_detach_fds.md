# Function: <code>unix_detach_fds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (ffffffff817be530)
Location: net/unix/af_unix.c:1491
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_destruct_scm
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff817be530-ffffffff817be57d: unix_detach_fds.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (ffffffff8182b4d0)
Location: net/unix/af_unix.c:1479
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_destruct_scm
```
**Symbols:**

```
ffffffff8182b4d0-ffffffff8182b51d: unix_detach_fds.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (ffffffff8185cef0)
Location: net/unix/af_unix.c:1484
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_destruct_scm
```
**Symbols:**

```
ffffffff8185cef0-ffffffff8185cf3d: unix_detach_fds.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (ffffffff81881700)
Location: net/unix/af_unix.c:1491
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_destruct_scm
```
**Symbols:**

```
ffffffff81881700-ffffffff8188174d: unix_detach_fds.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (ffffffff819028a0)
Location: net/unix/af_unix.c:1492
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_destruct_scm
```
**Symbols:**

```
ffffffff819028a0-ffffffff819028ed: unix_detach_fds.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (ffffffff81958d10)
Location: net/unix/af_unix.c:1482
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_destruct_scm
```
**Symbols:**

```
ffffffff81958d10-ffffffff81958d5d: unix_detach_fds.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198d8c0)
Location: net/unix/af_unix.c:1499
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_destruct_scm
```
**Symbols:**

```
ffffffff8198d8c0-ffffffff8198d90d: unix_detach_fds.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff819fe090)
Location: net/unix/scm.c:125
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/scm.c:unix_destruct_scm
```
**Symbols:**

```
ffffffff819fe090-ffffffff819fe0e0: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81a34c80)
Location: net/unix/scm.c:125
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/scm.c:unix_destruct_scm
```
**Symbols:**

```
ffffffff81a34c80-ffffffff81a34cd0: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81b29b64)
Location: net/unix/scm.c:125
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81b29ac0-ffffffff81b29b0d: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81b3849c)
Location: net/unix/scm.c:126
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81b383f0-ffffffff81b3843d: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81b2613c)
Location: net/unix/scm.c:126
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81b26090-ffffffff81b260dd: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81bebdac)
Location: net/unix/scm.c:128
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81bebd00-ffffffff81bebd4d: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81d842ac)
Location: net/unix/scm.c:128
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81d84200-ffffffff81d84259: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81f51b6c)
Location: net/unix/scm.c:128
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81f51ab0-ffffffff81f51b09: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81fb153f)
Location: net/unix/scm.c:129
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81fb1460-ffffffff81fb14db: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff8207ec5f)
Location: net/unix/scm.c:127
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff8207eb80-ffffffff8207ebfb: unix_detach_fds (STB_GLOBAL)
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
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffff800010cf5540)
Location: net/unix/scm.c:125
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/scm.c:unix_destruct_scm
```
**Symbols:**

```
ffff800010cf5540-ffff800010cf55a8: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (c0dfbff8)
Location: net/unix/scm.c:125
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/scm.c:unix_destruct_scm
```
**Symbols:**

```
c0dfbff8-c0dfc054: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (c000000000e1b700)
Location: net/unix/scm.c:125
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/scm.c:unix_destruct_scm
```
**Symbols:**

```
c000000000e1b700-c000000000e1b7a0: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffe000840ffc)
Location: net/unix/scm.c:125
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/scm.c:unix_destruct_scm
```
**Symbols:**

```
ffffffe000840ffc-ffffffe000841060: unix_detach_fds (STB_GLOBAL)
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
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff819d4310)
Location: net/unix/scm.c:125
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/scm.c:unix_destruct_scm
```
**Symbols:**

```
ffffffff819d4310-ffffffff819d4360: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff819910d0)
Location: net/unix/scm.c:125
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/scm.c:unix_destruct_scm
```
**Symbols:**

```
ffffffff819910d0-ffffffff81991120: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81a3ed90)
Location: net/unix/scm.c:125
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/scm.c:unix_destruct_scm
```
**Symbols:**

```
ffffffff81a3ed90-ffffffff81a3ede0: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unix_detach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81a4a850)
Location: net/unix/scm.c:125
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/scm.c:unix_destruct_scm
```
**Symbols:**

```
ffffffff81a4a850-ffffffff81a4a8a0: unix_detach_fds (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
