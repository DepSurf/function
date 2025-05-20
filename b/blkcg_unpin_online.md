# Function: <code>blkcg_unpin_online</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812783d1)
Location: include/linux/blk-cgroup.h:437
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff8156bd1a)
Location: include/linux/blk-cgroup.h:437
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81282561)
Location: include/linux/blk-cgroup.h:427
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff81586a1a)
Location: include/linux/blk-cgroup.h:427
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81287671)
Location: include/linux/blk-cgroup.h:427
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff8158d72a)
Location: include/linux/blk-cgroup.h:427
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c67f1)
Location: include/linux/blk-cgroup.h:432
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In block/blk-cgroup.c (ffffffff815f31aa)
Location: include/linux/blk-cgroup.h:432
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blkcg_unpin_online(struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a4600)
Location: block/blk-cgroup.c:1126
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff816a4600-ffffffff816a471c: blkcg_unpin_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blkcg_unpin_online(struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81763330)
Location: block/blk-cgroup.c:1138
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff81763330-ffffffff81763455: blkcg_unpin_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blkcg_unpin_online(struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a2480)
Location: block/blk-cgroup.c:1271
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff817a2480-ffffffff817a25a8: blkcg_unpin_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blkcg_unpin_online(struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e5fc0)
Location: block/blk-cgroup.c:1284
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff817e5fc0-ffffffff817e60e5: blkcg_unpin_online (STB_GLOBAL)
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
In <code>armhf</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
