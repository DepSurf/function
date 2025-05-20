# Function: <code>tcp_skb_shift</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198f60e)
Location: net/ipv4/tcp_input.c:1375
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81992bf0-ffffffff81992c1f: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c634e)
Location: net/ipv4/tcp_input.c:1378
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff819c9740-ffffffff819c976f: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab5acb)
Location: net/ipv4/tcp_input.c:1380
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
**Symbols:**

```
ffffffff81ab5920-ffffffff81ab594f: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac0e2d)
Location: net/ipv4/tcp_input.c:1486
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
**Symbols:**

```
ffffffff81ac0c80-ffffffff81ac0caf: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aabdde)
Location: net/ipv4/tcp_input.c:1486
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
**Symbols:**

```
ffffffff81aabc30-ffffffff81aabc5f: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b6822d)
Location: net/ipv4/tcp_input.c:1518
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
**Symbols:**

```
ffffffff81b68070-ffffffff81b6809f: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf73db)
Location: net/ipv4/tcp_input.c:1527
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
**Symbols:**

```
ffffffff81cf71b0-ffffffff81cf71f7: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebbe6b)
Location: net/ipv4/tcp_input.c:1526
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
**Symbols:**

```
ffffffff81ebbc30-ffffffff81ebbc77: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1a2f0)
Location: net/ipv4/tcp_input.c:1525
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
**Symbols:**

```
ffffffff81f1a0b0-ffffffff81f1a0f7: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fdeac0)
Location: net/ipv4/tcp_input.c:1559
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
**Symbols:**

```
ffffffff81fde880-ffffffff81fde8c7: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c79c24)
Location: net/ipv4/tcp_input.c:1378
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffff800010c7c650-ffff800010c7c6d4: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8a264)
Location: net/ipv4/tcp_input.c:1378
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
c0d8b5cc-c0d8b61c: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d81e14)
Location: net/ipv4/tcp_input.c:1378
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
c000000000d86220-c000000000d86298: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dbe80)
Location: net/ipv4/tcp_input.c:1378
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffe0007def26-ffffffe0007def96: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819661be)
Location: net/ipv4/tcp_input.c:1378
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff819695b0-ffffffff819695df: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191fcae)
Location: net/ipv4/tcp_input.c:1378
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff819230a0-ffffffff819230cf: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d098e)
Location: net/ipv4/tcp_input.c:1378
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff819d3d80-ffffffff819d3daf: tcp_skb_shift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tcp_skb_shift(struct sk_buff *to, struct sk_buff *from, int pcount, int shiftlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819da51e)
Location: net/ipv4/tcp_input.c:1378
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff819dd960-ffffffff819dd98f: tcp_skb_shift (STB_GLOBAL)
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
