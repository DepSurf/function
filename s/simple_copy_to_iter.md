# Function: <code>simple_copy_to_iter</code>

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
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a48b0)
Location: net/core/datagram.c:513
Inline: False
```
**Symbols:**

```
ffffffff818a48b0-ffffffff818a48e6: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818f0040)
Location: net/core/datagram.c:512
Inline: False
```
**Symbols:**

```
ffffffff818f0040-ffffffff818f0078: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81921780)
Location: net/core/datagram.c:512
Inline: False
```
**Symbols:**

```
ffffffff81921780-ffffffff819217c6: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f5570)
Location: net/core/datagram.c:516
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff819f5570-ffffffff819f55b6: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f5030)
Location: net/core/datagram.c:516
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff819f5030-ffffffff819f5076: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819db1c0)
Location: net/core/datagram.c:516
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff819db1c0-ffffffff819db206: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8a840)
Location: net/core/datagram.c:516
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff81a8a840-ffffffff81a8a886: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81bffe30)
Location: net/core/datagram.c:513
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff81bffe30-ffffffff81bffe8c: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81daf210)
Location: net/core/datagram.c:510
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff81daf210-ffffffff81daf26c: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81e1f400)
Location: net/core/datagram.c:510
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff81e1f400-ffffffff81e1f45c: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81edcab0)
Location: net/core/datagram.c:529
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/datagram.c:__skb_datagram_iter
```
**Symbols:**

```
ffffffff81edcab0-ffffffff81edcb0c: simple_copy_to_iter (STB_LOCAL)
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
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbca68)
Location: net/core/datagram.c:512
Inline: False
```
**Symbols:**

```
ffff800010bbca68-ffff800010bbcad4: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd8210)
Location: net/core/datagram.c:512
Inline: False
```
**Symbols:**

```
c0cd8210-c0cd8294: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c95ab0)
Location: net/core/datagram.c:512
Inline: False
```
**Symbols:**

```
c000000000c95ab0-c000000000c95b3c: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074b306)
Location: net/core/datagram.c:512
Inline: False
```
**Symbols:**

```
ffffffe00074b306-ffffffe00074b360: simple_copy_to_iter (STB_LOCAL)
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
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c1780)
Location: net/core/datagram.c:512
Inline: False
```
**Symbols:**

```
ffffffff818c1780-ffffffff818c17c6: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187b6c0)
Location: net/core/datagram.c:512
Inline: False
```
**Symbols:**

```
ffffffff8187b6c0-ffffffff8187b706: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81912780)
Location: net/core/datagram.c:512
Inline: False
```
**Symbols:**

```
ffffffff81912780-ffffffff819127c6: simple_copy_to_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t simple_copy_to_iter(const void *addr, size_t bytes, void *data, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81933900)
Location: net/core/datagram.c:512
Inline: False
```
**Symbols:**

```
ffffffff81933900-ffffffff81933946: simple_copy_to_iter (STB_LOCAL)
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
