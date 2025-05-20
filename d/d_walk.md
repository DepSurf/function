# Function: <code>d_walk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *), void (*finish)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81222ef0)
Location: fs/dcache.c:1159
Inline: False
Direct callers:
  - fs/dcache.c:have_submounts
  - fs/dcache.c:d_genocide
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:do_one_tree
```
**Symbols:**

```
ffffffff81222ef0-ffffffff8122317c: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *), void (*finish)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124acf0)
Location: fs/dcache.c:1167
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:have_submounts
```
**Symbols:**

```
ffffffff8124acf0-ffffffff8124af96: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *), void (*finish)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125dcb0)
Location: fs/dcache.c:1167
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff8125dcb0-ffffffff8125df56: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *), void (*finish)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126b4e0)
Location: fs/dcache.c:1200
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff8126b4e0-ffffffff8126b77d: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *), void (*finish)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128dd60)
Location: fs/dcache.c:1212
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:d_invalidate
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff8128dd60-ffffffff8128e006: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b6250)
Location: fs/dcache.c:1241
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff812b6250-ffffffff812b64e1: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cae90)
Location: fs/dcache.c:1250
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff812cae90-ffffffff812cb121: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e7ea0)
Location: fs/dcache.c:1267
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff812e7ea0-ffffffff812e812b: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f9a30)
Location: fs/dcache.c:1267
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff812f9a30-ffffffff812f9cbb: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813323d0)
Location: fs/dcache.c:1288
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff813323d0-ffffffff8133265b: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133e590)
Location: fs/dcache.c:1295
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff8133e590-ffffffff8133e821: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81344980)
Location: fs/dcache.c:1323
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff81344980-ffffffff81344c18: d_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81392470)
Location: fs/dcache.c:1323
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff81392470-ffffffff81392708: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814120c0)
Location: fs/dcache.c:1348
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff814120c0-ffffffff81412392: d_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149ceb0)
Location: fs/dcache.c:1348
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff8149ceb0-ffffffff8149d182: d_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d22d0)
Location: fs/dcache.c:1348
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff814d22d0-ffffffff814d25a6: d_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81504d10)
Location: fs/dcache.c:1222
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff81504d10-ffffffff81504fa1: d_walk (STB_LOCAL)
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
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a7380)
Location: fs/dcache.c:1267
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffff8000103a7380-ffff8000103a7760: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0588000)
Location: fs/dcache.c:1267
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
c0588000-c0588330: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a22f0)
Location: fs/dcache.c:1267
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
c0000000004a22f0-c0000000004a2800: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026e746)
Location: fs/dcache.c:1267
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffe00026e746-ffffffe00026eac4: d_walk (STB_GLOBAL)
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
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f2010)
Location: fs/dcache.c:1267
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff812f2010-ffffffff812f229b: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e2c40)
Location: fs/dcache.c:1267
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff812e2c40-ffffffff812e2ecb: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812efe20)
Location: fs/dcache.c:1267
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff812efe20-ffffffff812f00ab: d_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void d_walk(struct dentry *parent, void *data, enum d_walk_ret (*enter)(void *, struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ff990)
Location: fs/dcache.c:1267
Inline: False
Direct callers:
  - fs/dcache.c:d_genocide
  - fs/dcache.c:do_one_tree
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:path_has_submounts
```
**Symbols:**

```
ffffffff812ff990-ffffffff812ffc29: d_walk (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void (*finish)(void *)</code>
</li>
</ul>
</details>
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
