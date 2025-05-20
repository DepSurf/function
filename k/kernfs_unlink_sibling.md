# Function: <code>kernfs_unlink_sibling</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81289800)
Location: fs/kernfs/dir.c:429
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff81289800-ffffffff81289856: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b6cc0)
Location: fs/kernfs/dir.c:428
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_remove
```
**Symbols:**

```
ffffffff812b6cc0-ffffffff812b6d16: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cc4d0)
Location: fs/kernfs/dir.c:378
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_remove
```
**Symbols:**

```
ffffffff812cc4d0-ffffffff812cc526: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812d9aa0)
Location: fs/kernfs/dir.c:388
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff812d9aa0-ffffffff812d9af1: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812fe3a0)
Location: fs/kernfs/dir.c:389
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff812fe3a0-ffffffff812fe3f1: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132bea0)
Location: fs/kernfs/dir.c:389
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff8132bea0-ffffffff8132beef: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81343200)
Location: fs/kernfs/dir.c:389
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff81343200-ffffffff8134324f: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136b480)
Location: fs/kernfs/dir.c:388
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff8136b480-ffffffff8136b4cf: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81383650)
Location: fs/kernfs/dir.c:390
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff81383650-ffffffff8138369f: kernfs_unlink_sibling (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff813cfad6)
Location: fs/kernfs/dir.c:390
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
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
In fs/kernfs/dir.c (ffffffff813e1706)
Location: fs/kernfs/dir.c:390
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
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
In fs/kernfs/dir.c (ffffffff813e8336)
Location: fs/kernfs/dir.c:390
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81438380)
Location: fs/kernfs/dir.c:391
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff81438380-ffffffff814383d8: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b3520)
Location: fs/kernfs/dir.c:398
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff814b3520-ffffffff814b3580: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154a2f0)
Location: fs/kernfs/dir.c:409
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff8154a2f0-ffffffff8154a350: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81581f20)
Location: fs/kernfs/dir.c:406
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff81581f20-ffffffff81581f80: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815ba9c0)
Location: fs/kernfs/dir.c:408
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff815ba9c0-ffffffff815baa56: kernfs_unlink_sibling (STB_LOCAL)
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
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010451b90)
Location: fs/kernfs/dir.c:390
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffff800010451b90-ffff800010451c0c: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0614d7c)
Location: fs/kernfs/dir.c:390
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
c0614d7c-c0614de4: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056a9d0)
Location: fs/kernfs/dir.c:390
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
c00000000056a9d0-c00000000056aa70: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e47f0)
Location: fs/kernfs/dir.c:390
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffe0002e47f0-ffffffe0002e484a: kernfs_unlink_sibling (STB_LOCAL)
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
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137bc30)
Location: fs/kernfs/dir.c:390
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff8137bc30-ffffffff8137bc7f: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c700)
Location: fs/kernfs/dir.c:390
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff8136c700-ffffffff8136c74f: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81379700)
Location: fs/kernfs/dir.c:390
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff81379700-ffffffff8137974f: kernfs_unlink_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool kernfs_unlink_sibling(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138d390)
Location: fs/kernfs/dir.c:390
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
```
**Symbols:**

```
ffffffff8138d390-ffffffff8138d3df: kernfs_unlink_sibling (STB_LOCAL)
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
