# Function: <code>bt_iter</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81425800)
Location: block/blk-mq-tag.c:218
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff81425800-ffffffff8142584c: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814335b0)
Location: block/blk-mq-tag.c:205
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814335b0-ffffffff814335ff: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8145f180)
Location: block/blk-mq-tag.c:205
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff8145f180-ffffffff8145f1da: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81492b00)
Location: block/blk-mq-tag.c:221
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff81492b00-ffffffff81492b59: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814aca40)
Location: block/blk-mq-tag.c:221
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814aca40-ffffffff814aca94: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814dad50)
Location: block/blk-mq-tag.c:214
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814dad50-ffffffff814dada4: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814f40e0)
Location: block/blk-mq-tag.c:215
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814f40e0-ffffffff814f4134: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815553f6)
Location: block/blk-mq-tag.c:242
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff81554740-ffffffff81554794: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81571aa9)
Location: block/blk-mq-tag.c:202
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff81570e20-ffffffff81570e7a: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81578fd0)
Location: block/blk-mq-tag.c:216
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff81578fd0-ffffffff81579055: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:217
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff815de200-ffffffff815de29a: bt_iter (STB_LOCAL)
ffffffff81cd85eb-ffffffff81cd8600: bt_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:263
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff8168c220-ffffffff8168c2de: bt_iter (STB_LOCAL)
ffffffff81e8bd59-ffffffff81e8bd76: bt_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:259
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff8174a9b0-ffffffff8174aa6a: bt_iter (STB_LOCAL)
ffffffff8207632b-ffffffff82076348: bt_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:266
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff81787090-ffffffff8178714a: bt_iter (STB_LOCAL)
ffffffff820f61b9-ffffffff820f61d6: bt_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:266
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff817c9770-ffffffff817c982a: bt_iter (STB_LOCAL)
ffffffff821d36de-ffffffff821d36fb: bt_iter.cold (STB_LOCAL)
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
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffff8000105f3cb0)
Location: block/blk-mq-tag.c:215
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffff8000105f3cb0-ffff8000105f3d2c: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c079fa00)
Location: block/blk-mq-tag.c:215
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
c079fa00-c079fa64: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c00000000078b2e0)
Location: block/blk-mq-tag.c:215
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
c00000000078b2e0-c00000000078b370: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffe000431ece)
Location: block/blk-mq-tag.c:215
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffe000431ece-ffffffe000431f34: bt_iter (STB_LOCAL)
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
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814ec6c0)
Location: block/blk-mq-tag.c:215
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814ec6c0-ffffffff814ec714: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814dcc10)
Location: block/blk-mq-tag.c:215
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814dcc10-ffffffff814dcc64: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814e8750)
Location: block/blk-mq-tag.c:215
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814e8750-ffffffff814e87a4: bt_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool bt_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815016f0)
Location: block/blk-mq-tag.c:215
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff815016f0-ffffffff81501744: bt_iter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
