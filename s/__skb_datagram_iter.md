# Function: <code>__skb_datagram_iter</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a4d20)
Location: net/core/datagram.c:411
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff818a4d20-ffffffff818a4fdc: __skb_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/datagram.c (0)
Location: net/core/datagram.c:410
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff818ef490-ffffffff818ef71c: __skb_datagram_iter (STB_LOCAL)
ffffffff818f0471-ffffffff818f04c3: __skb_datagram_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81921440)
Location: net/core/datagram.c:410
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff81921440-ffffffff819216c1: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f55c0)
Location: net/core/datagram.c:412
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff819f55c0-ffffffff819f5899: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f5080)
Location: net/core/datagram.c:412
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff819f5080-ffffffff819f5359: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819db210)
Location: net/core/datagram.c:412
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff819db210-ffffffff819db4fa: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8a890)
Location: net/core/datagram.c:412
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff81a8a890-ffffffff81a8ab7a: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81bffe90)
Location: net/core/datagram.c:409
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff81bffe90-ffffffff81c00175: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81daf280)
Location: net/core/datagram.c:406
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff81daf280-ffffffff81daf565: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81e1f470)
Location: net/core/datagram.c:406
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff81e1f470-ffffffff81e1f7ae: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81edcb20)
Location: net/core/datagram.c:407
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff81edcb20-ffffffff81edce5e: __skb_datagram_iter (STB_LOCAL)
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
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbbac0)
Location: net/core/datagram.c:410
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffff800010bbbac0-ffff800010bbbd14: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd7e6c)
Location: net/core/datagram.c:410
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
c0cd7e6c-c0cd80f8: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c94970)
Location: net/core/datagram.c:410
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
c000000000c94970-c000000000c94d38: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074a942)
Location: net/core/datagram.c:410
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffe00074a942-ffffffe00074ab5e: __skb_datagram_iter (STB_LOCAL)
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
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c1440)
Location: net/core/datagram.c:410
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff818c1440-ffffffff818c16c1: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187b380)
Location: net/core/datagram.c:410
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff8187b380-ffffffff8187b601: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81912440)
Location: net/core/datagram.c:410
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff81912440-ffffffff819126c1: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __skb_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len, bool fault_short, size_t (*cb)(const void *, size_t, void *, struct iov_iter *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819335e0)
Location: net/core/datagram.c:410
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_hash_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff819335e0-ffffffff81933830: __skb_datagram_iter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
