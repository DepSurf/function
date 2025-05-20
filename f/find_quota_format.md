# Function: <code>find_quota_format</code>

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
In fs/quota/dquot.c (ffffffff81272128)
Location: fs/quota/dquot.c:185
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
In fs/quota/dquot.c (ffffffff8129e8e8)
Location: fs/quota/dquot.c:185
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
In fs/quota/dquot.c (ffffffff812b4248)
Location: fs/quota/dquot.c:184
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
In fs/quota/dquot.c (ffffffff812c2035)
Location: fs/quota/dquot.c:185
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
In fs/quota/dquot.c (ffffffff812e5e65)
Location: fs/quota/dquot.c:188
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
In fs/quota/dquot.c (ffffffff81313cc5)
Location: fs/quota/dquot.c:188
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
In fs/quota/dquot.c (ffffffff8132ac55)
Location: fs/quota/dquot.c:188
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
In fs/quota/dquot.c (ffffffff81352855)
Location: fs/quota/dquot.c:188
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
In fs/quota/dquot.c (ffffffff8136abd5)
Location: fs/quota/dquot.c:188
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
struct quota_format_type *find_quota_format(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813af680)
Location: fs/quota/dquot.c:188
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
```
**Symbols:**

```
ffffffff813af680-ffffffff813af779: find_quota_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct quota_format_type *find_quota_format(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c0c70)
Location: fs/quota/dquot.c:189
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
```
**Symbols:**

```
ffffffff813c0c70-ffffffff813c0d72: find_quota_format (STB_LOCAL)
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
In fs/quota/dquot.c (ffffffff813cb10e)
Location: fs/quota/dquot.c:189
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
In fs/quota/dquot.c (ffffffff8141c020)
Location: fs/quota/dquot.c:189
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
In fs/quota/dquot.c (ffffffff81491972)
Location: fs/quota/dquot.c:190
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
In fs/quota/dquot.c (ffffffff815255d2)
Location: fs/quota/dquot.c:190
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
In fs/quota/dquot.c (ffffffff8155da52)
Location: fs/quota/dquot.c:190
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
In fs/quota/dquot.c (ffffffff81594132)
Location: fs/quota/dquot.c:190
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
In fs/quota/dquot.c (ffff800010433b14)
Location: fs/quota/dquot.c:188
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
In fs/quota/dquot.c (c05fa49c)
Location: fs/quota/dquot.c:188
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
In fs/quota/dquot.c (c000000000543a70)
Location: fs/quota/dquot.c:188
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
In fs/quota/dquot.c (ffffffe0002cf498)
Location: fs/quota/dquot.c:188
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
In fs/quota/dquot.c (ffffffff813631b5)
Location: fs/quota/dquot.c:188
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
In fs/quota/dquot.c (ffffffff81353e55)
Location: fs/quota/dquot.c:188
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
In fs/quota/dquot.c (ffffffff81360c85)
Location: fs/quota/dquot.c:188
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
In fs/quota/dquot.c (ffffffff81372c05)
Location: fs/quota/dquot.c:188
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
