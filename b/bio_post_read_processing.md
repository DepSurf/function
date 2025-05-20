# Function: <code>bio_post_read_processing</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813cc2e0)
Location: fs/ext4/readpage.c:128
Inline: True
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813cc2e0-ffffffff813cc37d: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff814184f7)
Location: fs/ext4/readpage.c:128
Inline: True
Inline callers:
  - fs/ext4/readpage.c:decrypt_work
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff814183c0-ffffffff8141845d: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff8142c057)
Location: fs/ext4/readpage.c:128
Inline: True
Inline callers:
  - fs/ext4/readpage.c:decrypt_work
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff8142bf20-ffffffff8142bfbd: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff81432d17)
Location: fs/ext4/readpage.c:128
Inline: True
Inline callers:
  - fs/ext4/readpage.c:decrypt_work
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff81432be0-ffffffff81432c7d: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff81486627)
Location: fs/ext4/readpage.c:128
Inline: True
Inline callers:
  - fs/ext4/readpage.c:decrypt_work
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff814863b0-ffffffff8148644d: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff81509e96)
Location: fs/ext4/readpage.c:127
Inline: True
Inline callers:
  - fs/ext4/readpage.c:decrypt_work
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff81509d30-ffffffff81509de5: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff815a4910)
Location: fs/ext4/readpage.c:125
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff815a4910-ffffffff815a49c5: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff815db2e0)
Location: fs/ext4/readpage.c:123
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff815db2e0-ffffffff815db395: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff81613bb0)
Location: fs/ext4/readpage.c:116
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff81613bb0-ffffffff81613c65: bio_post_read_processing (STB_LOCAL)
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
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffff8000104a4768)
Location: fs/ext4/readpage.c:128
Inline: True
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffff8000104a4768-ffff8000104a4830: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (c0666344)
Location: fs/ext4/readpage.c:128
Inline: True
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
c0666344-c0666408: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (c0000000005d1750)
Location: fs/ext4/readpage.c:128
Inline: True
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
c0000000005d1750-c0000000005d1864: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffe00032595a)
Location: fs/ext4/readpage.c:128
Inline: True
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffe00032595a-ffffffe000325a0a: bio_post_read_processing (STB_LOCAL)
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
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813c48c0)
Location: fs/ext4/readpage.c:128
Inline: True
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813c48c0-ffffffff813c495d: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813b5340)
Location: fs/ext4/readpage.c:128
Inline: True
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813b5340-ffffffff813b53dd: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813c1d50)
Location: fs/ext4/readpage.c:128
Inline: True
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813c1d50-ffffffff813c1ded: bio_post_read_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813d6ed0)
Location: fs/ext4/readpage.c:128
Inline: True
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813d6ed0-ffffffff813d6f6d: bio_post_read_processing (STB_LOCAL)
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
