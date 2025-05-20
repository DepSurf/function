# Function: <code>kernfs_get_target_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff8128c1c1)
Location: fs/kernfs/symlink.c:49
Inline: True
Inline callers:
  - fs/kernfs/symlink.c:kernfs_iop_follow_link
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff812b97f2)
Location: fs/kernfs/symlink.c:49
Inline: True
Inline callers:
  - fs/kernfs/symlink.c:kernfs_iop_get_link
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
In fs/kernfs/symlink.c (ffffffff812cef32)
Location: fs/kernfs/symlink.c:49
Inline: True
Inline callers:
  - fs/kernfs/symlink.c:kernfs_iop_get_link
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
In fs/kernfs/symlink.c (ffffffff812dc5f7)
Location: fs/kernfs/symlink.c:49
Inline: True
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
In fs/kernfs/symlink.c (ffffffff81300f32)
Location: fs/kernfs/symlink.c:49
Inline: True
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
In fs/kernfs/symlink.c (ffffffff8132ec1d)
Location: fs/kernfs/symlink.c:58
Inline: True
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
In fs/kernfs/symlink.c (ffffffff81345fd1)
Location: fs/kernfs/symlink.c:58
Inline: True
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
In fs/kernfs/symlink.c (ffffffff8136e2ed)
Location: fs/kernfs/symlink.c:57
Inline: True
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
In fs/kernfs/symlink.c (ffffffff8138649d)
Location: fs/kernfs/symlink.c:57
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernfs_get_target_path(struct kernfs_node *parent, struct kernfs_node *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff813d1030)
Location: fs/kernfs/symlink.c:57
Inline: False
```
**Symbols:**

```
ffffffff813d1030-ffffffff813d1193: kernfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernfs_get_target_path(struct kernfs_node *parent, struct kernfs_node *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff813e2c40)
Location: fs/kernfs/symlink.c:57
Inline: False
```
**Symbols:**

```
ffffffff813e2c40-ffffffff813e2d97: kernfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernfs_get_target_path(struct kernfs_node *parent, struct kernfs_node *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff813e9850)
Location: fs/kernfs/symlink.c:57
Inline: False
```
**Symbols:**

```
ffffffff813e9850-ffffffff813e99bd: kernfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernfs_get_target_path(struct kernfs_node *parent, struct kernfs_node *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff8143b5c0)
Location: fs/kernfs/symlink.c:57
Inline: False
```
**Symbols:**

```
ffffffff8143b5c0-ffffffff8143b72d: kernfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernfs_get_target_path(struct kernfs_node *parent, struct kernfs_node *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff814b6890)
Location: fs/kernfs/symlink.c:56
Inline: False
```
**Symbols:**

```
ffffffff814b6890-ffffffff814b6a0c: kernfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernfs_get_target_path(struct kernfs_node *parent, struct kernfs_node *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff8154db70)
Location: fs/kernfs/symlink.c:56
Inline: False
```
**Symbols:**

```
ffffffff8154db70-ffffffff8154dced: kernfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernfs_get_target_path(struct kernfs_node *parent, struct kernfs_node *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff81585830)
Location: fs/kernfs/symlink.c:56
Inline: False
```
**Symbols:**

```
ffffffff81585830-ffffffff815859aa: kernfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernfs_get_target_path(struct kernfs_node *parent, struct kernfs_node *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff815be2e0)
Location: fs/kernfs/symlink.c:56
Inline: False
```
**Symbols:**

```
ffffffff815be2e0-ffffffff815be45a: kernfs_get_target_path (STB_LOCAL)
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
In fs/kernfs/symlink.c (ffff800010455f48)
Location: fs/kernfs/symlink.c:57
Inline: True
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
In fs/kernfs/symlink.c (c061803c)
Location: fs/kernfs/symlink.c:57
Inline: True
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
In fs/kernfs/symlink.c (c00000000056fb38)
Location: fs/kernfs/symlink.c:57
Inline: True
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
In fs/kernfs/symlink.c (ffffffe0002e78a2)
Location: fs/kernfs/symlink.c:57
Inline: True
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
In fs/kernfs/symlink.c (ffffffff8137ea7d)
Location: fs/kernfs/symlink.c:57
Inline: True
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
In fs/kernfs/symlink.c (ffffffff8136f50d)
Location: fs/kernfs/symlink.c:57
Inline: True
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
In fs/kernfs/symlink.c (ffffffff8137c54d)
Location: fs/kernfs/symlink.c:57
Inline: True
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
In fs/kernfs/symlink.c (ffffffff8139002d)
Location: fs/kernfs/symlink.c:57
Inline: True
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
