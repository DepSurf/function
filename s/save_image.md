# Function: <code>save_image</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d4200)
Location: kernel/power/swap.c:513
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff810d4200-ffffffff810d435f: save_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d9030)
Location: kernel/power/swap.c:532
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff810d9030-ffffffff810d918f: save_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810dfb20)
Location: kernel/power/swap.c:532
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff810dfb20-ffffffff810dfc7f: save_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810dec70)
Location: kernel/power/swap.c:532
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff810dec70-ffffffff810dedd1: save_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810e6ef0)
Location: kernel/power/swap.c:532
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff810e6ef0-ffffffff810e7051: save_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:532
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff810ee8e0-ffffffff810eea19: save_image (STB_LOCAL)
ffffffff810eff9b-ffffffff810effc8: save_image.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:532
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff810f9f60-ffffffff810fa099: save_image (STB_LOCAL)
ffffffff810fb629-ffffffff810fb656: save_image.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:530
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81102650-ffffffff8110279f: save_image (STB_LOCAL)
ffffffff81103c52-ffffffff81103c87: save_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:530
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff8110ea60-ffffffff8110ebaf: save_image (STB_LOCAL)
ffffffff8111007c-ffffffff811100b1: save_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:530
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81119cf0-ffffffff81119e3f: save_image (STB_LOCAL)
ffffffff8111b2a8-ffffffff8111b2dd: save_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:538
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81115700-ffffffff81115888: save_image (STB_LOCAL)
ffffffff81be0ac3-ffffffff81be0b04: save_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:538
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81115c90-ffffffff81115e18: save_image (STB_LOCAL)
ffffffff81bd2b0c-ffffffff81bd2b4d: save_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:538
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81135f10-ffffffff81136093: save_image (STB_LOCAL)
ffffffff81cab842-ffffffff81cab883: save_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:542
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81158340-ffffffff811584eb: save_image (STB_LOCAL)
ffffffff81e5bc0d-ffffffff81e5bc4e: save_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81189ef0)
Location: kernel/power/swap.c:540
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81189ef0-ffffffff8118a0cc: save_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8119b3f0)
Location: kernel/power/swap.c:540
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff8119b3f0-ffffffff8119b5cc: save_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811aa480)
Location: kernel/power/swap.c:541
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff811aa480-ffffffff811aa65c: save_image (STB_LOCAL)
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
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (c03c30a8)
Location: kernel/power/swap.c:530
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:603
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81106ff0-ffffffff81107147: save_image (STB_LOCAL)
ffffffff8110862d-ffffffff81108662: save_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:530
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff810f7f20-ffffffff810f806f: save_image (STB_LOCAL)
ffffffff810f953c-ffffffff810f9571: save_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:530
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81104f30-ffffffff8110507f: save_image (STB_LOCAL)
ffffffff8110654c-ffffffff81106581: save_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int save_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:530
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81110310-ffffffff8111045f: save_image (STB_LOCAL)
ffffffff81111916-ffffffff8111194b: save_image.cold (STB_LOCAL)
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
