# Function: <code>hugetlbfs_size_to_hpages</code>

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
In fs/hugetlbfs/inode.c (ffffffff812f4327)
Location: fs/hugetlbfs/inode.c:1009
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81327570)
Location: fs/hugetlbfs/inode.c:1016
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8133d2dd)
Location: fs/hugetlbfs/inode.c:1014
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813522cd)
Location: fs/hugetlbfs/inode.c:1073
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81376b50)
Location: fs/hugetlbfs/inode.c:1073
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813a53b5)
Location: fs/hugetlbfs/inode.c:1094
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813be1eb)
Location: fs/hugetlbfs/inode.c:1104
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813e8c68)
Location: fs/hugetlbfs/inode.c:1127
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81402d08)
Location: fs/hugetlbfs/inode.c:1127
Inline: True
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
In fs/hugetlbfs/inode.c (ffffffff81450c4f)
Location: fs/hugetlbfs/inode.c:1207
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8146d15f)
Location: fs/hugetlbfs/inode.c:1208
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8147285a)
Location: fs/hugetlbfs/inode.c:1202
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int hugetlbfs_size_to_hpages(struct hstate *h, long long unsigned int size_opt, enum hugetlbfs_size_type val_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1203
Inline: False
```
**Symbols:**

```
ffffffff814c85f0-ffffffff814c865c: hugetlbfs_size_to_hpages (STB_LOCAL)
ffffffff81ccf3ba-ffffffff81ccf405: hugetlbfs_size_to_hpages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int hugetlbfs_size_to_hpages(struct hstate *h, long long unsigned int size_opt, enum hugetlbfs_size_type val_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1254
Inline: False
```
**Symbols:**

```
ffffffff81553be0-ffffffff81553c73: hugetlbfs_size_to_hpages (STB_LOCAL)
ffffffff81e8243b-ffffffff81e82498: hugetlbfs_size_to_hpages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int hugetlbfs_size_to_hpages(struct hstate *h, long long unsigned int size_opt, enum hugetlbfs_size_type val_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1330
Inline: False
```
**Symbols:**

```
ffffffff815f54a0-ffffffff815f5533: hugetlbfs_size_to_hpages (STB_LOCAL)
ffffffff820717c6-ffffffff82071823: hugetlbfs_size_to_hpages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int hugetlbfs_size_to_hpages(struct hstate *h, long long unsigned int size_opt, enum hugetlbfs_size_type val_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1325
Inline: False
```
**Symbols:**

```
ffffffff8162d520-ffffffff8162d5b6: hugetlbfs_size_to_hpages (STB_LOCAL)
ffffffff820f1451-ffffffff820f148d: hugetlbfs_size_to_hpages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int hugetlbfs_size_to_hpages(struct hstate *h, long long unsigned int size_opt, enum hugetlbfs_size_type val_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1345
Inline: False
```
**Symbols:**

```
ffffffff81666a00-ffffffff81666a96: hugetlbfs_size_to_hpages (STB_LOCAL)
ffffffff821ce6f3-ffffffff821ce72f: hugetlbfs_size_to_hpages.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffff8000104e1594)
Location: fs/hugetlbfs/inode.c:1127
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (c00000000061e314)
Location: fs/hugetlbfs/inode.c:1127
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffe000355600)
Location: fs/hugetlbfs/inode.c:1127
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813fb2e8)
Location: fs/hugetlbfs/inode.c:1127
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813ebd68)
Location: fs/hugetlbfs/inode.c:1127
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813f8668)
Location: fs/hugetlbfs/inode.c:1127
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8140e468)
Location: fs/hugetlbfs/inode.c:1127
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
