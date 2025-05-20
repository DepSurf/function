# Function: <code>tcp_rate_skb_delivered</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81820f10)
Location: net/ipv4/tcp_rate.c:75
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81820f10-ffffffff81820fb6: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81841880)
Location: net/ipv4/tcp_rate.c:75
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81841880-ffffffff818418f2: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff818c10a0)
Location: net/ipv4/tcp_rate.c:75
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff818c10a0-ffffffff818c1112: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81916bf0)
Location: net/ipv4/tcp_rate.c:75
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81916bf0-ffffffff81916c62: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819453b0)
Location: net/ipv4/tcp_rate.c:77
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff819453b0-ffffffff81945439: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819a99b0)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff819a99b0-ffffffff819a9a39: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819e0670)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff819e0670-ffffffff819e06f9: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81acdc40)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81acdc40-ffffffff81acdcc9: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81ad9ca0)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81ad9ca0-ffffffff81ad9d29: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81ac4cf0)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81ac4cf0-ffffffff81ac4d7b: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81b834a0)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81b834a0-ffffffff81b8352b: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81d13af0)
Location: net/ipv4/tcp_rate.c:80
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81d13af0-ffffffff81d13bab: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81ed9af0)
Location: net/ipv4/tcp_rate.c:80
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81ed9af0-ffffffff81ed9bab: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81f38bd0)
Location: net/ipv4/tcp_rate.c:80
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81f38bd0-ffffffff81f38c8b: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81ffecb0)
Location: net/ipv4/tcp_rate.c:80
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81ffecb0-ffffffff81ffed6b: tcp_rate_skb_delivered (STB_GLOBAL)
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
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffff800010c943b0)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffff800010c943b0-ffff800010c94478: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (c0da2b60)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
c0da2b60-c0da2c78: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (c000000000da4ad0)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
c000000000da4ad0-c000000000da4b9c: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffe0007f3872)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffe0007f3872-ffffffe0007f3904: tcp_rate_skb_delivered (STB_GLOBAL)
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
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819804e0)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff819804e0-ffffffff81980569: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81939fa0)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81939fa0-ffffffff8193a029: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819eacb0)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff819eacb0-ffffffff819ead39: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_rate_skb_delivered(struct sock *sk, struct sk_buff *skb, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819f4b30)
Location: net/ipv4/tcp_rate.c:78
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff819f4b30-ffffffff819f4bb9: tcp_rate_skb_delivered (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
