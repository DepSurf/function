# Function: <code>secpath_set</code>

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
int secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8187df70)
Location: net/xfrm/xfrm_input.c:124
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff8187df70-ffffffff8187dfce: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff818fee20)
Location: net/xfrm/xfrm_input.c:141
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff818fee20-ffffffff818fee84: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff819558e0)
Location: net/xfrm/xfrm_input.c:148
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff819558e0-ffffffff81955944: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8198a3c0)
Location: net/xfrm/xfrm_input.c:112
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff8198a3c0-ffffffff8198a42f: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff819f46d0)
Location: net/xfrm/xfrm_input.c:114
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff819f46d0-ffffffff819f473f: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81a2b380)
Location: net/xfrm/xfrm_input.c:114
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81a2b380-ffffffff81a2b3ef: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1d590)
Location: net/xfrm/xfrm_input.c:115
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81b1d590-ffffffff81b1d605: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b2bdb0)
Location: net/xfrm/xfrm_input.c:117
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81b2bdb0-ffffffff81b2be25: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b19a20)
Location: net/xfrm/xfrm_input.c:117
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81b19a20-ffffffff81b19a95: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81bde3c0)
Location: net/xfrm/xfrm_input.c:117
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81bde3c0-ffffffff81bde435: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81d751d0)
Location: net/xfrm/xfrm_input.c:117
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81d751d0-ffffffff81d75259: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81f41860)
Location: net/xfrm/xfrm_input.c:119
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81f41860-ffffffff81f418e9: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81fa1100)
Location: net/xfrm/xfrm_input.c:119
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81fa1100-ffffffff81fa1190: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8206e420)
Location: net/xfrm/xfrm_input.c:119
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff8206e420-ffffffff8206e4b0: secpath_set (STB_GLOBAL)
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
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffff800010ce9b80)
Location: net/xfrm/xfrm_input.c:114
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffff800010ce9b80-ffff800010ce9bfc: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (c0df1d90)
Location: net/xfrm/xfrm_input.c:114
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
c0df1d90-c0df1e10: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (c000000000e0d6d0)
Location: net/xfrm/xfrm_input.c:114
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
c000000000e0d6d0-c000000000e0d78c: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffe000837ace)
Location: net/xfrm/xfrm_input.c:114
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffe000837ace-ffffffe000837b52: secpath_set (STB_GLOBAL)
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
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff819caa10)
Location: net/xfrm/xfrm_input.c:114
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff819caa10-ffffffff819caa7f: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81987800)
Location: net/xfrm/xfrm_input.c:114
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81987800-ffffffff8198786f: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81a35490)
Location: net/xfrm/xfrm_input.c:114
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81a35490-ffffffff81a354ff: secpath_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sec_path *secpath_set(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81a40d70)
Location: net/xfrm/xfrm_input.c:114
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81a40d70-ffffffff81a40ddf: secpath_set (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct sec_path *</code>
</li>
</ul>
</details>
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
