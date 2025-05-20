# Function: <code>ext4_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a4920)
Location: fs/ext4/namei.c:1555
Inline: True
```
**Symbols:**

```
ffffffff812a4920-ffffffff812a4b15: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d38f0)
Location: fs/ext4/namei.c:1565
Inline: True
```
**Symbols:**

```
ffffffff812d38f0-ffffffff812d3b8a: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e9630)
Location: fs/ext4/namei.c:1567
Inline: True
```
**Symbols:**

```
ffffffff812e9630-ffffffff812e98ca: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81318e40)
Location: fs/ext4/namei.c:1536
Inline: True
```
**Symbols:**

```
ffffffff81318e40-ffffffff81319095: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133d5d0)
Location: fs/ext4/namei.c:1541
Inline: True
```
**Symbols:**

```
ffffffff8133d5d0-ffffffff8133d7dc: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136bb70)
Location: fs/ext4/namei.c:1543
Inline: True
```
**Symbols:**

```
ffffffff8136bb70-ffffffff8136bd71: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81384030)
Location: fs/ext4/namei.c:1544
Inline: True
```
**Symbols:**

```
ffffffff81384030-ffffffff81384248: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ad7f0)
Location: fs/ext4/namei.c:1675
Inline: True
```
**Symbols:**

```
ffffffff813ad7f0-ffffffff813ada52: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c6730)
Location: fs/ext4/namei.c:1676
Inline: True
```
**Symbols:**

```
ffffffff813c6730-ffffffff813c6992: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff81412c50)
Location: fs/ext4/namei.c:1682
Inline: True
```
**Symbols:**

```
ffffffff81412c50-ffffffff81412e79: ext4_lookup.part.0 (STB_LOCAL)
ffffffff81412e80-ffffffff81412ea1: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff81426240)
Location: fs/ext4/namei.c:1672
Inline: True
```
**Symbols:**

```
ffffffff81426240-ffffffff81426465: ext4_lookup.part.0 (STB_LOCAL)
ffffffff81426470-ffffffff81426491: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142cdc0)
Location: fs/ext4/namei.c:1759
Inline: True
```
**Symbols:**

```
ffffffff8142cdc0-ffffffff8142cfe5: ext4_lookup.part.0 (STB_LOCAL)
ffffffff8142cff0-ffffffff8142d011: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff81480cd0)
Location: fs/ext4/namei.c:1760
Inline: True
```
**Symbols:**

```
ffffffff81480cd0-ffffffff81480ef5: ext4_lookup.part.0 (STB_LOCAL)
ffffffff81480f00-ffffffff81480f21: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81503c00)
Location: fs/ext4/namei.c:1806
Inline: False
```
**Symbols:**

```
ffffffff81503c00-ffffffff81503e7f: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159e7a0)
Location: fs/ext4/namei.c:1811
Inline: False
```
**Symbols:**

```
ffffffff8159e7a0-ffffffff8159ea1f: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d50a0)
Location: fs/ext4/namei.c:1826
Inline: False
```
**Symbols:**

```
ffffffff815d50a0-ffffffff815d531f: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160d740)
Location: fs/ext4/namei.c:1830
Inline: False
```
**Symbols:**

```
ffffffff8160d740-ffffffff8160d9bf: ext4_lookup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049e218)
Location: fs/ext4/namei.c:1676
Inline: True
```
**Symbols:**

```
ffff80001049e218-ffff80001049e49c: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (c065ff10)
Location: fs/ext4/namei.c:1676
Inline: True
```
**Symbols:**

```
c065ff10-c0660234: ext4_lookup.part.0 (STB_LOCAL)
c0660234-c0660264: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c9c00)
Location: fs/ext4/namei.c:1676
Inline: True
```
**Symbols:**

```
c0000000005c9c00-c0000000005c9f30: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe000320d28)
Location: fs/ext4/namei.c:1676
Inline: True
```
**Symbols:**

```
ffffffe000320d28-ffffffe000320f22: ext4_lookup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bed10)
Location: fs/ext4/namei.c:1676
Inline: True
```
**Symbols:**

```
ffffffff813bed10-ffffffff813bef72: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813af7a0)
Location: fs/ext4/namei.c:1676
Inline: True
```
**Symbols:**

```
ffffffff813af7a0-ffffffff813afa02: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bc2f0)
Location: fs/ext4/namei.c:1676
Inline: True
```
**Symbols:**

```
ffffffff813bc2f0-ffffffff813bc504: ext4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *ext4_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d12a0)
Location: fs/ext4/namei.c:1676
Inline: True
```
**Symbols:**

```
ffffffff813d12a0-ffffffff813d1502: ext4_lookup (STB_LOCAL)
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
