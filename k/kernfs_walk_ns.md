# Function: <code>kernfs_walk_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b7cd6)
Location: fs/kernfs/dir.c:820
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd476)
Location: fs/kernfs/dir.c:770
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812daa38)
Location: fs/kernfs/dir.c:780
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff318)
Location: fs/kernfs/dir.c:846
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132cfd8)
Location: fs/kernfs/dir.c:863
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81344378)
Location: fs/kernfs/dir.c:863
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c596)
Location: fs/kernfs/dir.c:864
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384746)
Location: fs/kernfs/dir.c:864
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_ns(struct kernfs_node *parent, const unsigned char *path, const void *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813ce4f0)
Location: fs/kernfs/dir.c:858
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
**Symbols:**

```
ffffffff813ce4f0-ffffffff813ce626: kernfs_walk_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_ns(struct kernfs_node *parent, const unsigned char *path, const void *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e0120)
Location: fs/kernfs/dir.c:857
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
**Symbols:**

```
ffffffff813e0120-ffffffff813e0256: kernfs_walk_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e7986)
Location: fs/kernfs/dir.c:857
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439696)
Location: fs/kernfs/dir.c:816
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
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
In fs/kernfs/dir.c (ffffffff814b4735)
Location: fs/kernfs/dir.c:825
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
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
In fs/kernfs/dir.c (ffffffff8154b645)
Location: fs/kernfs/dir.c:843
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
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
In fs/kernfs/dir.c (ffffffff81583295)
Location: fs/kernfs/dir.c:845
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_walk_ns(struct kernfs_node *parent, const unsigned char *path, const void *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815babd0)
Location: fs/kernfs/dir.c:861
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
**Symbols:**

```
ffffffff815babd0-ffffffff815bad08: kernfs_walk_ns (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010453574)
Location: fs/kernfs/dir.c:864
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0616100)
Location: fs/kernfs/dir.c:864
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056c8f8)
Location: fs/kernfs/dir.c:864
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e5ba8)
Location: fs/kernfs/dir.c:864
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137cd26)
Location: fs/kernfs/dir.c:864
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136d7f6)
Location: fs/kernfs/dir.c:864
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137a7f6)
Location: fs/kernfs/dir.c:864
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e306)
Location: fs/kernfs/dir.c:864
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
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
</ul>
