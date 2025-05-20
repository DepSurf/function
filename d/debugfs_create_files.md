# Function: <code>debugfs_create_files</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool debugfs_create_files(struct dentry *parent, void *data, const struct blk_mq_debugfs_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81459de0)
Location: block/blk-mq-debugfs.c:789
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81459de0-ffffffff81459e48: debugfs_create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool debugfs_create_files(struct dentry *parent, void *data, const struct blk_mq_debugfs_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81485ab0)
Location: block/blk-mq-debugfs.c:786
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81485ab0-ffffffff81485b18: debugfs_create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool debugfs_create_files(struct dentry *parent, void *data, const struct blk_mq_debugfs_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814ba940)
Location: block/blk-mq-debugfs.c:812
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814ba940-ffffffff814ba9a8: debugfs_create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814cf4b8)
Location: block/blk-mq-debugfs.c:839
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814ced60-ffffffff814cedc8: debugfs_create_files.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fdc5b)
Location: block/blk-mq-debugfs.c:808
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814fd630-ffffffff814fd67c: debugfs_create_files.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151bb9b)
Location: block/blk-mq-debugfs.c:808
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8151b580-ffffffff8151b5cc: debugfs_create_files.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void debugfs_create_files(struct dentry *parent, void *data, const struct blk_mq_debugfs_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157bfe5)
Location: block/blk-mq-debugfs.c:812
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8157b980-ffffffff8157b9db: debugfs_create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void debugfs_create_files(struct dentry *parent, void *data, const struct blk_mq_debugfs_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81599085)
Location: block/blk-mq-debugfs.c:813
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81598a40-ffffffff81598a9b: debugfs_create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void debugfs_create_files(struct dentry *parent, void *data, const struct blk_mq_debugfs_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8159fe85)
Location: block/blk-mq-debugfs.c:811
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8159f850-ffffffff8159f8ab: debugfs_create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void debugfs_create_files(struct dentry *parent, void *data, const struct blk_mq_debugfs_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816086a5)
Location: block/blk-mq-debugfs.c:812
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81608000-ffffffff8160805b: debugfs_create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816bc561)
Location: block/blk-mq-debugfs.c:668
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177cf61)
Location: block/blk-mq-debugfs.c:668
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817bc905)
Location: block/blk-mq-debugfs.c:642
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81800fc5)
Location: block/blk-mq-debugfs.c:623
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffff800010624218)
Location: block/blk-mq-debugfs.c:808
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffff800010623578-ffff8000106235e4: debugfs_create_files.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (c07cb82c)
Location: block/blk-mq-debugfs.c:808
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
c07cb1d0-c07cb234: debugfs_create_files.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c4dd8)
Location: block/blk-mq-debugfs.c:808
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
c0000000007c4340-c0000000007c43d4: debugfs_create_files.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe000455dca)
Location: block/blk-mq-debugfs.c:808
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffe000455696-ffffffe0004556f0: debugfs_create_files.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151417b)
Location: block/blk-mq-debugfs.c:808
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81513b60-ffffffff81513bac: debugfs_create_files.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8150448b)
Location: block/blk-mq-debugfs.c:808
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81503e70-ffffffff81503ebc: debugfs_create_files.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151020b)
Location: block/blk-mq-debugfs.c:808
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8150fbf0-ffffffff8150fc3c: debugfs_create_files.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815299cb)
Location: block/blk-mq-debugfs.c:808
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81529410-ffffffff8152945c: debugfs_create_files.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
</ul>
