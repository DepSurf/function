# Function: <code>__d_instantiate_anon</code>

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
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b6090)
Location: fs/dcache.c:1945
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff812b6090-ffffffff812b6229: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cb610)
Location: fs/dcache.c:1926
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff812cb610-ffffffff812cb7a9: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e7c60)
Location: fs/dcache.c:1998
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff812e7c60-ffffffff812e7de9: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f97f0)
Location: fs/dcache.c:1998
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff812f97f0-ffffffff812f9979: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81332d90)
Location: fs/dcache.c:2019
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff81332d90-ffffffff81332f19: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133e2c0)
Location: fs/dcache.c:2026
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff8133e2c0-ffffffff8133e449: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813446b0)
Location: fs/dcache.c:2053
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff813446b0-ffffffff81344839: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813921a0)
Location: fs/dcache.c:2054
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff813921a0-ffffffff81392329: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81413e00)
Location: fs/dcache.c:2079
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff81413e00-ffffffff81413fda: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149f230)
Location: fs/dcache.c:2079
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff8149f230-ffffffff8149f40a: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d4550)
Location: fs/dcache.c:2079
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff814d4550-ffffffff814d472b: __d_instantiate_anon (STB_LOCAL)
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
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a7f18)
Location: fs/dcache.c:1998
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffff8000103a7f18-ffff8000103a8150: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0589e38)
Location: fs/dcache.c:1998
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
c0589e38-c058a038: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a3210)
Location: fs/dcache.c:1998
Inline: True
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
c0000000004a3210-c0000000004a34d0: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026e43c)
Location: fs/dcache.c:1998
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffe00026e43c-ffffffe00026e612: __d_instantiate_anon (STB_LOCAL)
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
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1dd0)
Location: fs/dcache.c:1998
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff812f1dd0-ffffffff812f1f59: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e2a00)
Location: fs/dcache.c:1998
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff812e2a00-ffffffff812e2b89: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812efbe0)
Location: fs/dcache.c:1998
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff812efbe0-ffffffff812efd69: __d_instantiate_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *__d_instantiate_anon(struct dentry *dentry, struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81301150)
Location: fs/dcache.c:1998
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_anon
```
**Symbols:**

```
ffffffff81301150-ffffffff81301303: __d_instantiate_anon (STB_LOCAL)
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
