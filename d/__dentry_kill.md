# Function: <code>__dentry_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81223630)
Location: fs/dcache.c:499
Inline: False
Direct callers:
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff81223630-ffffffff8122380a: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124bd10)
Location: fs/dcache.c:509
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff8124bd10-ffffffff8124be69: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125ecf0)
Location: fs/dcache.c:509
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff8125ecf0-ffffffff8125ee49: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126c6c0)
Location: fs/dcache.c:543
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_prune_aliases
```
**Symbols:**

```
ffffffff8126c6c0-ffffffff8126c810: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128e9f0)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_prune_aliases
```
**Symbols:**

```
ffffffff8128e9f0-ffffffff8128eb51: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b52c0)
Location: fs/dcache.c:537
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff812b52c0-ffffffff812b5427: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ca480)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff812ca480-ffffffff812ca5e7: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e7060)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812e7060-ffffffff812e71d9: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8bd0)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812f8bd0-ffffffff812f8d49: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81331a80)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff81331a80-ffffffff81331c06: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133d420)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff8133d420-ffffffff8133d5a6: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813437d0)
Location: fs/dcache.c:553
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff813437d0-ffffffff81343953: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813911f0)
Location: fs/dcache.c:553
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff813911f0-ffffffff81391373: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81412eb0)
Location: fs/dcache.c:578
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff81412eb0-ffffffff8141303c: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149e130)
Location: fs/dcache.c:578
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff8149e130-ffffffff8149e2bc: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d3450)
Location: fs/dcache.c:578
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff814d3450-ffffffff814d35dc: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *__dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81505be0)
Location: fs/dcache.c:579
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff81505be0-ffffffff81505d58: __dentry_kill (STB_LOCAL)
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
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a6d78)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffff8000103a6d78-ffff8000103a6f5c: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0588ca0)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
c0588ca0-c0588e60: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a0d00)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
c0000000004a0d00-c0000000004a0fac: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026d5ec)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffe00026d5ec-ffffffe00026d7f6: __dentry_kill (STB_LOCAL)
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
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f11b0)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812f11b0-ffffffff812f1329: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e1de0)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812e1de0-ffffffff812e1f59: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812eefc0)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812eefc0-ffffffff812ef139: __dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81300340)
Location: fs/dcache.c:550
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff81300340-ffffffff813004b0: __dentry_kill (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct dentry *</code>
</li>
</ul>
</details>
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
