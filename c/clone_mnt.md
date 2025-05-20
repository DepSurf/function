# Function: <code>clone_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122c780)
Location: fs/namespace.c:967
Inline: False
Direct callers:
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff8122c780-ffffffff8122ca91: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81254f10)
Location: fs/namespace.c:967
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff81254f10-ffffffff8125522c: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81268470)
Location: fs/namespace.c:1010
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff81268470-ffffffff81268798: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812757f0)
Location: fs/namespace.c:1011
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff812757f0-ffffffff81275b02: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81298730)
Location: fs/namespace.c:1078
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff81298730-ffffffff81298a42: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812be690)
Location: fs/namespace.c:1088
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff812be690-ffffffff812be9b8: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d3a90)
Location: fs/namespace.c:1000
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff812d3a90-ffffffff812d3de0: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f0af0)
Location: fs/namespace.c:1024
Inline: False
Direct callers:
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff812f0af0-ffffffff812f0dcc: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81302690)
Location: fs/namespace.c:1024
Inline: False
Direct callers:
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff81302690-ffffffff8130296c: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133bcb0)
Location: fs/namespace.c:1040
Inline: False
Direct callers:
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff8133bcb0-ffffffff8133bfa6: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81347b50)
Location: fs/namespace.c:1040
Inline: False
Direct callers:
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff81347b50-ffffffff81347e46: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134e000)
Location: fs/namespace.c:1047
Inline: False
Direct callers:
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff8134e000-ffffffff8134e347: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139c000)
Location: fs/namespace.c:1056
Inline: False
Direct callers:
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff8139c000-ffffffff8139c347: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141ef80)
Location: fs/namespace.c:1097
Inline: False
Direct callers:
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff8141ef80-ffffffff8141f32b: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ab640)
Location: fs/namespace.c:1203
Inline: False
Direct callers:
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff814ab640-ffffffff814ab9dc: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e0440)
Location: fs/namespace.c:1166
Inline: False
Direct callers:
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff814e0440-ffffffff814e079d: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81513d00)
Location: fs/namespace.c:1179
Inline: False
Direct callers:
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff81513d00-ffffffff8151405d: clone_mnt (STB_LOCAL)
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
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b5790)
Location: fs/namespace.c:1024
Inline: False
Direct callers:
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffff8000103b5790-ffff8000103b5a5c: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0593ef0)
Location: fs/namespace.c:1024
Inline: False
Direct callers:
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
c0593ef0-c0594164: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b1a20)
Location: fs/namespace.c:1024
Inline: False
Direct callers:
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
c0000000004b1a20-c0000000004b1d88: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027870c)
Location: fs/namespace.c:1024
Inline: False
Direct callers:
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffe00027870c-ffffffe00027896e: clone_mnt (STB_LOCAL)
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
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fac70)
Location: fs/namespace.c:1024
Inline: False
Direct callers:
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff812fac70-ffffffff812faf4c: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812eb890)
Location: fs/namespace.c:1024
Inline: False
Direct callers:
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff812eb890-ffffffff812ebb6c: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f8a60)
Location: fs/namespace.c:1024
Inline: False
Direct callers:
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff812f8a60-ffffffff812f8d3c: clone_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mount *clone_mnt(struct mount *old, struct dentry *root, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81309180)
Location: fs/namespace.c:1024
Inline: False
Direct callers:
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_clone_internal
```
**Symbols:**

```
ffffffff81309180-ffffffff8130945a: clone_mnt (STB_LOCAL)
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
