# Function: <code>kernfs_walk_and_get_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b7ca0)
Location: fs/kernfs/dir.c:886
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff812b7ca0-ffffffff812b7da3: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd440)
Location: fs/kernfs/dir.c:836
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff812cd440-ffffffff812cd543: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812daa00)
Location: fs/kernfs/dir.c:846
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff812daa00-ffffffff812dab5a: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff2e0)
Location: fs/kernfs/dir.c:912
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff812ff2e0-ffffffff812ff43a: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132cfa0)
Location: fs/kernfs/dir.c:929
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff8132cfa0-ffffffff8132d0fa: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81344340)
Location: fs/kernfs/dir.c:929
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff81344340-ffffffff8134449a: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c560)
Location: fs/kernfs/dir.c:930
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff8136c560-ffffffff8136c6b5: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384710)
Location: fs/kernfs/dir.c:930
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff81384710-ffffffff81384865: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf1f0)
Location: fs/kernfs/dir.c:924
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff813cf1f0-ffffffff813cf244: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e0e20)
Location: fs/kernfs/dir.c:923
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff813e0e20-ffffffff813e0e74: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e7950)
Location: fs/kernfs/dir.c:923
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff813e7950-ffffffff813e7aa1: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439660)
Location: fs/kernfs/dir.c:882
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff81439660-ffffffff814397c3: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b46f0)
Location: fs/kernfs/dir.c:891
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff814b46f0-ffffffff814b485e: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154b600)
Location: fs/kernfs/dir.c:911
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff8154b600-ffffffff8154b76e: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81583250)
Location: fs/kernfs/dir.c:913
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff81583250-ffffffff815833dd: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bbea0)
Location: fs/kernfs/dir.c:929
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff815bbea0-ffffffff815bbf15: kernfs_walk_and_get_ns (STB_GLOBAL)
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
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010453528)
Location: fs/kernfs/dir.c:930
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffff800010453528-ffff8000104536d8: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c06160b4)
Location: fs/kernfs/dir.c:930
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
c06160b4-c061620c: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056c880)
Location: fs/kernfs/dir.c:930
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
c00000000056c880-c00000000056caa8: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e5b7a)
Location: fs/kernfs/dir.c:930
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffe0002e5b7a-ffffffe0002e5cd8: kernfs_walk_and_get_ns (STB_GLOBAL)
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
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137ccf0)
Location: fs/kernfs/dir.c:930
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff8137ccf0-ffffffff8137ce45: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136d7c0)
Location: fs/kernfs/dir.c:930
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff8136d7c0-ffffffff8136d909: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137a7c0)
Location: fs/kernfs/dir.c:930
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff8137a7c0-ffffffff8137a915: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_and_get_ns(struct kernfs_node *parent, const char *path, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e2d0)
Location: fs/kernfs/dir.c:930
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
```
**Symbols:**

```
ffffffff8138e2d0-ffffffff8138e414: kernfs_walk_and_get_ns (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
