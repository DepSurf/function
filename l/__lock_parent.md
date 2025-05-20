# Function: <code>__lock_parent</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b5250)
Location: fs/dcache.c:584
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff812b5250-ffffffff812b52bc: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ca5f0)
Location: fs/dcache.c:597
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff812ca5f0-ffffffff812ca65c: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6f00)
Location: fs/dcache.c:597
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812e6f00-ffffffff812e6f6c: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8a70)
Location: fs/dcache.c:597
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812f8a70-ffffffff812f8adc: __lock_parent (STB_LOCAL)
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
In fs/dcache.c (ffffffff81332c9a)
Location: fs/dcache.c:597
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133d5b0)
Location: fs/dcache.c:597
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff8133d5b0-ffffffff8133d621: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81343a30)
Location: fs/dcache.c:600
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff81343a30-ffffffff81343aa1: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81391450)
Location: fs/dcache.c:600
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
```
**Symbols:**

```
ffffffff81391450-ffffffff813914c1: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81413cd0)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
Direct callers:
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff81411620-ffffffff8141169e: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149f0e0)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
Direct callers:
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff8149c0b0-ffffffff8149c12e: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d4400)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
Direct callers:
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff814d12f0-ffffffff814d136e: __lock_parent (STB_LOCAL)
```
</details>
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
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a60e0)
Location: fs/dcache.c:597
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffff8000103a60e0-ffff8000103a620c: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0586d60)
Location: fs/dcache.c:597
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
c0586d60-c0586de0: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c00000000049fa90)
Location: fs/dcache.c:597
Inline: True
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
c00000000049fa90-c00000000049fbcc: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026d36c)
Location: fs/dcache.c:597
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffe00026d36c-ffffffe00026d434: __lock_parent (STB_LOCAL)
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
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1050)
Location: fs/dcache.c:597
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812f1050-ffffffff812f10bc: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e1c80)
Location: fs/dcache.c:597
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812e1c80-ffffffff812e1cec: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812eee60)
Location: fs/dcache.c:597
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812eee60-ffffffff812eeecc: __lock_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *__lock_parent(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fef40)
Location: fs/dcache.c:597
Inline: False
Direct callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff812fef40-ffffffff812fefb2: __lock_parent (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
