# Function: <code>find_inode_by_ino_rcu</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *find_inode_by_ino_rcu(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813346b0)
Location: fs/inode.c:1515
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_update_other_inode_time
```
**Symbols:**

```
ffffffff813346b0-ffffffff8133472d: find_inode_by_ino_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *find_inode_by_ino_rcu(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81340000)
Location: fs/inode.c:1514
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_update_other_inode_time
```
**Symbols:**

```
ffffffff81340000-ffffffff8134007d: find_inode_by_ino_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *find_inode_by_ino_rcu(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81346510)
Location: fs/inode.c:1521
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_update_other_inode_time
```
**Symbols:**

```
ffffffff81346510-ffffffff81346593: find_inode_by_ino_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_by_ino_rcu(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1525
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_update_other_inode_time
```
**Symbols:**

```
ffffffff81cc3c08-ffffffff81cc3c2c: find_inode_by_ino_rcu.cold (STB_LOCAL)
ffffffff81395230-ffffffff813952d2: find_inode_by_ino_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_by_ino_rcu(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1606
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_update_other_inode_time
```
**Symbols:**

```
ffffffff81e764bf-ffffffff81e764e3: find_inode_by_ino_rcu.cold (STB_LOCAL)
ffffffff81418220-ffffffff814182d1: find_inode_by_ino_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_by_ino_rcu(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1608
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_update_other_inode_time
```
**Symbols:**

```
ffffffff82068a2e-ffffffff82068a52: find_inode_by_ino_rcu.cold (STB_LOCAL)
ffffffff814a3ad0-ffffffff814a3b81: find_inode_by_ino_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_by_ino_rcu(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1652
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_update_other_inode_time
```
**Symbols:**

```
ffffffff820e836c-ffffffff820e8390: find_inode_by_ino_rcu.cold (STB_LOCAL)
ffffffff814d8c50-ffffffff814d8d01: find_inode_by_ino_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_by_ino_rcu(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1600
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_update_other_inode_time
```
**Symbols:**

```
ffffffff821c50a9-ffffffff821c50cd: find_inode_by_ino_rcu.cold (STB_LOCAL)
ffffffff8150b350-ffffffff8150b401: find_inode_by_ino_rcu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
