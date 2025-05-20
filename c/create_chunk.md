# Function: <code>create_chunk</code>

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
In kernel/audit_tree.c (ffffffff8112b264)
Location: kernel/audit_tree.c:317
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffff8113346b)
Location: kernel/audit_tree.c:317
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffff8113d1a8)
Location: kernel/audit_tree.c:322
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffff8113e7cb)
Location: kernel/audit_tree.c:348
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffff8114b5d3)
Location: kernel/audit_tree.c:349
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffff8115a6f3)
Location: kernel/audit_tree.c:349
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffff811673ab)
Location: kernel/audit_tree.c:399
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffff81174102)
Location: kernel/audit_tree.c:399
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffff8117ff72)
Location: kernel/audit_tree.c:399
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int create_chunk(struct inode *inode, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81192f40)
Location: kernel/audit_tree.c:399
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_chunk
```
**Symbols:**

```
ffffffff81192f40-ffffffff811931db: create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_chunk(struct inode *inode, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811900b0)
Location: kernel/audit_tree.c:397
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_chunk
```
**Symbols:**

```
ffffffff811900b0-ffffffff8119034b: create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int create_chunk(struct inode *inode, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811913e0)
Location: kernel/audit_tree.c:397
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_chunk
```
**Symbols:**

```
ffffffff811913e0-ffffffff81191677: create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int create_chunk(struct inode *inode, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811ba2a0)
Location: kernel/audit_tree.c:397
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_chunk
```
**Symbols:**

```
ffffffff811ba2a0-ffffffff811ba537: create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int create_chunk(struct inode *inode, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811ed630)
Location: kernel/audit_tree.c:397
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_chunk
```
**Symbols:**

```
ffffffff811ed630-ffffffff811ed963: create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int create_chunk(struct inode *inode, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81233c00)
Location: kernel/audit_tree.c:397
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_chunk
```
**Symbols:**

```
ffffffff81233c00-ffffffff81233f33: create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int create_chunk(struct inode *inode, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8124a8f0)
Location: kernel/audit_tree.c:397
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_chunk
```
**Symbols:**

```
ffffffff8124a8f0-ffffffff8124ac23: create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int create_chunk(struct inode *inode, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81264800)
Location: kernel/audit_tree.c:397
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_chunk
```
**Symbols:**

```
ffffffff81264800-ffffffff81264b2a: create_chunk (STB_LOCAL)
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
In kernel/audit_tree.c (ffff8000101f5234)
Location: kernel/audit_tree.c:399
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (c04353cc)
Location: kernel/audit_tree.c:399
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (c00000000026a750)
Location: kernel/audit_tree.c:399
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffe0001682b8)
Location: kernel/audit_tree.c:399
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffff81178592)
Location: kernel/audit_tree.c:399
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffff8116b732)
Location: kernel/audit_tree.c:399
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffff81176362)
Location: kernel/audit_tree.c:399
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
In kernel/audit_tree.c (ffffffff81183c36)
Location: kernel/audit_tree.c:399
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
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
