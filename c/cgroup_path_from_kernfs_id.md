# Function: <code>cgroup_path_from_kernfs_id</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811347c0)
Location: kernel/cgroup/cgroup.c:5366
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff811347c0-ffffffff8113480a: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81142ee0)
Location: kernel/cgroup/cgroup.c:5404
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff81142ee0-ffffffff81142f2a: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114ea10)
Location: kernel/cgroup/cgroup.c:5497
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff8114ea10-ffffffff8114ea5a: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a570)
Location: kernel/cgroup/cgroup.c:5838
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff8115a570-ffffffff8115a5bc: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166220)
Location: kernel/cgroup/cgroup.c:5853
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff81166220-ffffffff8116626c: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(u64 id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811773b0)
Location: kernel/cgroup/cgroup.c:5795
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff811773b0-ffffffff811773fc: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(u64 id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174090)
Location: kernel/cgroup/cgroup.c:5787
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff81174090-ffffffff811740dc: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(u64 id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174c60)
Location: kernel/cgroup/cgroup.c:5762
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff81174c60-ffffffff81174cac: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(u64 id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119bf80)
Location: kernel/cgroup/cgroup.c:5952
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff8119bf80-ffffffff8119bfcc: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(u64 id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cc240)
Location: kernel/cgroup/cgroup.c:5963
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff811cc240-ffffffff811cc298: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(u64 id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120f780)
Location: kernel/cgroup/cgroup.c:6174
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff8120f780-ffffffff8120f7d8: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(u64 id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81225190)
Location: kernel/cgroup/cgroup.c:6155
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff81225190-ffffffff812251e8: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(u64 id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123ce80)
Location: kernel/cgroup/cgroup.c:6188
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff8123ce80-ffffffff8123ced8: cgroup_path_from_kernfs_id (STB_GLOBAL)
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
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d7f10)
Location: kernel/cgroup/cgroup.c:5853
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffff8000101d7f10-ffff8000101d7f74: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041ab34)
Location: kernel/cgroup/cgroup.c:5853
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
c041ab34-c041ab88: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000244da0)
Location: kernel/cgroup/cgroup.c:5853
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
c000000000244da0-c000000000244e2c: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000150f56)
Location: kernel/cgroup/cgroup.c:5853
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffe000150f56-ffffffe000150fb0: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e840)
Location: kernel/cgroup/cgroup.c:5853
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff8115e840-ffffffff8115e88c: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81151af0)
Location: kernel/cgroup/cgroup.c:5853
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff81151af0-ffffffff81151b3c: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115c610)
Location: kernel/cgroup/cgroup.c:5853
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff8115c610-ffffffff8115c65c: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_path_from_kernfs_id(const union kernfs_node_id *id, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81169730)
Location: kernel/cgroup/cgroup.c:5853
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_log_action
```
**Symbols:**

```
ffffffff81169730-ffffffff8116977c: cgroup_path_from_kernfs_id (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const union kernfs_node_id *id</code> ➡️ <code>u64 id</code>
</li>
</ul>
</details>
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
