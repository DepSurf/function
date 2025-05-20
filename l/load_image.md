# Function: <code>load_image</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d30f0)
Location: kernel/power/swap.c:1038
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff810d30f0-ffffffff810d328c: load_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d7ea0)
Location: kernel/power/swap.c:1058
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff810d7ea0-ffffffff810d803c: load_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810de9a0)
Location: kernel/power/swap.c:1057
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff810de9a0-ffffffff810deb3c: load_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810dda50)
Location: kernel/power/swap.c:1057
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff810dda50-ffffffff810ddbec: load_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810e5cc0)
Location: kernel/power/swap.c:1052
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff810e5cc0-ffffffff810e5e5c: load_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1052
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff810ee1a0-ffffffff810ee2f9: load_image (STB_LOCAL)
ffffffff810ef549-ffffffff810ef591: load_image.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1052
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff810f9810-ffffffff810f9969: load_image (STB_LOCAL)
ffffffff810fabd9-ffffffff810fac21: load_image.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1049
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff81101f10-ffffffff81102089: load_image (STB_LOCAL)
ffffffff81103284-ffffffff811032d4: load_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1049
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff8110e340-ffffffff8110e4b9: load_image (STB_LOCAL)
ffffffff8110f6d4-ffffffff8110f724: load_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1049
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff811193d0-ffffffff81119542: load_image (STB_LOCAL)
ffffffff8111a91a-ffffffff8111a96a: load_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1059
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff811151e0-ffffffff81115392: load_image (STB_LOCAL)
ffffffff81be0a67-ffffffff81be0ac3: load_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1059
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff81115540-ffffffff811156f2: load_image (STB_LOCAL)
ffffffff81bd211e-ffffffff81bd217a: load_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1059
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff81135760-ffffffff81135912: load_image (STB_LOCAL)
ffffffff81caae30-ffffffff81caae8c: load_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1060
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff81157b90-ffffffff81157d62: load_image (STB_LOCAL)
ffffffff81e5b280-ffffffff81e5b2dc: load_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81188ae0)
Location: kernel/power/swap.c:1058
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff81188ae0-ffffffff81188d0a: load_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81199c90)
Location: kernel/power/swap.c:1058
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff81199c90-ffffffff81199eba: load_image (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811a8cf0)
Location: kernel/power/swap.c:1059
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff811a8cf0-ffffffff811a8f1a: load_image (STB_LOCAL)
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
In kernel/power/swap.c (c03c2a64)
Location: kernel/power/swap.c:1049
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1186
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff81106900-ffffffff81106a90: load_image (STB_LOCAL)
ffffffff81107c1c-ffffffff81107c6c: load_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1049
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff810f7800-ffffffff810f7979: load_image (STB_LOCAL)
ffffffff810f8b94-ffffffff810f8be4: load_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1049
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff81104810-ffffffff81104989: load_image (STB_LOCAL)
ffffffff81105ba4-ffffffff81105bf4: load_image.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int load_image(struct swap_map_handle *handle, struct snapshot_handle *snapshot, unsigned int nr_to_read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:1049
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff8110fbf0-ffffffff8110fd69: load_image (STB_LOCAL)
ffffffff81110f84-ffffffff81110fd4: load_image.cold (STB_LOCAL)
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
