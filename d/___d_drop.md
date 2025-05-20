# Function: <code>___d_drop</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128e8d0)
Location: fs/dcache.c:475
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
```
**Symbols:**

```
ffffffff8128e8d0-ffffffff8128e949: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b4850)
Location: fs/dcache.c:463
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812b4850-ffffffff812b48b9: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c9ad0)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812c9ad0-ffffffff812c9b39: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e64e0)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812e64e0-ffffffff812e6549: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8040)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812f8040-ffffffff812f80a9: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81330dc0)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81330dc0-ffffffff81330e29: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133c750)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8133c750-ffffffff8133c7b9: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81342bd0)
Location: fs/dcache.c:461
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81342bd0-ffffffff81342c39: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:461
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff813905f0-ffffffff81390675: ___d_drop (STB_LOCAL)
ffffffff81cc3b50-ffffffff81cc3b6f: ___d_drop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:486
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81412dd0-ffffffff81412ea6: ___d_drop (STB_LOCAL)
ffffffff81e76384-ffffffff81e763a3: ___d_drop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:486
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8149e040-ffffffff8149e116: ___d_drop (STB_LOCAL)
ffffffff82068956-ffffffff82068975: ___d_drop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:486
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff814d3360-ffffffff814d3436: ___d_drop (STB_LOCAL)
ffffffff820e8294-ffffffff820e82b3: ___d_drop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:487
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81505af0-ffffffff81505bc6: ___d_drop (STB_LOCAL)
ffffffff821c4fd1-ffffffff821c4ff0: ___d_drop.cold (STB_LOCAL)
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
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a5508)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffff8000103a5508-ffff8000103a55e4: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0588a40)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
c0588a40-c0588b58: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a09b0)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
c0000000004a09b0-c0000000004a0a9c: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026bc06)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffe00026bc06-ffffffe00026bc88: ___d_drop (STB_LOCAL)
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
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0620)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812f0620-ffffffff812f0689: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e1250)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812e1250-ffffffff812e12b9: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ee430)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812ee430-ffffffff812ee499: ___d_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ___d_drop(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813001a0)
Location: fs/dcache.c:476
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff813001a0-ffffffff81300230: ___d_drop (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
