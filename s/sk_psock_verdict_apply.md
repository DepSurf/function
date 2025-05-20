# Function: <code>sk_psock_verdict_apply</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e5f0a)
Location: net/core/skmsg.c:668
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff81935ae1)
Location: net/core/skmsg.c:680
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff819688f1)
Location: net/core/skmsg.c:689
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff81a3d41d)
Location: net/core/skmsg.c:749
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sk_psock_verdict_apply(struct sk_psock *psock, struct sk_buff *skb, int verdict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3f180)
Location: net/core/skmsg.c:828
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
```
**Symbols:**

```
ffffffff81a3f180-ffffffff81a3f21e: sk_psock_verdict_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sk_psock_verdict_apply(struct sk_psock *psock, struct sk_buff *skb, int verdict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4e310)
Location: net/core/skmsg.c:957
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
```
**Symbols:**

```
ffffffff81a4e310-ffffffff81a4e439: sk_psock_verdict_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sk_psock_verdict_apply(struct sk_psock *psock, struct sk_buff *skb, int verdict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b07000)
Location: net/core/skmsg.c:953
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
```
**Symbols:**

```
ffffffff81b07000-ffffffff81b07172: sk_psock_verdict_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sk_psock_verdict_apply(struct sk_psock *psock, struct sk_buff *skb, int verdict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8bbc0)
Location: net/core/skmsg.c:973
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
```
**Symbols:**

```
ffffffff81c8bbc0-ffffffff81c8bd2b: sk_psock_verdict_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sk_psock_verdict_apply(struct sk_psock *psock, struct sk_buff *skb, int verdict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e47f50)
Location: net/core/skmsg.c:980
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
```
**Symbols:**

```
ffffffff81e47f50-ffffffff81e480ca: sk_psock_verdict_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sk_psock_verdict_apply(struct sk_psock *psock, struct sk_buff *skb, int verdict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea3050)
Location: net/core/skmsg.c:970
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
```
**Symbols:**

```
ffffffff81ea3050-ffffffff81ea31d5: sk_psock_verdict_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sk_psock_verdict_apply(struct sk_psock *psock, struct sk_buff *skb, int verdict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f65370)
Location: net/core/skmsg.c:976
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
```
**Symbols:**

```
ffffffff81f65370-ffffffff81f654f5: sk_psock_verdict_apply (STB_LOCAL)
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
In net/core/skmsg.c (ffff800010c0f400)
Location: net/core/skmsg.c:689
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (c0d26928)
Location: net/core/skmsg.c:689
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (c000000000cf9fd0)
Location: net/core/skmsg.c:689
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffe00078afb8)
Location: net/core/skmsg.c:689
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff819088c1)
Location: net/core/skmsg.c:689
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff818c26d1)
Location: net/core/skmsg.c:689
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff819598f1)
Location: net/core/skmsg.c:689
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff8197bb0c)
Location: net/core/skmsg.c:689
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
