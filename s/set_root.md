# Function: <code>set_root</code>

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
In fs/namei.c (ffffffff81217ab7)
Location: fs/namei.c:808
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:follow_dotdot
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123d260)
Location: fs/namei.c:813
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8123d260-ffffffff8123d30d: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81250000)
Location: fs/namei.c:813
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81250000-ffffffff812500ad: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125bf40)
Location: fs/namei.c:825
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8125bf40-ffffffff8125bff3: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127e300)
Location: fs/namei.c:826
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8127e300-ffffffff8127e3b3: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a6b20)
Location: fs/namei.c:810
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812a6b20-ffffffff812a6bd7: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bbd50)
Location: fs/namei.c:810
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812bbd50-ffffffff812bbe07: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8900)
Location: fs/namei.c:808
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812d8900-ffffffff812d89ad: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ea400)
Location: fs/namei.c:801
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812ea400-ffffffff812ea4b1: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81322060)
Location: fs/namei.c:836
Inline: False
Direct callers:
  - fs/namei.c:nd_jump_root
```
**Symbols:**

```
ffffffff81322060-ffffffff8132213f: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132d7d0)
Location: fs/namei.c:836
Inline: False
Direct callers:
  - fs/namei.c:nd_jump_root
```
**Symbols:**

```
ffffffff8132d7d0-ffffffff8132d8aa: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333520)
Location: fs/namei.c:896
Inline: False
Direct callers:
  - fs/namei.c:nd_jump_root
```
**Symbols:**

```
ffffffff81333520-ffffffff813335fa: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81380e50)
Location: fs/namei.c:924
Inline: False
Direct callers:
  - fs/namei.c:nd_jump_root
```
**Symbols:**

```
ffffffff81380e50-ffffffff81380f2a: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81401190)
Location: fs/namei.c:918
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:nd_jump_root
```
**Symbols:**

```
ffffffff81401190-ffffffff8140127d: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148b0c0)
Location: fs/namei.c:926
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:nd_jump_root
```
**Symbols:**

```
ffffffff8148b0c0-ffffffff8148b1ad: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c1d00)
Location: fs/namei.c:929
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:nd_jump_root
```
**Symbols:**

```
ffffffff814c1d00-ffffffff814c1ded: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f41c0)
Location: fs/namei.c:932
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:nd_jump_root
```
**Symbols:**

```
ffffffff814f41c0-ffffffff814f42ad: set_root (STB_LOCAL)
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
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010393ab8)
Location: fs/namei.c:801
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffff800010393ab8-ffff800010393bc4: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05784d4)
Location: fs/namei.c:801
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
```
**Symbols:**

```
c05784d4-c0578604: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000489dd0)
Location: fs/namei.c:801
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
```
**Symbols:**

```
c000000000489dd0-c000000000489f2c: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000262700)
Location: fs/namei.c:801
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffe000262700-ffffffe0002627f4: set_root (STB_LOCAL)
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
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e29e0)
Location: fs/namei.c:801
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812e29e0-ffffffff812e2a91: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d3620)
Location: fs/namei.c:801
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812d3620-ffffffff812d36d1: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e07f0)
Location: fs/namei.c:801
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812e07f0-ffffffff812e08a1: set_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812efd90)
Location: fs/namei.c:801
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812efd90-ffffffff812efe3f: set_root (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
