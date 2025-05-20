# Function: <code>get_rsvd</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139bf1e)
Location: fs/ext4/extents_status.c:1157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int get_rsvd(struct inode *inode, ext4_lblk_t end, struct extent_status *right_es, struct rsvd_count *rc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e72d0)
Location: fs/ext4/extents_status.c:1157
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
**Symbols:**

```
ffffffff813e72d0-ffffffff813e7528: get_rsvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int get_rsvd(struct inode *inode, ext4_lblk_t end, struct extent_status *right_es, struct rsvd_count *rc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f9590)
Location: fs/ext4/extents_status.c:1175
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
**Symbols:**

```
ffffffff813f9590-ffffffff813f97e8: get_rsvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int get_rsvd(struct inode *inode, ext4_lblk_t end, struct extent_status *right_es, struct rsvd_count *rc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813fef60)
Location: fs/ext4/extents_status.c:1175
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
**Symbols:**

```
ffffffff813fef60-ffffffff813ff1b8: get_rsvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int get_rsvd(struct inode *inode, ext4_lblk_t end, struct extent_status *right_es, struct rsvd_count *rc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1175
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
**Symbols:**

```
ffffffff81450db0-ffffffff8145105f: get_rsvd (STB_LOCAL)
ffffffff81cc99ee-ffffffff81cc9a6b: get_rsvd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int get_rsvd(struct inode *inode, ext4_lblk_t end, struct extent_status *right_es, struct rsvd_count *rc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1175
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
**Symbols:**

```
ffffffff814cdf30-ffffffff814ce20a: get_rsvd (STB_LOCAL)
ffffffff81e7c6fe-ffffffff81e7c763: get_rsvd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int get_rsvd(struct inode *inode, ext4_lblk_t end, struct extent_status *right_es, struct rsvd_count *rc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1172
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
**Symbols:**

```
ffffffff815666e0-ffffffff815669ba: get_rsvd (STB_LOCAL)
ffffffff8206cd48-ffffffff8206cdad: get_rsvd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int get_rsvd(struct inode *inode, ext4_lblk_t end, struct extent_status *right_es, struct rsvd_count *rc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1205
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
**Symbols:**

```
ffffffff8159e370-ffffffff8159e64a: get_rsvd (STB_LOCAL)
ffffffff820ecad0-ffffffff820ecb35: get_rsvd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int get_rsvd(struct inode *inode, ext4_lblk_t end, struct extent_status *right_es, struct rsvd_count *rc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1237
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
**Symbols:**

```
ffffffff815d6ee0-ffffffff815d71ba: get_rsvd (STB_LOCAL)
ffffffff821c9cee-ffffffff821c9d53: get_rsvd.cold (STB_LOCAL)
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
In fs/ext4/extents_status.c (ffff80001046ec9c)
Location: fs/ext4/extents_status.c:1157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
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
In fs/ext4/extents_status.c (c06302b0)
Location: fs/ext4/extents_status.c:1157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
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
In fs/ext4/extents_status.c (c00000000058efb4)
Location: fs/ext4/extents_status.c:1157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
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
In fs/ext4/extents_status.c (ffffffe0002fba26)
Location: fs/ext4/extents_status.c:1157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
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
In fs/ext4/extents_status.c (ffffffff813944fe)
Location: fs/ext4/extents_status.c:1157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
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
In fs/ext4/extents_status.c (ffffffff81384f8e)
Location: fs/ext4/extents_status.c:1157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
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
In fs/ext4/extents_status.c (ffffffff81391e5e)
Location: fs/ext4/extents_status.c:1157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
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
In fs/ext4/extents_status.c (ffffffff813a5d3e)
Location: fs/ext4/extents_status.c:1157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
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
