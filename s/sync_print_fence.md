# Function: <code>sync_print_fence</code>

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
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff8162c860)
Location: drivers/dma-buf/sync_debug.c:74
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
```
**Symbols:**

```
ffffffff8162c860-ffffffff8162ca90: sync_print_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff81641eb0)
Location: drivers/dma-buf/sync_debug.c:74
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81641eb0-ffffffff81642052: sync_print_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff816aaec0)
Location: drivers/dma-buf/sync_debug.c:74
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff816aaec0-ffffffff816ab06e: sync_print_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:74
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff816e73c0-ffffffff816e756e: sync_print_fence (STB_LOCAL)
ffffffff816e798d-ffffffff816e79a5: sync_print_fence.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:74
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff8170a750-ffffffff8170a8fe: sync_print_fence (STB_LOCAL)
ffffffff8170ad1d-ffffffff8170ad35: sync_print_fence.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81745fc0-ffffffff81746172: sync_print_fence (STB_LOCAL)
ffffffff817464f0-ffffffff81746508: sync_print_fence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff8176a110-ffffffff8176a2c1: sync_print_fence (STB_LOCAL)
ffffffff8176a640-ffffffff8176a658: sync_print_fence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff8182c230-ffffffff8182c3e1: sync_print_fence (STB_LOCAL)
ffffffff8182c773-ffffffff8182c78b: sync_print_fence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff8183d290-ffffffff8183d441: sync_print_fence (STB_LOCAL)
ffffffff81c1627d-ffffffff81c16295: sync_print_fence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81820420-ffffffff818205d1: sync_print_fence (STB_LOCAL)
ffffffff81c07f83-ffffffff81c07f9b: sync_print_fence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff818aaaf0-ffffffff818aaca1: sync_print_fence (STB_LOCAL)
ffffffff81d0bdab-ffffffff81d0bdc3: sync_print_fence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff819f5110-ffffffff819f52fc: sync_print_fence (STB_LOCAL)
ffffffff81ed4c0b-ffffffff81ed4c23: sync_print_fence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff81b725f0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81b725f0-ffffffff81b727ec: sync_print_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff81bc5ff0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81bc5ff0-ffffffff81bc61ec: sync_print_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff81c1ab10)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81c1ab10-ffffffff81c1ad0c: sync_print_fence (STB_LOCAL)
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
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffff80001096bc80)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffff80001096bc80-ffff80001096beb4: sync_print_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (c0a417e4)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
c0a417e4-c0a41a2c: sync_print_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (c000000000a24670)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
c000000000a24670-c000000000a24958: sync_print_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffe0005d6b28)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffe0005d6b28-ffffffe0005d6cda: sync_print_fence (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff8171e800-ffffffff8171e9b1: sync_print_fence (STB_LOCAL)
ffffffff8171ed30-ffffffff8171ed48: sync_print_fence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff816f7c40-ffffffff816f7df1: sync_print_fence (STB_LOCAL)
ffffffff816f8160-ffffffff816f8178: sync_print_fence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff8175d5d0-ffffffff8175d781: sync_print_fence (STB_LOCAL)
ffffffff8175db00-ffffffff8175db18: sync_print_fence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void sync_print_fence(struct seq_file *s, struct dma_fence *fence, bool show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81778c60-ffffffff81778e11: sync_print_fence (STB_LOCAL)
ffffffff81779170-ffffffff81779188: sync_print_fence.cold (STB_LOCAL)
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
