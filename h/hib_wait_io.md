# Function: <code>hib_wait_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d2a30)
Location: kernel/power/swap.c:284
Inline: False
Direct callers:
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
**Symbols:**

```
ffffffff810d2a30-ffffffff810d2ac2: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d77e0)
Location: kernel/power/swap.c:296
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810d77e0-ffffffff810d7872: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810de310)
Location: kernel/power/swap.c:296
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810de310-ffffffff810de398: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810dd400)
Location: kernel/power/swap.c:296
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810dd400-ffffffff810dd48e: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810e5670)
Location: kernel/power/swap.c:297
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810e5670-ffffffff810e56fe: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810edb80)
Location: kernel/power/swap.c:297
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810edb80-ffffffff810edc0e: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810f91f0)
Location: kernel/power/swap.c:297
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810f91f0-ffffffff810f927e: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811018e0)
Location: kernel/power/swap.c:295
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff811018e0-ffffffff8110196e: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8110dd10)
Location: kernel/power/swap.c:295
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff8110dd10-ffffffff8110dd9e: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81118d30)
Location: kernel/power/swap.c:295
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:swap_write_page
```
**Symbols:**

```
ffffffff81118d30-ffffffff81118dbe: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81114800)
Location: kernel/power/swap.c:302
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff81114800-ffffffff8111488e: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81114fb0)
Location: kernel/power/swap.c:302
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff81114fb0-ffffffff8111503e: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81135050)
Location: kernel/power/swap.c:302
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff81135050-ffffffff811350de: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811572f0)
Location: kernel/power/swap.c:303
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff811572f0-ffffffff811573b3: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81188060)
Location: kernel/power/swap.c:302
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:swap_write_page
```
**Symbols:**

```
ffffffff81188060-ffffffff81188123: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811991f0)
Location: kernel/power/swap.c:302
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:swap_write_page
```
**Symbols:**

```
ffffffff811991f0-ffffffff811992b3: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811a8250)
Location: kernel/power/swap.c:303
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:swap_write_page
```
**Symbols:**

```
ffffffff811a8250-ffffffff811a8313: hib_wait_io (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (c03c0d00)
Location: kernel/power/swap.c:295
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
c03c0d00-c03c0db4: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81105f60)
Location: kernel/power/swap.c:355
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff81105f60-ffffffff81106013: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810f71d0)
Location: kernel/power/swap.c:295
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810f71d0-ffffffff810f725e: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811041e0)
Location: kernel/power/swap.c:295
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff811041e0-ffffffff8110426e: hib_wait_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_status_t hib_wait_io(struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8110f5d0)
Location: kernel/power/swap.c:295
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff8110f5d0-ffffffff8110f659: hib_wait_io (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>blk_status_t</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
