# Function: <code>find_next_ancestor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *find_next_ancestor(struct kernfs_node *child, struct kernfs_node *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81288530)
Location: fs/kernfs/mount.c:75
Inline: True
Direct callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
```
**Symbols:**

```
ffffffff81288530-ffffffff81288578: find_next_ancestor (STB_LOCAL)
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
In fs/kernfs/mount.c (ffffffff812b5ab5)
Location: fs/kernfs/mount.c:89
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff812cb345)
Location: fs/kernfs/mount.c:89
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff812d87b8)
Location: fs/kernfs/mount.c:89
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff812fd038)
Location: fs/kernfs/mount.c:162
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff8132ac45)
Location: fs/kernfs/mount.c:162
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff81341f95)
Location: fs/kernfs/mount.c:162
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff8136a3a7)
Location: fs/kernfs/mount.c:150
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff8138259b)
Location: fs/kernfs/mount.c:150
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813ccd9b)
Location: fs/kernfs/mount.c:173
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813de9eb)
Location: fs/kernfs/mount.c:173
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff813e562b)
Location: fs/kernfs/mount.c:173
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff814371fb)
Location: fs/kernfs/mount.c:173
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct kernfs_node *find_next_ancestor(struct kernfs_node *child, struct kernfs_node *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:173
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
```
**Symbols:**

```
ffffffff814b1d90-ffffffff814b1def: find_next_ancestor (STB_LOCAL)
ffffffff81e7b2cc-ffffffff81e7b2f8: find_next_ancestor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct kernfs_node *find_next_ancestor(struct kernfs_node *child, struct kernfs_node *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:174
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
```
**Symbols:**

```
ffffffff81548890-ffffffff81548900: find_next_ancestor (STB_LOCAL)
ffffffff8206bbe7-ffffffff8206bbfb: find_next_ancestor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct kernfs_node *find_next_ancestor(struct kernfs_node *child, struct kernfs_node *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:174
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
```
**Symbols:**

```
ffffffff81580440-ffffffff815804b0: find_next_ancestor (STB_LOCAL)
ffffffff820eba75-ffffffff820eba89: find_next_ancestor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct kernfs_node *find_next_ancestor(struct kernfs_node *child, struct kernfs_node *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/mount.c (0)
Location: fs/kernfs/mount.c:181
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
```
**Symbols:**

```
ffffffff815b8de0-ffffffff815b8e50: find_next_ancestor (STB_LOCAL)
ffffffff821c8cd9-ffffffff821c8ced: find_next_ancestor.cold (STB_LOCAL)
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
In fs/kernfs/mount.c (ffff800010450a04)
Location: fs/kernfs/mount.c:150
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (c06139c0)
Location: fs/kernfs/mount.c:150
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (c000000000568c70)
Location: fs/kernfs/mount.c:150
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffe0002e3968)
Location: fs/kernfs/mount.c:150
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff8137ab7b)
Location: fs/kernfs/mount.c:150
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff8136b64b)
Location: fs/kernfs/mount.c:150
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff8137864b)
Location: fs/kernfs/mount.c:150
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
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
In fs/kernfs/mount.c (ffffffff8138c0fb)
Location: fs/kernfs/mount.c:150
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/kernfs/mount.c:kernfs_node_dentry
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
