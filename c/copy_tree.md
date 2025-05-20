# Function: <code>copy_tree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122e490)
Location: fs/namespace.c:1673
Inline: False
Direct callers:
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:do_mount
  - fs/namespace.c:copy_mnt_ns
```
**Symbols:**

```
ffffffff8122e490-ffffffff8122e7e5: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81256c90)
Location: fs/namespace.c:1682
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff81256c90-ffffffff81257000: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81269c70)
Location: fs/namespace.c:1761
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff81269c70-ffffffff81269f71: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81277420)
Location: fs/namespace.c:1703
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff81277420-ffffffff81277723: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81299e60)
Location: fs/namespace.c:1768
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff81299e60-ffffffff8129a163: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bff80)
Location: fs/namespace.c:1799
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff812bff80-ffffffff812c0242: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d51a0)
Location: fs/namespace.c:1717
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff812d51a0-ffffffff812d5494: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f26a0)
Location: fs/namespace.c:1754
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff812f26a0-ffffffff812f2959: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81304260)
Location: fs/namespace.c:1757
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff81304260-ffffffff81304519: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133ddd0)
Location: fs/namespace.c:1812
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff8133ddd0-ffffffff8133e0e7: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81349e30)
Location: fs/namespace.c:1818
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff81349e30-ffffffff8134a147: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81350820)
Location: fs/namespace.c:1833
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff81350820-ffffffff81350b37: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139ebe0)
Location: fs/namespace.c:1834
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff8139ebe0-ffffffff8139eef7: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81421e90)
Location: fs/namespace.c:1875
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff81421e90-ffffffff814221a1: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ae4b0)
Location: fs/namespace.c:1980
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff814ae4b0-ffffffff814ae7c1: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e3450)
Location: fs/namespace.c:1967
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff814e3450-ffffffff814e3726: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff815171a0)
Location: fs/namespace.c:1969
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff815171a0-ffffffff8151747c: copy_tree (STB_GLOBAL)
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
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b7a58)
Location: fs/namespace.c:1757
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffff8000103b7a58-ffff8000103b7e34: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0595c48)
Location: fs/namespace.c:1757
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
c0595c48-c0595fb0: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b46d0)
Location: fs/namespace.c:1757
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
c0000000004b46d0-c0000000004b4b54: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027a4c4)
Location: fs/namespace.c:1757
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffe00027a4c4-ffffffe00027a7d0: copy_tree (STB_GLOBAL)
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
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fc840)
Location: fs/namespace.c:1757
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff812fc840-ffffffff812fcaf9: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ed460)
Location: fs/namespace.c:1757
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff812ed460-ffffffff812ed719: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fa630)
Location: fs/namespace.c:1757
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff812fa630-ffffffff812fa8e9: copy_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mount *copy_tree(struct mount *mnt, struct dentry *dentry, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130b960)
Location: fs/namespace.c:1757
Inline: False
Direct callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:collect_mounts
```
**Symbols:**

```
ffffffff8130b960-ffffffff8130bc15: copy_tree (STB_GLOBAL)
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
