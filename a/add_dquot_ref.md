# Function: <code>add_dquot_ref</code>

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
In fs/quota/dquot.c (ffffffff81272388)
Location: fs/quota/dquot.c:930
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffff8129eb38)
Location: fs/quota/dquot.c:939
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffff812b448b)
Location: fs/quota/dquot.c:936
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffff812c22a3)
Location: fs/quota/dquot.c:937
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffff812e60d0)
Location: fs/quota/dquot.c:944
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffff81313f4a)
Location: fs/quota/dquot.c:941
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffff8132aeda)
Location: fs/quota/dquot.c:941
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffff81352ae8)
Location: fs/quota/dquot.c:947
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffff8136ae68)
Location: fs/quota/dquot.c:948
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_dquot_ref(struct super_block *sb, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b2e50)
Location: fs/quota/dquot.c:946
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
```
**Symbols:**

```
ffffffff813b2e50-ffffffff813b2fc7: add_dquot_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_dquot_ref(struct super_block *sb, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c4440)
Location: fs/quota/dquot.c:947
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
```
**Symbols:**

```
ffffffff813c4440-ffffffff813c45b7: add_dquot_ref (STB_LOCAL)
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
In fs/quota/dquot.c (ffffffff813cb39b)
Location: fs/quota/dquot.c:945
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
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
In fs/quota/dquot.c (ffffffff8141c303)
Location: fs/quota/dquot.c:950
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
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
In fs/quota/dquot.c (ffffffff81491c84)
Location: fs/quota/dquot.c:960
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
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
In fs/quota/dquot.c (ffffffff815258e4)
Location: fs/quota/dquot.c:960
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
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
In fs/quota/dquot.c (ffffffff8155dd7b)
Location: fs/quota/dquot.c:1018
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
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
In fs/quota/dquot.c (ffffffff8159445c)
Location: fs/quota/dquot.c:1024
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
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
In fs/quota/dquot.c (ffff800010433dd4)
Location: fs/quota/dquot.c:948
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (c05fa758)
Location: fs/quota/dquot.c:948
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (c000000000543e30)
Location: fs/quota/dquot.c:948
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffe0002cf6fe)
Location: fs/quota/dquot.c:948
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffff81363448)
Location: fs/quota/dquot.c:948
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffff813540e8)
Location: fs/quota/dquot.c:948
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffff81360f18)
Location: fs/quota/dquot.c:948
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
In fs/quota/dquot.c (ffffffff81372e98)
Location: fs/quota/dquot.c:948
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
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
