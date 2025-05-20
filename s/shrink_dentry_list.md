# Function: <code>shrink_dentry_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81223bf0)
Location: fs/dcache.c:931
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:prune_dcache_sb
```
**Symbols:**

```
ffffffff81223bf0-ffffffff81223ef1: shrink_dentry_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124c2a0)
Location: fs/dcache.c:939
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
```
**Symbols:**

```
ffffffff8124c2a0-ffffffff8124c595: shrink_dentry_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125f280)
Location: fs/dcache.c:939
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
```
**Symbols:**

```
ffffffff8125f280-ffffffff8125f575: shrink_dentry_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126cbd0)
Location: fs/dcache.c:971
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
```
**Symbols:**

```
ffffffff8126cbd0-ffffffff8126ceb0: shrink_dentry_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128ef40)
Location: fs/dcache.c:983
Inline: False
Direct callers:
  - fs/dcache.c:d_invalidate
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
```
**Symbols:**

```
ffffffff8128ef40-ffffffff8128f242: shrink_dentry_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b6620)
Location: fs/dcache.c:1057
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
```
**Symbols:**

```
ffffffff812b6620-ffffffff812b67e2: shrink_dentry_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cb7d0)
Location: fs/dcache.c:1070
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
```
**Symbols:**

```
ffffffff812cb7d0-ffffffff812cb992: shrink_dentry_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e8960)
Location: fs/dcache.c:1096
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff812e8960-ffffffff812e8a15: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fa500)
Location: fs/dcache.c:1096
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff812fa500-ffffffff812fa5b5: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813335a0)
Location: fs/dcache.c:1117
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff813335a0-ffffffff81333656: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133ef10)
Location: fs/dcache.c:1124
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff8133ef10-ffffffff8133efd0: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81345380)
Location: fs/dcache.c:1152
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff81345380-ffffffff81345440: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81392f10)
Location: fs/dcache.c:1152
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff81392f10-ffffffff81393049: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81414620)
Location: fs/dcache.c:1177
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff81414620-ffffffff8141476f: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149faf0)
Location: fs/dcache.c:1177
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff8149faf0-ffffffff8149fc3f: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d4e10)
Location: fs/dcache.c:1177
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff814d4e10-ffffffff814d4f59: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81507100)
Location: fs/dcache.c:1056
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/dcache.c:d_prune_aliases
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff81507100-ffffffff81507272: shrink_dentry_list (STB_GLOBAL)
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
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a9550)
Location: fs/dcache.c:1096
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffff8000103a9550-ffff8000103a966c: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058a7f0)
Location: fs/dcache.c:1096
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
c058a7f0-c058a8b0: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a3fe0)
Location: fs/dcache.c:1096
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
c0000000004a3fe0-c0000000004a4134: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026f50e)
Location: fs/dcache.c:1096
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffe00026f50e-ffffffe00026f60c: shrink_dentry_list (STB_GLOBAL)
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
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f2ae0)
Location: fs/dcache.c:1096
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff812f2ae0-ffffffff812f2b95: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e3710)
Location: fs/dcache.c:1096
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff812e3710-ffffffff812e37c5: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f08f0)
Location: fs/dcache.c:1096
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff812f08f0-ffffffff812f09a5: shrink_dentry_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void shrink_dentry_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81301aa0)
Location: fs/dcache.c:1096
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:prune_dcache_sb
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff81301aa0-ffffffff81301b6b: shrink_dentry_list (STB_GLOBAL)
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
