# Function: <code>bpf_xmit</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817da010)
Location: net/core/lwt_bpf.c:151
Inline: True
```
**Symbols:**

```
ffffffff817da010-ffffffff817da0a8: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817f8fd0)
Location: net/core/lwt_bpf.c:151
Inline: True
```
**Symbols:**

```
ffffffff817f8fd0-ffffffff817f9067: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff818768d0)
Location: net/core/lwt_bpf.c:151
Inline: True
```
**Symbols:**

```
ffffffff818768d0-ffffffff81876967: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff818c7fc0)
Location: net/core/lwt_bpf.c:151
Inline: True
```
**Symbols:**

```
ffffffff818c7fc0-ffffffff818c8054: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff818f1130)
Location: net/core/lwt_bpf.c:150
Inline: True
```
**Symbols:**

```
ffffffff818f1130-ffffffff818f11c4: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff819434a0)
Location: net/core/lwt_bpf.c:266
Inline: True
```
**Symbols:**

```
ffffffff819434a0-ffffffff81943576: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81978470)
Location: net/core/lwt_bpf.c:269
Inline: True
```
**Symbols:**

```
ffffffff81978470-ffffffff81978546: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a4cf80)
Location: net/core/lwt_bpf.c:269
Inline: False
```
**Symbols:**

```
ffffffff81a4cf80-ffffffff81a4d056: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a52c40)
Location: net/core/lwt_bpf.c:269
Inline: False
```
**Symbols:**

```
ffffffff81a52c40-ffffffff81a52d16: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a38440)
Location: net/core/lwt_bpf.c:269
Inline: False
```
**Symbols:**

```
ffffffff81a38440-ffffffff81a38516: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81aee2b0)
Location: net/core/lwt_bpf.c:269
Inline: False
```
**Symbols:**

```
ffffffff81aee2b0-ffffffff81aee386: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81c71120)
Location: net/core/lwt_bpf.c:268
Inline: False
```
**Symbols:**

```
ffffffff81c71120-ffffffff81c71246: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e291b0)
Location: net/core/lwt_bpf.c:268
Inline: False
```
**Symbols:**

```
ffffffff81e291b0-ffffffff81e292d6: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e9e7f0)
Location: net/core/lwt_bpf.c:267
Inline: False
```
**Symbols:**

```
ffffffff81e9e7f0-ffffffff81e9e903: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81f60f60)
Location: net/core/lwt_bpf.c:267
Inline: False
```
**Symbols:**

```
ffffffff81f60f60-ffffffff81f61073: bpf_xmit (STB_LOCAL)
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
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffff800010c1ef78)
Location: net/core/lwt_bpf.c:269
Inline: True
```
**Symbols:**

```
ffff800010c1ef78-ffff800010c1f074: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c0d36cd0)
Location: net/core/lwt_bpf.c:269
Inline: True
```
**Symbols:**

```
c0d36cd0-c0d36db4: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c000000000d10f00)
Location: net/core/lwt_bpf.c:269
Inline: True
```
**Symbols:**

```
c000000000d10f00-c000000000d11078: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffe0007988c0)
Location: net/core/lwt_bpf.c:269
Inline: True
```
**Symbols:**

```
ffffffe0007988c0-ffffffe000798994: bpf_xmit (STB_LOCAL)
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
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff819182e0)
Location: net/core/lwt_bpf.c:269
Inline: True
```
**Symbols:**

```
ffffffff819182e0-ffffffff819183b6: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff818d2090)
Location: net/core/lwt_bpf.c:269
Inline: True
```
**Symbols:**

```
ffffffff818d2090-ffffffff818d2166: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81969470)
Location: net/core/lwt_bpf.c:269
Inline: True
```
**Symbols:**

```
ffffffff81969470-ffffffff81969546: bpf_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bpf_xmit(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff8198b850)
Location: net/core/lwt_bpf.c:269
Inline: True
```
**Symbols:**

```
ffffffff8198b850-ffffffff8198b926: bpf_xmit (STB_LOCAL)
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
