# Function: <code>bt_tags_iter</code>

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
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81425850)
Location: block/blk-mq-tag.c:255
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffff81425850-ffffffff81425885: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81433600)
Location: block/blk-mq-tag.c:242
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffff81433600-ffffffff81433635: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8145f1e0)
Location: block/blk-mq-tag.c:246
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffff8145f1e0-ffffffff8145f226: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81492bb0)
Location: block/blk-mq-tag.c:262
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffff81492bb0-ffffffff81492c0f: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814acac0)
Location: block/blk-mq-tag.c:276
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffff814acac0-ffffffff814acb26: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814dadd0)
Location: block/blk-mq-tag.c:269
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffff814dadd0-ffffffff814dae36: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814f4160)
Location: block/blk-mq-tag.c:270
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffff814f4160-ffffffff814f41c6: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81555142)
Location: block/blk-mq-tag.c:301
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
Direct callers:
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
**Symbols:**

```
ffffffff815547a0-ffffffff8155480d: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81571812)
Location: block/blk-mq-tag.c:261
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
Direct callers:
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
**Symbols:**

```
ffffffff81570e80-ffffffff81570eed: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81578f00)
Location: block/blk-mq-tag.c:279
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
**Symbols:**

```
ffffffff81578f00-ffffffff81578fc1: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815de130)
Location: block/blk-mq-tag.c:280
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
**Symbols:**

```
ffffffff815de130-ffffffff815de1f1: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8168c130)
Location: block/blk-mq-tag.c:336
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
**Symbols:**

```
ffffffff8168c130-ffffffff8168c213: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8174a8c0)
Location: block/blk-mq-tag.c:331
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
**Symbols:**

```
ffffffff8174a8c0-ffffffff8174a991: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81786fa0)
Location: block/blk-mq-tag.c:338
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
**Symbols:**

```
ffffffff81786fa0-ffffffff81787071: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817c9680)
Location: block/blk-mq-tag.c:338
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
**Symbols:**

```
ffffffff817c9680-ffffffff817c9751: bt_tags_iter (STB_LOCAL)
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
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffff8000105f3d68)
Location: block/blk-mq-tag.c:270
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffff8000105f3d68-ffff8000105f3dec: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c079fb3c)
Location: block/blk-mq-tag.c:270
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
c079fb3c-c079fba8: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c00000000078b390)
Location: block/blk-mq-tag.c:270
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
c00000000078b390-c00000000078b45c: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffe000431f66)
Location: block/blk-mq-tag.c:270
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffe000431f66-ffffffe000431fd6: bt_tags_iter (STB_LOCAL)
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
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814ec740)
Location: block/blk-mq-tag.c:270
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffff814ec740-ffffffff814ec7a6: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814dcc90)
Location: block/blk-mq-tag.c:270
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffff814dcc90-ffffffff814dccf6: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814e87d0)
Location: block/blk-mq-tag.c:270
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffff814e87d0-ffffffff814e8836: bt_tags_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool bt_tags_iter(struct sbitmap *bitmap, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81501770)
Location: block/blk-mq-tag.c:270
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffff81501770-ffffffff815017d6: bt_tags_iter (STB_LOCAL)
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
