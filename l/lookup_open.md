# Function: <code>lookup_open</code>

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
In fs/namei.c (ffffffff8121a9e2)
Location: fs/namei.c:2950
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff81241d89)
Location: fs/namei.c:3078
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff81254c6a)
Location: fs/namei.c:3042
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff81260cd6)
Location: fs/namei.c:3093
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff812833c4)
Location: fs/namei.c:3091
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int lookup_open(struct nameidata *nd, struct path *path, struct file *file, const struct open_flags *op, bool got_write, int *opened);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a9dc0)
Location: fs/namei.c:3113
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812a9dc0-ffffffff812aa4ec: lookup_open (STB_LOCAL)
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
In fs/namei.c (ffffffff812bfb57)
Location: fs/namei.c:3127
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int lookup_open(struct nameidata *nd, struct path *path, struct file *file, const struct open_flags *op, bool got_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namei.c (0)
Location: fs/namei.c:3125
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff812dc290-ffffffff812dc937: lookup_open (STB_LOCAL)
ffffffff812dfcd7-ffffffff812dfd34: lookup_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int lookup_open(struct nameidata *nd, struct path *path, struct file *file, const struct open_flags *op, bool got_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812edda0)
Location: fs/namei.c:3118
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff812edda0-ffffffff812ee478: lookup_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81325b20)
Location: fs/namei.c:3003
Inline: True
Direct callers:
  - fs/namei.c:open_last_lookups
```
**Symbols:**

```
ffffffff81325b20-ffffffff81325ee2: lookup_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81330fc0)
Location: fs/namei.c:3009
Inline: True
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
```
**Symbols:**

```
ffffffff81330fc0-ffffffff81331382: lookup_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81337790)
Location: fs/namei.c:3119
Inline: True
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
```
**Symbols:**

```
ffffffff81337790-ffffffff81337d4f: lookup_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81385220)
Location: fs/namei.c:3186
Inline: True
Direct callers:
  - fs/namei.c:open_last_lookups
```
**Symbols:**

```
ffffffff81385220-ffffffff813857df: lookup_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81402650)
Location: fs/namei.c:3280
Inline: True
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
```
**Symbols:**

```
ffffffff81402650-ffffffff81402c47: lookup_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff8148c7b0)
Location: fs/namei.c:3318
Inline: True
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
```
**Symbols:**

```
ffffffff8148c7b0-ffffffff8148cddd: lookup_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff814c0010)
Location: fs/namei.c:3397
Inline: True
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
```
**Symbols:**

```
ffffffff814c0010-ffffffff814c05b5: lookup_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff814f2530)
Location: fs/namei.c:3405
Inline: True
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
```
**Symbols:**

```
ffffffff814f2530-ffffffff814f2a93: lookup_open.isra.0 (STB_LOCAL)
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
int lookup_open(struct nameidata *nd, struct path *path, struct file *file, const struct open_flags *op, bool got_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010397590)
Location: fs/namei.c:3118
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
```
**Symbols:**

```
ffff800010397590-ffff800010397c5c: lookup_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int lookup_open(struct nameidata *nd, struct path *path, struct file *file, const struct open_flags *op, bool got_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057db30)
Location: fs/namei.c:3118
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
```
**Symbols:**

```
c057db30-c057e22c: lookup_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int lookup_open(struct nameidata *nd, struct path *path, struct file *file, const struct open_flags *op, bool got_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000491410)
Location: fs/namei.c:3118
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
```
**Symbols:**

```
c000000000491410-c000000000491c2c: lookup_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lookup_open(struct nameidata *nd, struct path *path, struct file *file, const struct open_flags *op, bool got_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe00026563a)
Location: fs/namei.c:3118
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffe00026563a-ffffffe000265b4c: lookup_open (STB_LOCAL)
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
int lookup_open(struct nameidata *nd, struct path *path, struct file *file, const struct open_flags *op, bool got_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e6380)
Location: fs/namei.c:3118
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff812e6380-ffffffff812e6a58: lookup_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int lookup_open(struct nameidata *nd, struct path *path, struct file *file, const struct open_flags *op, bool got_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d6fc0)
Location: fs/namei.c:3118
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff812d6fc0-ffffffff812d7698: lookup_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int lookup_open(struct nameidata *nd, struct path *path, struct file *file, const struct open_flags *op, bool got_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e4190)
Location: fs/namei.c:3118
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff812e4190-ffffffff812e4868: lookup_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int lookup_open(struct nameidata *nd, struct path *path, struct file *file, const struct open_flags *op, bool got_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f5110)
Location: fs/namei.c:3118
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff812f5110-ffffffff812f57e4: lookup_open (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
