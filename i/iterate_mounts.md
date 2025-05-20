# Function: <code>iterate_mounts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122bde0)
Location: fs/namespace.c:1793
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_tag_tree
```
**Symbols:**

```
ffffffff8122bde0-ffffffff8122be4f: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81254540)
Location: fs/namespace.c:1802
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81254540-ffffffff812545b1: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81267a80)
Location: fs/namespace.c:1871
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81267a80-ffffffff81267af1: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812760c0)
Location: fs/namespace.c:1813
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812760c0-ffffffff8127613d: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81298300)
Location: fs/namespace.c:1878
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81298300-ffffffff81298381: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bdbc0)
Location: fs/namespace.c:1909
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812bdbc0-ffffffff812bdc35: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d2ef0)
Location: fs/namespace.c:1833
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812d2ef0-ffffffff812d2f65: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812effd0)
Location: fs/namespace.c:1892
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812effd0-ffffffff812f0045: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81301b70)
Location: fs/namespace.c:1894
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81301b70-ffffffff81301be5: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133aa40)
Location: fs/namespace.c:1952
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff8133aa40-ffffffff8133aab5: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81346680)
Location: fs/namespace.c:1958
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81346680-ffffffff813466f5: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81351410)
Location: fs/namespace.c:2001
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81351410-ffffffff81351485: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139a920)
Location: fs/namespace.c:2002
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff8139a920-ffffffff8139a995: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81422d00)
Location: fs/namespace.c:2043
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81422d00-ffffffff81422d81: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814af400)
Location: fs/namespace.c:2148
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff814af400-ffffffff814af481: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e4370)
Location: fs/namespace.c:2135
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff814e4370-ffffffff814e43f1: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81518080)
Location: fs/namespace.c:2137
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81518080-ffffffff81518101: iterate_mounts (STB_GLOBAL)
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
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b4268)
Location: fs/namespace.c:1894
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffff8000103b4268-ffff8000103b42f8: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0593354)
Location: fs/namespace.c:1894
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
c0593354-c05933cc: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b02c0)
Location: fs/namespace.c:1894
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
c0000000004b02c0-c0000000004b03c8: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000277a9c)
Location: fs/namespace.c:1894
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffe000277a9c-ffffffe000277b02: iterate_mounts (STB_GLOBAL)
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
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fa150)
Location: fs/namespace.c:1894
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812fa150-ffffffff812fa1c5: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ead70)
Location: fs/namespace.c:1894
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812ead70-ffffffff812eade5: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f7f40)
Location: fs/namespace.c:1894
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff812f7f40-ffffffff812f7fb5: iterate_mounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int iterate_mounts(int (*f)(struct vfsmount *, void *), void *arg, struct vfsmount *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81309880)
Location: fs/namespace.c:1894
Inline: True
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
```
**Symbols:**

```
ffffffff81309880-ffffffff813098f5: iterate_mounts (STB_GLOBAL)
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
