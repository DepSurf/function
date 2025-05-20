# Function: <code>kernfs_put_open_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/file.c (ffffffff8128ba00)
Location: fs/kernfs/file.c:589
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_unmap_bin_file
```
**Symbols:**

```
ffffffff8128ba00-ffffffff8128ba9d: kernfs_put_open_node.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/file.c (ffffffff812b8e60)
Location: fs/kernfs/file.c:595
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_unmap_bin_file
  - fs/kernfs/file.c:kernfs_fop_release
```
**Symbols:**

```
ffffffff812b8e60-ffffffff812b8efd: kernfs_put_open_node.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/file.c (ffffffff812ce5c0)
Location: fs/kernfs/file.c:595
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_unmap_bin_file
  - fs/kernfs/file.c:kernfs_fop_release
```
**Symbols:**

```
ffffffff812ce5c0-ffffffff812ce65d: kernfs_put_open_node.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/file.c (ffffffff812dbbc0)
Location: fs/kernfs/file.c:594
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff812dbbc0-ffffffff812dbc5e: kernfs_put_open_node.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/file.c (ffffffff813004e0)
Location: fs/kernfs/file.c:594
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff813004e0-ffffffff8130057e: kernfs_put_open_node.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/file.c (ffffffff8132e1d0)
Location: fs/kernfs/file.c:594
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff8132e1d0-ffffffff8132e26e: kernfs_put_open_node.isra.13 (STB_LOCAL)
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
In fs/kernfs/file.c (ffffffff813455c0)
Location: fs/kernfs/file.c:594
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff813455c0-ffffffff8134565e: kernfs_put_open_node.isra.13 (STB_LOCAL)
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
In fs/kernfs/file.c (ffffffff8136d5e0)
Location: fs/kernfs/file.c:593
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff8136d5e0-ffffffff8136d677: kernfs_put_open_node.isra.0 (STB_LOCAL)
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
In fs/kernfs/file.c (ffffffff81385770)
Location: fs/kernfs/file.c:593
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff81385770-ffffffff81385807: kernfs_put_open_node.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kernfs_put_open_node(struct kernfs_node *kn, struct kernfs_open_file *of);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813cfcc0)
Location: fs/kernfs/file.c:593
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff813cfcc0-ffffffff813cfd58: kernfs_put_open_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kernfs_put_open_node(struct kernfs_node *kn, struct kernfs_open_file *of);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e1890)
Location: fs/kernfs/file.c:574
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff813e1890-ffffffff813e1928: kernfs_put_open_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kernfs_put_open_node(struct kernfs_node *kn, struct kernfs_open_file *of);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e84c0)
Location: fs/kernfs/file.c:574
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff813e84c0-ffffffff813e8558: kernfs_put_open_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kernfs_put_open_node(struct kernfs_node *kn, struct kernfs_open_file *of);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8143a1f0)
Location: fs/kernfs/file.c:574
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff8143a1f0-ffffffff8143a288: kernfs_put_open_node (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/kernfs/file.c (ffff800010454c78)
Location: fs/kernfs/file.c:593
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffff800010454c78-ffff800010454db4: kernfs_put_open_node.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kernfs_put_open_node(struct kernfs_node *kn, struct kernfs_open_file *of);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (c0616bec)
Location: fs/kernfs/file.c:593
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
c0616bec-c0616ca0: kernfs_put_open_node (STB_LOCAL)
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
In fs/kernfs/file.c (c00000000056e580)
Location: fs/kernfs/file.c:593
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
c00000000056e580-c00000000056e6a8: kernfs_put_open_node.isra.0 (STB_LOCAL)
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
In fs/kernfs/file.c (ffffffe0002e6b52)
Location: fs/kernfs/file.c:593
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffe0002e6b52-ffffffe0002e6bf8: kernfs_put_open_node.isra.0 (STB_LOCAL)
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
In fs/kernfs/file.c (ffffffff8137dd50)
Location: fs/kernfs/file.c:593
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff8137dd50-ffffffff8137dde7: kernfs_put_open_node.isra.0 (STB_LOCAL)
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
In fs/kernfs/file.c (ffffffff8136e800)
Location: fs/kernfs/file.c:593
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff8136e800-ffffffff8136e897: kernfs_put_open_node.isra.0 (STB_LOCAL)
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
In fs/kernfs/file.c (ffffffff8137b820)
Location: fs/kernfs/file.c:593
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff8137b820-ffffffff8137b8b7: kernfs_put_open_node.isra.0 (STB_LOCAL)
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
In fs/kernfs/file.c (ffffffff8138f4c0)
Location: fs/kernfs/file.c:593
Inline: True
Direct callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff8138f4c0-ffffffff8138f557: kernfs_put_open_node.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Arch</b>
<ul>
</ul>
