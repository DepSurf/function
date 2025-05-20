# Function: <code>ext4_num_overhead_clusters</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8128fa1e)
Location: fs/ext4/balloc.c:85
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bcf5e)
Location: fs/ext4/balloc.c:85
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d25ae)
Location: fs/ext4/balloc.c:85
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e3c2e)
Location: fs/ext4/balloc.c:85
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81308614)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81336544)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134d7c4)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813761a4)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138e414)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int ext4_num_overhead_clusters(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813d98f0)
Location: fs/ext4/balloc.c:86
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
**Symbols:**

```
ffffffff813d98f0-ffffffff813d9b3e: ext4_num_overhead_clusters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int ext4_num_overhead_clusters(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813eb5a0)
Location: fs/ext4/balloc.c:86
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
**Symbols:**

```
ffffffff813eb5a0-ffffffff813eb7ee: ext4_num_overhead_clusters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int ext4_num_overhead_clusters(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f1ae0)
Location: fs/ext4/balloc.c:86
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
**Symbols:**

```
ffffffff813f1ae0-ffffffff813f1d2e: ext4_num_overhead_clusters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int ext4_num_overhead_clusters(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:86
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
**Symbols:**

```
ffffffff81443b40-ffffffff81443d2c: ext4_num_overhead_clusters (STB_LOCAL)
ffffffff81cc8bba-ffffffff81cc8c26: ext4_num_overhead_clusters.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int ext4_num_overhead_clusters(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:86
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
**Symbols:**

```
ffffffff814bfa20-ffffffff814bfc09: ext4_num_overhead_clusters (STB_LOCAL)
ffffffff81e7b903-ffffffff81e7b95d: ext4_num_overhead_clusters.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int ext4_num_overhead_clusters(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:86
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
**Symbols:**

```
ffffffff815579e0-ffffffff81557bc9: ext4_num_overhead_clusters (STB_LOCAL)
ffffffff8206c094-ffffffff8206c0ee: ext4_num_overhead_clusters.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int ext4_num_overhead_clusters(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:87
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
**Symbols:**

```
ffffffff8158f740-ffffffff8158f916: ext4_num_overhead_clusters (STB_LOCAL)
ffffffff820ebedc-ffffffff820ebf79: ext4_num_overhead_clusters.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int ext4_num_overhead_clusters(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:88
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
**Symbols:**

```
ffffffff815c8c40-ffffffff815c8e16: ext4_num_overhead_clusters (STB_LOCAL)
ffffffff821c91a2-ffffffff821c9250: ext4_num_overhead_clusters.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff800010460644)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c0620e20)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057cbf0)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002efba2)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
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
In fs/ext4/balloc.c (ffffffff813869f4)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81377484)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813844c4)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81398044)
Location: fs/ext4/balloc.c:86
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
