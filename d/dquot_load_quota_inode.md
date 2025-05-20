# Function: <code>dquot_load_quota_inode</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dquot_load_quota_inode(struct inode *inode, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b3330)
Location: fs/quota/dquot.c:2414
Inline: True
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
```
**Symbols:**

```
ffffffff813b3330-ffffffff813b3432: dquot_load_quota_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dquot_load_quota_inode(struct inode *inode, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c4920)
Location: fs/quota/dquot.c:2415
Inline: True
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
```
**Symbols:**

```
ffffffff813c4920-ffffffff813c4a22: dquot_load_quota_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dquot_load_quota_inode(struct inode *inode, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813cb6d0)
Location: fs/quota/dquot.c:2413
Inline: True
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/ext4/super.c:ext4_enable_quotas
```
**Symbols:**

```
ffffffff813cb6d0-ffffffff813cb7d2: dquot_load_quota_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dquot_load_quota_inode(struct inode *inode, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff8141c81e)
Location: fs/quota/dquot.c:2418
Inline: True
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/ext4/super.c:ext4_enable_quotas
```
**Symbols:**

```
ffffffff81cc7e7f-ffffffff81cc7e9e: dquot_load_quota_inode.cold (STB_LOCAL)
ffffffff8141c780-ffffffff8141c8d7: dquot_load_quota_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dquot_load_quota_inode(struct inode *inode, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff81492126)
Location: fs/quota/dquot.c:2428
Inline: True
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/ext4/super.c:ext4_enable_quotas
```
**Symbols:**

```
ffffffff81e7aa3f-ffffffff81e7aa58: dquot_load_quota_inode.cold (STB_LOCAL)
ffffffff81492090-ffffffff814921fb: dquot_load_quota_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dquot_load_quota_inode(struct inode *inode, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff81525db7)
Location: fs/quota/dquot.c:2437
Inline: True
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/ext4/super.c:ext4_enable_quotas
```
**Symbols:**

```
ffffffff8206b953-ffffffff8206b96c: dquot_load_quota_inode.cold (STB_LOCAL)
ffffffff81525d10-ffffffff81525e96: dquot_load_quota_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dquot_load_quota_inode(struct inode *inode, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff8155e287)
Location: fs/quota/dquot.c:2496
Inline: True
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/ext4/super.c:ext4_enable_quotas
```
**Symbols:**

```
ffffffff820eb807-ffffffff820eb820: dquot_load_quota_inode.cold (STB_LOCAL)
ffffffff8155e1e0-ffffffff8155e366: dquot_load_quota_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dquot_load_quota_inode(struct inode *inode, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff81594951)
Location: fs/quota/dquot.c:2463
Inline: True
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/ext4/super.c:ext4_enable_quotas
```
**Symbols:**

```
ffffffff821c8a31-ffffffff821c8a4a: dquot_load_quota_inode.cold (STB_LOCAL)
ffffffff815948a0-ffffffff81594a3a: dquot_load_quota_inode (STB_GLOBAL)
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
