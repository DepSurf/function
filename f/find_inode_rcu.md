# Function: <code>find_inode_rcu</code>

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
struct inode *find_inode_rcu(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813345f0)
Location: fs/inode.c:1477
Inline: False
```
**Symbols:**

```
ffffffff813345f0-ffffffff813346a1: find_inode_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *find_inode_rcu(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8133ff40)
Location: fs/inode.c:1476
Inline: False
```
**Symbols:**

```
ffffffff8133ff40-ffffffff8133fff1: find_inode_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *find_inode_rcu(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81346450)
Location: fs/inode.c:1483
Inline: False
```
**Symbols:**

```
ffffffff81346450-ffffffff81346501: find_inode_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_rcu(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1487
Inline: False
```
**Symbols:**

```
ffffffff81cc3c2c-ffffffff81cc3c50: find_inode_rcu.cold (STB_LOCAL)
ffffffff813952e0-ffffffff8139539a: find_inode_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_rcu(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1568
Inline: False
```
**Symbols:**

```
ffffffff81e764e3-ffffffff81e76507: find_inode_rcu.cold (STB_LOCAL)
ffffffff814182e0-ffffffff814183a3: find_inode_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_rcu(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1570
Inline: False
```
**Symbols:**

```
ffffffff82068a52-ffffffff82068a76: find_inode_rcu.cold (STB_LOCAL)
ffffffff814a3ba0-ffffffff814a3c63: find_inode_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_rcu(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1614
Inline: False
```
**Symbols:**

```
ffffffff820e8390-ffffffff820e83b4: find_inode_rcu.cold (STB_LOCAL)
ffffffff814d8d20-ffffffff814d8de3: find_inode_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_rcu(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1562
Inline: False
```
**Symbols:**

```
ffffffff821c50cd-ffffffff821c50f1: find_inode_rcu.cold (STB_LOCAL)
ffffffff8150b420-ffffffff8150b4e3: find_inode_rcu (STB_GLOBAL)
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
