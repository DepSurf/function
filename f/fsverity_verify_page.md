# Function: <code>fsverity_verify_page</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81351910)
Location: fs/verity/verify.c:187
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81351910-ffffffff81351995: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81398190)
Location: fs/verity/verify.c:189
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81398190-ffffffff813981ef: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff813a9a10)
Location: fs/verity/verify.c:189
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813a9a10-ffffffff813a9a6f: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff813b0f50)
Location: fs/verity/verify.c:189
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813b0f50-ffffffff813b0faf: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81400c30)
Location: fs/verity/verify.c:189
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81400c30-ffffffff81400c8f: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81474ca0)
Location: fs/verity/verify.c:189
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81474ca0-ffffffff81474d10: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81507070)
Location: fs/verity/verify.c:179
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81507070-ffffffff815070e0: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffff8000104137c8)
Location: fs/verity/verify.c:187
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffff8000104137c8-ffff800010413870: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (c05dfd44)
Location: fs/verity/verify.c:187
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
c05dfd44-c05dfdbc: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (c000000000521ae0)
Location: fs/verity/verify.c:187
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
c000000000521ae0-c000000000521bcc: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffe0002bb404)
Location: fs/verity/verify.c:187
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffe0002bb404-ffffffe0002bb48e: fsverity_verify_page (STB_GLOBAL)
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
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81349ef0)
Location: fs/verity/verify.c:187
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81349ef0-ffffffff81349f75: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff8133abd0)
Location: fs/verity/verify.c:187
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8133abd0-ffffffff8133ac55: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff813479c0)
Location: fs/verity/verify.c:187
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813479c0-ffffffff81347a45: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool fsverity_verify_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff8135acc0)
Location: fs/verity/verify.c:187
Inline: False
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8135acc0-ffffffff8135ad45: fsverity_verify_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
