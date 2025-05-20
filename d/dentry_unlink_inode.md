# Function: <code>dentry_unlink_inode</code>

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
In fs/dcache.c (ffffffff8122429f)
Location: fs/dcache.c:355
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124a6b0)
Location: fs/dcache.c:323
Inline: False
Direct callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8124a6b0-ffffffff8124a805: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125d630)
Location: fs/dcache.c:323
Inline: False
Direct callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8125d630-ffffffff8125d785: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126b010)
Location: fs/dcache.c:355
Inline: False
Direct callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8126b010-ffffffff8126b146: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128d890)
Location: fs/dcache.c:355
Inline: False
Direct callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8128d890-ffffffff8128d9c9: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b4b80)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812b4b80-ffffffff812b4c58: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c9f80)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812c9f80-ffffffff812ca068: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6a00)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812e6a00-ffffffff812e6b06: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8650)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812f8650-ffffffff812f8756: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813315a0)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff813315a0-ffffffff813316a8: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133cf30)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8133cf30-ffffffff8133d042: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813433b0)
Location: fs/dcache.c:359
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff813433b0-ffffffff813434c2: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81390cf0)
Location: fs/dcache.c:359
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81390cf0-ffffffff81390e15: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81411f70)
Location: fs/dcache.c:384
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81411f70-ffffffff814120b1: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149cd50)
Location: fs/dcache.c:384
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff8149cd50-ffffffff8149ce91: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d2170)
Location: fs/dcache.c:384
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff814d2170-ffffffff814d22b1: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81504bb0)
Location: fs/dcache.c:383
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff81504bb0-ffffffff81504cf1: dentry_unlink_inode (STB_LOCAL)
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
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a5da0)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffff8000103a5da0-ffff8000103a5ed8: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0587458)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
c0587458-c05875b8: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c00000000049f0f0)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
c00000000049f0f0-c00000000049f300: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026cc10)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffe00026cc10-ffffffe00026cd72: dentry_unlink_inode (STB_LOCAL)
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
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0c30)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812f0c30-ffffffff812f0d36: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e1860)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812e1860-ffffffff812e1966: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812eea40)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812eea40-ffffffff812eeb46: dentry_unlink_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dentry_unlink_inode(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ff020)
Location: fs/dcache.c:357
Inline: False
Direct callers:
  - fs/dcache.c:__dentry_kill
```
**Symbols:**

```
ffffffff812ff020-ffffffff812ff122: dentry_unlink_inode (STB_LOCAL)
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
