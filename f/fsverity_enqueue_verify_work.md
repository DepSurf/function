# Function: <code>fsverity_enqueue_verify_work</code>

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
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81351110)
Location: fs/verity/verify.c:253
Inline: False
```
**Symbols:**

```
ffffffff81351110-ffffffff8135112f: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81397b80)
Location: fs/verity/verify.c:273
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff81397b80-ffffffff81397b9f: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff813a9400)
Location: fs/verity/verify.c:273
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813a9400-ffffffff813a941f: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff813b0940)
Location: fs/verity/verify.c:273
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813b0940-ffffffff813b095f: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81400520)
Location: fs/verity/verify.c:273
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff81400520-ffffffff8140053f: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff814743c0)
Location: fs/verity/verify.c:273
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff814743c0-ffffffff814743eb: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81506670)
Location: fs/verity/verify.c:263
Inline: False
Direct callers:
  - fs/ext4/readpage.c:bio_post_read_processing
```
**Symbols:**

```
ffffffff81506670-ffffffff8150669b: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff8153dad0)
Location: fs/verity/verify.c:343
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_async_read_io
  - fs/buffer.c:decrypt_bh
  - fs/ext4/readpage.c:bio_post_read_processing
```
**Symbols:**

```
ffffffff8153dad0-ffffffff8153dafb: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81573070)
Location: fs/verity/verify.c:343
Inline: False
Direct callers:
  - fs/buffer.c:end_buffer_async_read_io
  - fs/buffer.c:decrypt_bh
  - fs/ext4/readpage.c:bio_post_read_processing
```
**Symbols:**

```
ffffffff81573070-ffffffff8157309b: fsverity_enqueue_verify_work (STB_GLOBAL)
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
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffff800010413188)
Location: fs/verity/verify.c:253
Inline: False
```
**Symbols:**

```
ffff800010413188-ffff8000104131c0: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (c05df468)
Location: fs/verity/verify.c:253
Inline: False
```
**Symbols:**

```
c05df468-c05df498: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (c000000000520ef0)
Location: fs/verity/verify.c:253
Inline: False
```
**Symbols:**

```
c000000000520ef0-c000000000520f34: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffe0002bad34)
Location: fs/verity/verify.c:253
Inline: False
```
**Symbols:**

```
ffffffe0002bad34-ffffffe0002bad68: fsverity_enqueue_verify_work (STB_GLOBAL)
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
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff813496f0)
Location: fs/verity/verify.c:253
Inline: False
```
**Symbols:**

```
ffffffff813496f0-ffffffff8134970f: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff8133a3d0)
Location: fs/verity/verify.c:253
Inline: False
```
**Symbols:**

```
ffffffff8133a3d0-ffffffff8133a3ef: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff813471c0)
Location: fs/verity/verify.c:253
Inline: False
```
**Symbols:**

```
ffffffff813471c0-ffffffff813471df: fsverity_enqueue_verify_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fsverity_enqueue_verify_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff8135a4c0)
Location: fs/verity/verify.c:253
Inline: False
```
**Symbols:**

```
ffffffff8135a4c0-ffffffff8135a4df: fsverity_enqueue_verify_work (STB_GLOBAL)
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
