# Function: <code>bio_copy_data_iter</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479e70)
Location: block/bio.c:1031
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff81479e70-ffffffff8147a132: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81497c80)
Location: block/bio.c:955
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff81497c80-ffffffff81497f32: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c5840)
Location: block/bio.c:1014
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff814c5840-ffffffff814c5bc7: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814dea40)
Location: block/bio.c:1053
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff814dea40-ffffffff814dedc7: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153e410)
Location: block/bio.c:1187
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff8153e410-ffffffff8153e732: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155ae10)
Location: block/bio.c:1190
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff8155ae10-ffffffff8155b085: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81563640)
Location: block/bio.c:1191
Inline: False
Direct callers:
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff81563640-ffffffff815638b3: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c6fa0)
Location: block/bio.c:1285
Inline: False
Direct callers:
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff815c6fa0-ffffffff815c7201: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81671eb0)
Location: block/bio.c:1342
Inline: False
Direct callers:
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff81671eb0-ffffffff816720ff: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172d630)
Location: block/bio.c:1405
Inline: False
Direct callers:
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff8172d630-ffffffff8172d8aa: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817699e0)
Location: block/bio.c:1390
Inline: False
Direct callers:
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff817699e0-ffffffff81769c4e: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817abb90)
Location: block/bio.c:1402
Inline: False
Direct callers:
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff817abb90-ffffffff817abdfe: bio_copy_data_iter (STB_GLOBAL)
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
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dac88)
Location: block/bio.c:1053
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffff8000105dac88-ffff8000105dafb8: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c078879c)
Location: block/bio.c:1053
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
c078879c-c0788b0c: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076bc80)
Location: block/bio.c:1053
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
c00000000076bc80-c00000000076c118: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041ea06)
Location: block/bio.c:1053
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffe00041ea06-ffffffe00041ed4a: bio_copy_data_iter (STB_GLOBAL)
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
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d7020)
Location: block/bio.c:1053
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff814d7020-ffffffff814d73a7: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c79e0)
Location: block/bio.c:1053
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff814c79e0-ffffffff814c7d67: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d30b0)
Location: block/bio.c:1053
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff814d30b0-ffffffff814d3437: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_copy_data_iter(struct bio *dst, struct bvec_iter *dst_iter, struct bio *src, struct bvec_iter *src_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ebac0)
Location: block/bio.c:1053
Inline: False
Direct callers:
  - block/bio.c:bio_list_copy_data
  - block/bio.c:bio_copy_data
```
**Symbols:**

```
ffffffff814ebac0-ffffffff814ebe8d: bio_copy_data_iter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
