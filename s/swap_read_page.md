# Function: <code>swap_read_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d3030)
Location: kernel/power/swap.c:996
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff810d3030-ffffffff810d30e8: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d7de0)
Location: kernel/power/swap.c:1016
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff810d7de0-ffffffff810d7e97: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810de8e0)
Location: kernel/power/swap.c:1015
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff810de8e0-ffffffff810de994: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810dd990)
Location: kernel/power/swap.c:1015
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff810dd990-ffffffff810dda43: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810e5c00)
Location: kernel/power/swap.c:1010
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff810e5c00-ffffffff810e5cb3: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810ee0e0)
Location: kernel/power/swap.c:1010
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff810ee0e0-ffffffff810ee197: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810f9750)
Location: kernel/power/swap.c:1010
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff810f9750-ffffffff810f9807: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81101e40)
Location: kernel/power/swap.c:1007
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff81101e40-ffffffff81101f07: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8110e270)
Location: kernel/power/swap.c:1007
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff8110e270-ffffffff8110e337: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81119320)
Location: kernel/power/swap.c:1007
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff81119320-ffffffff811193ce: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81114ce0)
Location: kernel/power/swap.c:1017
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff81114ce0-ffffffff81114d8e: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81115490)
Location: kernel/power/swap.c:1017
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff81115490-ffffffff8111553e: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81135660)
Location: kernel/power/swap.c:1017
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff81135660-ffffffff81135758: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81157a60)
Location: kernel/power/swap.c:1018
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff81157a60-ffffffff81157b8b: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811889a0)
Location: kernel/power/swap.c:1016
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff811889a0-ffffffff81188ac4: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81199b50)
Location: kernel/power/swap.c:1016
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff81199b50-ffffffff81199c74: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811a8bb0)
Location: kernel/power/swap.c:1017
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff811a8bb0-ffffffff811a8cd4: swap_read_page (STB_LOCAL)
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
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (c03c1304)
Location: kernel/power/swap.c:1007
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
```
**Symbols:**

```
c03c1304-c03c13d8: swap_read_page (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81107652)
Location: kernel/power/swap.c:1167
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810f7730)
Location: kernel/power/swap.c:1007
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff810f7730-ffffffff810f77f7: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81104740)
Location: kernel/power/swap.c:1007
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff81104740-ffffffff81104807: swap_read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int swap_read_page(struct swap_map_handle *handle, void *buf, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8110fb20)
Location: kernel/power/swap.c:1007
Inline: True
Direct callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
```
**Symbols:**

```
ffffffff8110fb20-ffffffff8110fbe7: swap_read_page (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
