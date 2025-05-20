# Function: <code>kernfs_node_from_dentry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128a7f0)
Location: fs/kernfs/dir.c:652
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroupstats_build
  - kernel/cgroup.c:css_tryget_online_from_dir
```
**Symbols:**

```
ffffffff8128a7f0-ffffffff8128a80f: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b7c30)
Location: fs/kernfs/dir.c:651
Inline: False
Direct callers:
  - kernel/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup.c:cgroupstats_build
```
**Symbols:**

```
ffffffff812b7c30-ffffffff812b7c4f: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd3d0)
Location: fs/kernfs/dir.c:601
Inline: False
Direct callers:
  - kernel/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup.c:cgroupstats_build
```
**Symbols:**

```
ffffffff812cd3d0-ffffffff812cd3ef: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812da980)
Location: fs/kernfs/dir.c:611
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff812da980-ffffffff812da9a1: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff210)
Location: fs/kernfs/dir.c:612
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff812ff210-ffffffff812ff23d: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132ced0)
Location: fs/kernfs/dir.c:612
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff8132ced0-ffffffff8132cefb: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81344270)
Location: fs/kernfs/dir.c:612
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff81344270-ffffffff8134429b: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c480)
Location: fs/kernfs/dir.c:608
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff8136c480-ffffffff8136c4ab: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384630)
Location: fs/kernfs/dir.c:609
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff81384630-ffffffff8138465b: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf0e0)
Location: fs/kernfs/dir.c:605
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff813cf0e0-ffffffff813cf10b: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e0d10)
Location: fs/kernfs/dir.c:605
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff813e0d10-ffffffff813e0d3d: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e7840)
Location: fs/kernfs/dir.c:605
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff813e7840-ffffffff813e786d: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439550)
Location: fs/kernfs/dir.c:564
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff81439550-ffffffff8143957d: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b45b0)
Location: fs/kernfs/dir.c:572
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff814b45b0-ffffffff814b45ed: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154b490)
Location: fs/kernfs/dir.c:593
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff8154b490-ffffffff8154b4cd: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815830e0)
Location: fs/kernfs/dir.c:590
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff815830e0-ffffffff8158311d: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bbd10)
Location: fs/kernfs/dir.c:594
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff815bbd10-ffffffff815bbd4d: kernfs_node_from_dentry (STB_GLOBAL)
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
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010453390)
Location: fs/kernfs/dir.c:609
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffff800010453390-ffff8000104533e8: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0615f78)
Location: fs/kernfs/dir.c:609
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
c0615f78-c0615fbc: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056c6f0)
Location: fs/kernfs/dir.c:609
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
c00000000056c6f0-c00000000056c738: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e5a3c)
Location: fs/kernfs/dir.c:609
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffe0002e5a3c-ffffffe0002e5a76: kernfs_node_from_dentry (STB_GLOBAL)
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
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137cc10)
Location: fs/kernfs/dir.c:609
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff8137cc10-ffffffff8137cc3b: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136d6e0)
Location: fs/kernfs/dir.c:609
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff8136d6e0-ffffffff8136d70b: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137a6e0)
Location: fs/kernfs/dir.c:609
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff8137a6e0-ffffffff8137a70b: kernfs_node_from_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kernfs_node *kernfs_node_from_dentry(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e1d0)
Location: fs/kernfs/dir.c:609
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
**Symbols:**

```
ffffffff8138e1d0-ffffffff8138e1fb: kernfs_node_from_dentry (STB_GLOBAL)
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
