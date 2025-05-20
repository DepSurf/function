# Function: <code>balloon_page_dequeue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff81207340)
Location: mm/balloon_compaction.c:57
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff81207340-ffffffff8120745e: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8122cea0)
Location: mm/balloon_compaction.c:57
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff8122cea0-ffffffff8122cfd3: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8123f3c0)
Location: mm/balloon_compaction.c:57
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff8123f3c0-ffffffff8123f4f3: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8124ad10)
Location: mm/balloon_compaction.c:57
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff8124ad10-ffffffff8124ae50: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8126af80)
Location: mm/balloon_compaction.c:71
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff8126af80-ffffffff8126b0c0: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8128f970)
Location: mm/balloon_compaction.c:71
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff8128f970-ffffffff8128fab6: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812a4890)
Location: mm/balloon_compaction.c:71
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff812a4890-ffffffff812a49d6: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812bff00)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff812bff00-ffffffff812bff92: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812d1e50)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff812d1e50-ffffffff812d1ee2: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff81307be0)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff81307be0-ffffffff81307c72: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff81313910)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff81313910-ffffffff813139a2: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff81319aa0)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff81319aa0-ffffffff81319b32: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff81366290)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff81366290-ffffffff81366322: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff813e32b0)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff813e32b0-ffffffff813e334c: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8146ac30)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff8146ac30-ffffffff8146accc: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8149fac0)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff8149fac0-ffffffff8149fb5c: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff814cf210)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff814cf210-ffffffff814cf2ac: balloon_page_dequeue (STB_GLOBAL)
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
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffff800010377b48)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffff800010377b48-ffff800010377c60: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (c056350c)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
c056350c-c05635c4: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (c00000000046a200)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
c00000000046a200-c00000000046a2dc: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffe00024f99a)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffe00024f99a-ffffffe00024fa1c: balloon_page_dequeue (STB_GLOBAL)
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
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812ca430)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff812ca430-ffffffff812ca4c2: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812bb470)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff812bb470-ffffffff812bb502: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812c8240)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff812c8240-ffffffff812c82d2: balloon_page_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct page *balloon_page_dequeue(struct balloon_dev_info *b_dev_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812d8f50)
Location: mm/balloon_compaction.c:177
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff812d8f50-ffffffff812d8fe2: balloon_page_dequeue (STB_GLOBAL)
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
