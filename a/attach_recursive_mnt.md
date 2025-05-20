# Function: <code>attach_recursive_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, struct path *parent_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122ddb0)
Location: fs/namespace.c:1899
Inline: False
Direct callers:
  - fs/namespace.c:graft_tree
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff8122ddb0-ffffffff8122dfd8: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, struct path *parent_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812565a0)
Location: fs/namespace.c:1908
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff812565a0-ffffffff812567d0: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, struct path *parent_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126a110)
Location: fs/namespace.c:1999
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff8126a110-ffffffff8126a420: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, struct path *parent_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812778c0)
Location: fs/namespace.c:1941
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff812778c0-ffffffff81277ba7: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, struct path *parent_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129a300)
Location: fs/namespace.c:2006
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff8129a300-ffffffff8129a5e7: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, struct path *parent_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c03c0)
Location: fs/namespace.c:2037
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff812c03c0-ffffffff812c06b4: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, struct path *parent_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d5610)
Location: fs/namespace.c:1961
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff812d5610-ffffffff812d5904: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f3760)
Location: fs/namespace.c:2046
Inline: False
Direct callers:
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff812f3760-ffffffff812f3af1: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81305320)
Location: fs/namespace.c:2049
Inline: False
Direct callers:
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff81305320-ffffffff813056aa: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133ec20)
Location: fs/namespace.c:2107
Inline: False
Direct callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff8133ec20-ffffffff8133efe7: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134ac80)
Location: fs/namespace.c:2113
Inline: False
Direct callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff8134ac80-ffffffff8134b047: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81351530)
Location: fs/namespace.c:2155
Inline: False
Direct callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff81351530-ffffffff813518f7: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139f8a0)
Location: fs/namespace.c:2157
Inline: False
Direct callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff8139f8a0-ffffffff8139fc67: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81422e40)
Location: fs/namespace.c:2198
Inline: False
Direct callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff81422e40-ffffffff8142320c: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814af560)
Location: fs/namespace.c:2303
Inline: False
Direct callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff814af560-ffffffff814af92c: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *top_mnt, struct mountpoint *dest_mp, enum mnt_tree_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e44d0)
Location: fs/namespace.c:2299
Inline: False
Direct callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff814e44d0-ffffffff814e4951: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *top_mnt, struct mountpoint *dest_mp, enum mnt_tree_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff815181e0)
Location: fs/namespace.c:2301
Inline: False
Direct callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff815181e0-ffffffff8151877e: attach_recursive_mnt (STB_LOCAL)
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
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b8960)
Location: fs/namespace.c:2049
Inline: False
Direct callers:
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffff8000103b8960-ffff8000103b8d78: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0596344)
Location: fs/namespace.c:2049
Inline: False
Direct callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
c0596344-c0596718: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b5980)
Location: fs/namespace.c:2049
Inline: False
Direct callers:
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
c0000000004b5980-c0000000004b5e9c: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027ade0)
Location: fs/namespace.c:2049
Inline: False
Direct callers:
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffe00027ade0-ffffffe00027b154: attach_recursive_mnt (STB_LOCAL)
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
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fd900)
Location: fs/namespace.c:2049
Inline: False
Direct callers:
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff812fd900-ffffffff812fdc8a: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ee520)
Location: fs/namespace.c:2049
Inline: False
Direct callers:
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff812ee520-ffffffff812ee8aa: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fb6f0)
Location: fs/namespace.c:2049
Inline: False
Direct callers:
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff812fb6f0-ffffffff812fba7a: attach_recursive_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int attach_recursive_mnt(struct mount *source_mnt, struct mount *dest_mnt, struct mountpoint *dest_mp, bool moving);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130ca30)
Location: fs/namespace.c:2049
Inline: False
Direct callers:
  - fs/namespace.c:graft_tree
```
**Symbols:**

```
ffffffff8130ca30-ffffffff8130cd9f: attach_recursive_mnt (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool moving</code>
</li>
<li>
<b>Param removed. </b>
<code>struct path *parent_path</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mount *top_mnt</code>
</li>
<li>
<b>Param added. </b>
<code>enum mnt_tree_flags_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mount *dest_mnt</code>
</li>
<li>
<b>Param removed. </b>
<code>bool moving</code>
</li>
</ul>
</details>
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
