# Function: <code>ecryptfs_write_inode_size_to_xattr</code>

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
In fs/ecryptfs/mmap.c (ffffffff81304545)
Location: fs/ecryptfs/mmap.c:417
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
In fs/ecryptfs/mmap.c (ffffffff81338617)
Location: fs/ecryptfs/mmap.c:416
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
In fs/ecryptfs/mmap.c (ffffffff8134e3d7)
Location: fs/ecryptfs/mmap.c:417
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
In fs/ecryptfs/mmap.c (ffffffff81362f57)
Location: fs/ecryptfs/mmap.c:417
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
In fs/ecryptfs/mmap.c (ffffffff81387bf7)
Location: fs/ecryptfs/mmap.c:417
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
In fs/ecryptfs/mmap.c (ffffffff813b685b)
Location: fs/ecryptfs/mmap.c:417
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
In fs/ecryptfs/mmap.c (ffffffff813cfdab)
Location: fs/ecryptfs/mmap.c:417
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
In fs/ecryptfs/mmap.c (ffffffff813fa99b)
Location: fs/ecryptfs/mmap.c:403
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
In fs/ecryptfs/mmap.c (ffffffff8141486b)
Location: fs/ecryptfs/mmap.c:403
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_inode_size_to_xattr(struct inode *ecryptfs_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:403
Inline: False
```
**Symbols:**

```
ffffffff81462420-ffffffff81462502: ecryptfs_write_inode_size_to_xattr (STB_LOCAL)
ffffffff81462e8d-ffffffff81462eb8: ecryptfs_write_inode_size_to_xattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_inode_size_to_xattr(struct inode *ecryptfs_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:403
Inline: False
```
**Symbols:**

```
ffffffff8147dd70-ffffffff8147de52: ecryptfs_write_inode_size_to_xattr (STB_LOCAL)
ffffffff81bee389-ffffffff81bee3b4: ecryptfs_write_inode_size_to_xattr.cold (STB_LOCAL)
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
In fs/ecryptfs/mmap.c (ffffffff8148416b)
Location: fs/ecryptfs/mmap.c:404
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff814db7eb)
Location: fs/ecryptfs/mmap.c:404
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff815693bb)
Location: fs/ecryptfs/mmap.c:405
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff8160cf5b)
Location: fs/ecryptfs/mmap.c:405
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81644e0b)
Location: fs/ecryptfs/mmap.c:405
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff8167e31b)
Location: fs/ecryptfs/mmap.c:404
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
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
In fs/ecryptfs/mmap.c (ffff8000104f5fa4)
Location: fs/ecryptfs/mmap.c:403
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (c06b382c)
Location: fs/ecryptfs/mmap.c:403
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (c000000000636ddc)
Location: fs/ecryptfs/mmap.c:403
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
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
In fs/ecryptfs/mmap.c (ffffffe000364d80)
Location: fs/ecryptfs/mmap.c:403
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
In fs/ecryptfs/mmap.c (ffffffff8140ce4b)
Location: fs/ecryptfs/mmap.c:403
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
In fs/ecryptfs/mmap.c (ffffffff813fd8cb)
Location: fs/ecryptfs/mmap.c:403
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
In fs/ecryptfs/mmap.c (ffffffff8140a1cb)
Location: fs/ecryptfs/mmap.c:403
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
In fs/ecryptfs/mmap.c (ffffffff8141febb)
Location: fs/ecryptfs/mmap.c:403
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
