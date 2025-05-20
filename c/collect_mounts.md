# Function: <code>collect_mounts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122e7f0)
Location: fs/namespace.c:1742
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff8122e7f0-ffffffff8122e867: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81257000)
Location: fs/namespace.c:1751
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81257000-ffffffff81257077: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81269f80)
Location: fs/namespace.c:1822
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81269f80-ffffffff81269ff7: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81277730)
Location: fs/namespace.c:1764
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81277730-ffffffff812777b2: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129a170)
Location: fs/namespace.c:1829
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff8129a170-ffffffff8129a1f2: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c0250)
Location: fs/namespace.c:1860
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812c0250-ffffffff812c02c8: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d54a0)
Location: fs/namespace.c:1784
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812d54a0-ffffffff812d5518: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f2a40)
Location: fs/namespace.c:1821
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812f2a40-ffffffff812f2abd: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81304600)
Location: fs/namespace.c:1824
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81304600-ffffffff8130467d: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133e1d0)
Location: fs/namespace.c:1879
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff8133e1d0-ffffffff8133e251: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134a230)
Location: fs/namespace.c:1885
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff8134a230-ffffffff8134a2b1: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81350c20)
Location: fs/namespace.c:1900
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81350c20-ffffffff81350ca1: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139efe0)
Location: fs/namespace.c:1901
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff8139efe0-ffffffff8139f061: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814222b0)
Location: fs/namespace.c:1942
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff814222b0-ffffffff8142234a: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ae8f0)
Location: fs/namespace.c:2047
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff814ae8f0-ffffffff814ae98a: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e3850)
Location: fs/namespace.c:2034
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff814e3850-ffffffff814e38ea: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff815175a0)
Location: fs/namespace.c:2036
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff815175a0-ffffffff8151763a: collect_mounts (STB_GLOBAL)
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
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b7f50)
Location: fs/namespace.c:1824
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffff8000103b7f50-ffff8000103b7fe0: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05960ac)
Location: fs/namespace.c:1824
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
c05960ac-c0596134: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b4cf0)
Location: fs/namespace.c:1824
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
c0000000004b4cf0-c0000000004b4da0: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027a8ae)
Location: fs/namespace.c:1824
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffe00027a8ae-ffffffe00027a928: collect_mounts (STB_GLOBAL)
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
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fcbe0)
Location: fs/namespace.c:1824
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812fcbe0-ffffffff812fcc5d: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ed800)
Location: fs/namespace.c:1824
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812ed800-ffffffff812ed87d: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fa9d0)
Location: fs/namespace.c:1824
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812fa9d0-ffffffff812faa4d: collect_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vfsmount *collect_mounts(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130bd00)
Location: fs/namespace.c:1824
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff8130bd00-ffffffff8130bd7d: collect_mounts (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
