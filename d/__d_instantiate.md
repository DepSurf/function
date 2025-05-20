# Function: <code>__d_instantiate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81224370)
Location: fs/dcache.c:1743
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_no_diralias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_instantiate_unique
  - fs/dcache.c:d_instantiate_unique
```
**Symbols:**

```
ffffffff81224370-ffffffff81224452: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124b280)
Location: fs/dcache.c:1779
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_no_diralias
```
**Symbols:**

```
ffffffff8124b280-ffffffff8124b364: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125e260)
Location: fs/dcache.c:1788
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_no_diralias
```
**Symbols:**

```
ffffffff8125e260-ffffffff8125e344: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126bad0)
Location: fs/dcache.c:1818
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_no_diralias
```
**Symbols:**

```
ffffffff8126bad0-ffffffff8126bba7: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128e360)
Location: fs/dcache.c:1830
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_no_diralias
```
**Symbols:**

```
ffffffff8128e360-ffffffff8128e437: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b4c60)
Location: fs/dcache.c:1838
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff812b4c60-ffffffff812b4d35: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ca120)
Location: fs/dcache.c:1841
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff812ca120-ffffffff812ca205: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff812e6b90-ffffffff812e6c6e: __d_instantiate (STB_LOCAL)
ffffffff812e9d54-ffffffff812e9d67: __d_instantiate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8560)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff812f8560-ffffffff812f8645: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81331370)
Location: fs/dcache.c:1936
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff81331370-ffffffff81331455: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133cd00)
Location: fs/dcache.c:1943
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff8133cd00-ffffffff8133cde5: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81343180)
Location: fs/dcache.c:1970
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff81343180-ffffffff81343265: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81390a00)
Location: fs/dcache.c:1971
Inline: False
Direct callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff81390a00-ffffffff81390ae5: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814126f0)
Location: fs/dcache.c:1996
Inline: False
Direct callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff814126f0-ffffffff814127df: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149d920)
Location: fs/dcache.c:1996
Inline: False
Direct callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff8149d920-ffffffff8149da0f: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d2d60)
Location: fs/dcache.c:1996
Inline: False
Direct callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff814d2d60-ffffffff814d2e4f: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81505550)
Location: fs/dcache.c:1840
Inline: False
Direct callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff81505550-ffffffff8150563f: __d_instantiate (STB_LOCAL)
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
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a65c8)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffff8000103a65c8-ffff8000103a675c: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0588400)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
c0588400-c0588540: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a1220)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
c0000000004a1220-c0000000004a1410: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026ce54)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffe00026ce54-ffffffe00026cf96: __d_instantiate (STB_LOCAL)
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
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0b40)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff812f0b40-ffffffff812f0c25: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e1770)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff812e1770-ffffffff812e1855: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ee950)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff812ee950-ffffffff812eea35: __d_instantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ffcd0)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff812ffcd0-ffffffff812ffdb3: __d_instantiate (STB_LOCAL)
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
