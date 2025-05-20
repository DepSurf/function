# Function: <code>unlazy_walk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd, struct dentry *dentry, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812174b0)
Location: fs/namei.c:680
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812174b0-ffffffff812175f4: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd, struct dentry *dentry, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123e6f0)
Location: fs/namei.c:685
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff8123e6f0-ffffffff8123e86b: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd, struct dentry *dentry, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812514c0)
Location: fs/namei.c:685
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff812514c0-ffffffff8125163b: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125d270)
Location: fs/namei.c:683
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff8125d270-ffffffff8125d311: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127f5f0)
Location: fs/namei.c:684
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff8127f5f0-ffffffff8127f691: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a5a80)
Location: fs/namei.c:668
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff812a5a80-ffffffff812a5b29: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812babf0)
Location: fs/namei.c:668
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff812babf0-ffffffff812bac99: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d7bd0)
Location: fs/namei.c:666
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff812d7bd0-ffffffff812d7c79: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9780)
Location: fs/namei.c:672
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff812e9780-ffffffff812e97fa: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321010)
Location: fs/namei.c:682
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff81321010-ffffffff81321086: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010392bd0)
Location: fs/namei.c:672
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffff800010392bd0-ffff800010392c70: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05792ec)
Location: fs/namei.c:672
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
c05792ec-c0579380: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048bee0)
Location: fs/namei.c:672
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
c00000000048bee0-c00000000048bfb4: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000261cfa)
Location: fs/namei.c:672
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffe000261cfa-ffffffe000261d82: unlazy_walk (STB_LOCAL)
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
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e1d60)
Location: fs/namei.c:672
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff812e1d60-ffffffff812e1dda: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d29a0)
Location: fs/namei.c:672
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff812d29a0-ffffffff812d2a1a: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dfb70)
Location: fs/namei.c:672
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff812dfb70-ffffffff812dfbea: unlazy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1220)
Location: fs/namei.c:672
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff812f1220-ffffffff812f12a4: unlazy_walk (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int seq</code>
</li>
</ul>
</details>
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
