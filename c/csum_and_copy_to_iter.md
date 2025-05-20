# Function: <code>csum_and_copy_to_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fd3f0)
Location: lib/iov_iter.c:707
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
**Symbols:**

```
ffffffff813fd3f0-ffffffff813fd8a9: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81444040)
Location: lib/iov_iter.c:669
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
**Symbols:**

```
ffffffff81444040-ffffffff814444e4: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81462170)
Location: lib/iov_iter.c:1140
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
**Symbols:**

```
ffffffff81462170-ffffffff8146265d: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81467f10)
Location: lib/iov_iter.c:1264
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
**Symbols:**

```
ffffffff81467f10-ffffffff8146835d: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814941a0)
Location: lib/iov_iter.c:1266
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
**Symbols:**

```
ffffffff814941a0-ffffffff814945fd: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c95e0)
Location: lib/iov_iter.c:1396
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
**Symbols:**

```
ffffffff814c95e0-ffffffff814c9a39: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *csump, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814de470)
Location: lib/iov_iter.c:1470
Inline: False
```
**Symbols:**

```
ffffffff814de470-ffffffff814dea8a: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *csump, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1487
Inline: False
```
**Symbols:**

```
ffffffff8150ae60-ffffffff8150ae76: csum_and_copy_to_iter.cold (STB_LOCAL)
ffffffff8150a070-ffffffff8150a6bb: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *csump, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81528190)
Location: lib/iov_iter.c:1487
Inline: False
```
**Symbols:**

```
ffffffff81528190-ffffffff815287f9: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *csump, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81588170)
Location: lib/iov_iter.c:1522
Inline: False
```
**Symbols:**

```
ffffffff81588170-ffffffff81588699: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *_csstate, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a7dd0)
Location: lib/iov_iter.c:1527
Inline: False
```
**Symbols:**

```
ffffffff815a7dd0-ffffffff815a8241: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *_csstate, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815b30d0)
Location: lib/iov_iter.c:1792
Inline: False
```
**Symbols:**

```
ffffffff815b30d0-ffffffff815b3a43: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *_csstate, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81619380)
Location: lib/iov_iter.c:1667
Inline: False
```
**Symbols:**

```
ffffffff81619380-ffffffff81619bbd: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *_csstate, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1716
Inline: False
```
**Symbols:**

```
ffffffff81e931fc-ffffffff81e93258: csum_and_copy_to_iter.cold (STB_LOCAL)
ffffffff816e6770-ffffffff816e703b: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *_csstate, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1562
Inline: False
```
**Symbols:**

```
ffffffff8207839e-ffffffff820783e8: csum_and_copy_to_iter.cold (STB_LOCAL)
ffffffff817d6100-ffffffff817d6819: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *_csstate, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1192
Inline: False
```
**Symbols:**

```
ffffffff820f872a-ffffffff820f8770: csum_and_copy_to_iter.cold (STB_LOCAL)
ffffffff818138b0-ffffffff81813ead: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *_csstate, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/datagram.c (0)
Location: net/core/datagram.c:765
Inline: False
```
**Symbols:**

```
ffffffff81edd530-ffffffff81eddc5f: csum_and_copy_to_iter (STB_LOCAL)
ffffffff8220e0bd-ffffffff8220e0da: csum_and_copy_to_iter.cold (STB_LOCAL)
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
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *csump, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff8000106326a0)
Location: lib/iov_iter.c:1487
Inline: False
```
**Symbols:**

```
ffff8000106326a0-ffff800010632e10: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *csump, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d8844)
Location: lib/iov_iter.c:1487
Inline: False
```
**Symbols:**

```
c07d8844-c07d9044: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *csump, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d5e00)
Location: lib/iov_iter.c:1487
Inline: False
```
**Symbols:**

```
c0000000007d5e00-c0000000007d65b4: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *csump, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe000460c40)
Location: lib/iov_iter.c:1487
Inline: False
```
**Symbols:**

```
ffffffe000460c40-ffffffe000461220: csum_and_copy_to_iter (STB_GLOBAL)
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
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *csump, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81520770)
Location: lib/iov_iter.c:1487
Inline: False
```
**Symbols:**

```
ffffffff81520770-ffffffff81520dd9: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *csump, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81510a60)
Location: lib/iov_iter.c:1487
Inline: False
```
**Symbols:**

```
ffffffff81510a60-ffffffff815110c9: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *csump, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151c800)
Location: lib/iov_iter.c:1487
Inline: False
```
**Symbols:**

```
ffffffff8151c800-ffffffff8151ce69: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t csum_and_copy_to_iter(const void *addr, size_t bytes, void *csump, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81536060)
Location: lib/iov_iter.c:1487
Inline: False
```
**Symbols:**

```
ffffffff81536060-ffffffff815366d8: csum_and_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *addr</code> ➡️ <code>const void *addr</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *csump</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum *csum</code>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *_csstate</code>
</li>
<li>
<b>Param removed. </b>
<code>void *csump</code>
</li>
</ul>
</details>
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
