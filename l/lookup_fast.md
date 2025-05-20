# Function: <code>lookup_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81217600)
Location: fs/namei.c:1528
Inline: False
Direct callers:
  - fs/namei.c:walk_component
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81217600-ffffffff8121792a: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123e870)
Location: fs/namei.c:1534
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8123e870-ffffffff8123eb71: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81251640)
Location: fs/namei.c:1530
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81251640-ffffffff81251941: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125dd90)
Location: fs/namei.c:1537
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8125dd90-ffffffff8125e094: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81280100)
Location: fs/namei.c:1535
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81280100-ffffffff81280418: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a65e0)
Location: fs/namei.c:1513
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812a65e0-ffffffff812a690c: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bb6b0)
Location: fs/namei.c:1554
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812bb6b0-ffffffff812bb9dc: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8390)
Location: fs/namei.c:1552
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812d8390-ffffffff812d86e1: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9f00)
Location: fs/namei.c:1547
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812e9f00-ffffffff812ea1fb: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *lookup_fast(struct nameidata *nd, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321e60)
Location: fs/namei.c:1453
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81321e60-ffffffff81321fae: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *lookup_fast(struct nameidata *nd, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132d420)
Location: fs/namei.c:1453
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8132d420-ffffffff8132d56e: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *lookup_fast(struct nameidata *nd, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813332d0)
Location: fs/namei.c:1538
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff813332d0-ffffffff81333428: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *lookup_fast(struct nameidata *nd, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81380c00)
Location: fs/namei.c:1566
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81380c00-ffffffff81380d58: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *lookup_fast(struct nameidata *nd, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81401010)
Location: fs/namei.c:1612
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81401010-ffffffff81401181: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *lookup_fast(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148aee0)
Location: fs/namei.c:1609
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8148aee0-ffffffff8148afd8: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *lookup_fast(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c15f0)
Location: fs/namei.c:1614
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff814c15f0-ffffffff814c16ec: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *lookup_fast(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f3ab0)
Location: fs/namei.c:1617
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff814f3ab0-ffffffff814f3bac: lookup_fast (STB_LOCAL)
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
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff8000103933a0)
Location: fs/namei.c:1547
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffff8000103933a0-ffff80001039367c: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057a51c)
Location: fs/namei.c:1547
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
```
**Symbols:**

```
c057a51c-c057a7dc: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048cc40)
Location: fs/namei.c:1547
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
```
**Symbols:**

```
c00000000048cc40-c00000000048d00c: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe00026234c)
Location: fs/namei.c:1547
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffe00026234c-ffffffe000262562: lookup_fast (STB_LOCAL)
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
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e24e0)
Location: fs/namei.c:1547
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812e24e0-ffffffff812e27db: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d3120)
Location: fs/namei.c:1547
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812d3120-ffffffff812d341b: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e02f0)
Location: fs/namei.c:1547
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812e02f0-ffffffff812e05eb: lookup_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int lookup_fast(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1bd0)
Location: fs/namei.c:1547
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812f1bd0-ffffffff812f1ee6: lookup_fast (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct path *path</code>
</li>
<li>
<b>Param reordered. </b>
<code>nd, path, inode, seqp</code> ➡️ <code>nd, inode, seqp</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct dentry *</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct inode **inode</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *seqp</code>
</li>
</ul>
</details>
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
