# Function: <code>__d_obtain_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, int disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81225a50)
Location: fs/dcache.c:1932
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_alias
  - fs/dcache.c:d_obtain_root
```
**Symbols:**

```
ffffffff81225a50-ffffffff81225c25: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, int disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124db80)
Location: fs/dcache.c:1891
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff8124db80-ffffffff8124dd40: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, int disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81260c60)
Location: fs/dcache.c:1900
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff81260c60-ffffffff81260e20: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff8126e430)
Location: fs/dcache.c:1930
Inline: True
```
**Symbols:**

```
ffffffff8126e430-ffffffff8126e5e3: __d_obtain_alias.part.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff81290d50)
Location: fs/dcache.c:1942
Inline: True
```
**Symbols:**

```
ffffffff81290d50-ffffffff81290f03: __d_obtain_alias.part.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812b7570)
Location: fs/dcache.c:1991
Inline: True
```
**Symbols:**

```
ffffffff812b7570-ffffffff812b75d9: __d_obtain_alias.part.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812cc6d0)
Location: fs/dcache.c:1972
Inline: True
```
**Symbols:**

```
ffffffff812cc6d0-ffffffff812cc739: __d_obtain_alias.part.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e92b0)
Location: fs/dcache.c:2044
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff812e92b0-ffffffff812e933b: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fae50)
Location: fs/dcache.c:2044
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff812fae50-ffffffff812faedb: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81332f40)
Location: fs/dcache.c:2065
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff81332f40-ffffffff81333011: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133e470)
Location: fs/dcache.c:2072
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff8133e470-ffffffff8133e541: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81344860)
Location: fs/dcache.c:2099
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff81344860-ffffffff81344931: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81392350)
Location: fs/dcache.c:2100
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff81392350-ffffffff81392421: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81414000)
Location: fs/dcache.c:2125
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff81414000-ffffffff814140f7: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149f450)
Location: fs/dcache.c:2125
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff8149f450-ffffffff8149f547: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d4770)
Location: fs/dcache.c:2125
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff814d4770-ffffffff814d4867: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81506960)
Location: fs/dcache.c:1923
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff81506960-ffffffff81506bb0: __d_obtain_alias (STB_LOCAL)
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
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103aa158)
Location: fs/dcache.c:2044
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffff8000103aa158-ffff8000103aa20c: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058b164)
Location: fs/dcache.c:2044
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
c058b164-c058b1e8: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a4fc0)
Location: fs/dcache.c:2044
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
c0000000004a4fc0-c0000000004a50b8: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026fef8)
Location: fs/dcache.c:2044
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffe00026fef8-ffffffe00026ff8c: __d_obtain_alias (STB_LOCAL)
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
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f3430)
Location: fs/dcache.c:2044
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff812f3430-ffffffff812f34bb: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e4060)
Location: fs/dcache.c:2044
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff812e4060-ffffffff812e40eb: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1240)
Location: fs/dcache.c:2044
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff812f1240-ffffffff812f12cb: __d_obtain_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *__d_obtain_alias(struct inode *inode, bool disconnected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81302400)
Location: fs/dcache.c:2044
Inline: False
Direct callers:
  - fs/dcache.c:d_obtain_root
  - fs/dcache.c:d_obtain_alias
```
**Symbols:**

```
ffffffff81302400-ffffffff8130248b: __d_obtain_alias (STB_LOCAL)
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
