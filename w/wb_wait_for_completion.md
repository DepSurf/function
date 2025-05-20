# Function: <code>wb_wait_for_completion</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct backing_dev_info *bdi, struct wb_completion *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81236730)
Location: fs/fs-writeback.c:203
Inline: True
Direct callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:sync_inodes_sb
```
**Symbols:**

```
ffffffff81236730-ffffffff812367c8: wb_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct backing_dev_info *bdi, struct wb_completion *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8125fdd0)
Location: fs/fs-writeback.c:203
Inline: True
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff8125fdd0-ffffffff8125fe68: wb_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct backing_dev_info *bdi, struct wb_completion *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812732f0)
Location: fs/fs-writeback.c:203
Inline: True
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff812732f0-ffffffff8127337e: wb_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct backing_dev_info *bdi, struct wb_completion *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81280850)
Location: fs/fs-writeback.c:217
Inline: True
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff81280850-ffffffff812808de: wb_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct backing_dev_info *bdi, struct wb_completion *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a33f0)
Location: fs/fs-writeback.c:217
Inline: True
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff812a33f0-ffffffff812a347e: wb_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct backing_dev_info *bdi, struct wb_completion *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812c9e40)
Location: fs/fs-writeback.c:217
Inline: True
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff812c9e40-ffffffff812c9ece: wb_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct backing_dev_info *bdi, struct wb_completion *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812df000)
Location: fs/fs-writeback.c:217
Inline: True
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff812df000-ffffffff812df08e: wb_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct backing_dev_info *bdi, struct wb_completion *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fd6c0)
Location: fs/fs-writeback.c:218
Inline: True
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff812fd6c0-ffffffff812fd74e: wb_wait_for_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81314200)
Location: fs/fs-writeback.c:205
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff81314200-ffffffff81314282: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134dd30)
Location: fs/fs-writeback.c:206
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff8134dd30-ffffffff8134ddb1: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135abb0)
Location: fs/fs-writeback.c:206
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff8135abb0-ffffffff8135ac31: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813617b0)
Location: fs/fs-writeback.c:206
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff813617b0-ffffffff81361831: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813afe10)
Location: fs/fs-writeback.c:187
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff813afe10-ffffffff813afe91: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814349b0)
Location: fs/fs-writeback.c:188
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff814349b0-ffffffff81434a68: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c29a0)
Location: fs/fs-writeback.c:189
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff814c29a0-ffffffff814c2a58: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f7d60)
Location: fs/fs-writeback.c:189
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff814f7d60-ffffffff814f7e18: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152c4b0)
Location: fs/fs-writeback.c:189
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff8152c4b0-ffffffff8152c568: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c9fb8)
Location: fs/fs-writeback.c:205
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffff8000103c9fb8-ffff8000103ca070: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a65b0)
Location: fs/fs-writeback.c:205
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
c05a65b0-c05a666c: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004cb800)
Location: fs/fs-writeback.c:205
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
c0000000004cb800-c0000000004cb8e4: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe0002882e0)
Location: fs/fs-writeback.c:205
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffe0002882e0-ffffffe00028835a: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130c7e0)
Location: fs/fs-writeback.c:205
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff8130c7e0-ffffffff8130c862: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fd400)
Location: fs/fs-writeback.c:205
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff812fd400-ffffffff812fd482: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130a5d0)
Location: fs/fs-writeback.c:205
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff8130a5d0-ffffffff8130a652: wb_wait_for_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wb_wait_for_completion(struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131bc90)
Location: fs/fs-writeback.c:205
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
**Symbols:**

```
ffffffff8131bc90-ffffffff8131bd0d: wb_wait_for_completion (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct backing_dev_info *bdi</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdi, done</code> ➡️ <code>done</code>
</li>
</ul>
</details>
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
