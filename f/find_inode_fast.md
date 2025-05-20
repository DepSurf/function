# Function: <code>find_inode_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227390)
Location: fs/inode.c:801
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff81227390-ffffffff81227424: find_inode_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124fab0)
Location: fs/inode.c:810
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff8124fab0-ffffffff8124fb43: find_inode_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262ae0)
Location: fs/inode.c:812
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff81262ae0-ffffffff81262b73: find_inode_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81270370)
Location: fs/inode.c:813
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff81270370-ffffffff81270402: find_inode_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81292cb0)
Location: fs/inode.c:813
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff81292cb0-ffffffff81292d42: find_inode_fast (STB_LOCAL)
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
In fs/inode.c (ffffffff812b9900)
Location: fs/inode.c:818
Inline: True
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff812b9900-ffffffff812b9992: find_inode_fast.isra.25 (STB_LOCAL)
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
In fs/inode.c (ffffffff812cf490)
Location: fs/inode.c:822
Inline: True
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff812cf490-ffffffff812cf53c: find_inode_fast.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812ec3c0)
Location: fs/inode.c:835
Inline: True
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff812ec3c0-ffffffff812ec474: find_inode_fast.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812fdf10)
Location: fs/inode.c:846
Inline: True
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff812fdf10-ffffffff812fdfc4: find_inode_fast.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813365d0)
Location: fs/inode.c:847
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff813365d0-ffffffff81336684: find_inode_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81341f30)
Location: fs/inode.c:846
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff81341f30-ffffffff81341fe4: find_inode_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81348320)
Location: fs/inode.c:853
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff81348320-ffffffff813483d4: find_inode_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81395f40)
Location: fs/inode.c:857
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff81395f40-ffffffff81395ff4: find_inode_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814166f0)
Location: fs/inode.c:938
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff814166f0-ffffffff814167b0: find_inode_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a1b10)
Location: fs/inode.c:937
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff814a1b10-ffffffff814a1bd0: find_inode_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d6c60)
Location: fs/inode.c:939
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff814d6c60-ffffffff814d6d20: find_inode_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81509100)
Location: fs/inode.c:924
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff81509100-ffffffff815091c0: find_inode_fast (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffff8000103ada70)
Location: fs/inode.c:846
Inline: True
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffff8000103ada70-ffff8000103adba0: find_inode_fast.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *find_inode_fast(struct super_block *sb, struct hlist_head *head, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058cec8)
Location: fs/inode.c:846
Inline: False
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
c058cec8-c058cfb8: find_inode_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (c0000000004a7e80)
Location: fs/inode.c:846
Inline: True
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
c0000000004a7e80-c0000000004a8008: find_inode_fast.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffe00027353c)
Location: fs/inode.c:846
Inline: True
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffe00027353c-ffffffe000273654: find_inode_fast.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812f64f0)
Location: fs/inode.c:846
Inline: True
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff812f64f0-ffffffff812f65a4: find_inode_fast.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812e7110)
Location: fs/inode.c:846
Inline: True
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff812e7110-ffffffff812e71c4: find_inode_fast.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812f4300)
Location: fs/inode.c:846
Inline: True
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff812f4300-ffffffff812f43b4: find_inode_fast.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff81304670)
Location: fs/inode.c:846
Inline: True
Direct callers:
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff81304670-ffffffff81304720: find_inode_fast.isra.0 (STB_LOCAL)
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
</ul>
