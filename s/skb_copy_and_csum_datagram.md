# Function: <code>skb_copy_and_csum_datagram</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int skb_copy_and_csum_datagram(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, __wsum *csump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8170d8a0)
Location: net/core/datagram.c:569
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
**Symbols:**

```
ffffffff8170d8a0-ffffffff8170dbff: skb_copy_and_csum_datagram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int skb_copy_and_csum_datagram(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, __wsum *csump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81774ef0)
Location: net/core/datagram.c:591
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
**Symbols:**

```
ffffffff81774ef0-ffffffff81775214: skb_copy_and_csum_datagram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skb_copy_and_csum_datagram(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, __wsum *csump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817a21f0)
Location: net/core/datagram.c:611
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
**Symbols:**

```
ffffffff817a21f0-ffffffff817a2506: skb_copy_and_csum_datagram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skb_copy_and_csum_datagram(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, __wsum *csump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817bfa50)
Location: net/core/datagram.c:636
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
**Symbols:**

```
ffffffff817bfa50-ffffffff817bfd35: skb_copy_and_csum_datagram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skb_copy_and_csum_datagram(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, __wsum *csump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81839600)
Location: net/core/datagram.c:650
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
**Symbols:**

```
ffffffff81839600-ffffffff818398e5: skb_copy_and_csum_datagram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_copy_and_csum_datagram(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, __wsum *csump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81883d30)
Location: net/core/datagram.c:648
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
**Symbols:**

```
ffffffff81883d30-ffffffff81884025: skb_copy_and_csum_datagram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a50fa)
Location: net/core/datagram.c:692
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffff818efc7d)
Location: net/core/datagram.c:691
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffff81921c9d)
Location: net/core/datagram.c:691
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffff819f59bd)
Location: net/core/datagram.c:695
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f5461)
Location: net/core/datagram.c:720
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819db601)
Location: net/core/datagram.c:720
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffff81a8ae71)
Location: net/core/datagram.c:720
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffff81c004ce)
Location: net/core/datagram.c:718
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffff81daf8fe)
Location: net/core/datagram.c:720
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffff81e1fb6e)
Location: net/core/datagram.c:728
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffff81edd21e)
Location: net/core/datagram.c:801
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffff800010bbc340)
Location: net/core/datagram.c:691
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (c0cd8798)
Location: net/core/datagram.c:691
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (c000000000c9561c)
Location: net/core/datagram.c:691
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffe00074b066)
Location: net/core/datagram.c:691
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffff818c1c9d)
Location: net/core/datagram.c:691
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffff8187bbdd)
Location: net/core/datagram.c:691
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffff81912c9d)
Location: net/core/datagram.c:691
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
In net/core/datagram.c (ffffffff81933e1d)
Location: net/core/datagram.c:691
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
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
</ul>
