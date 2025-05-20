# Function: <code>copy_from_xfs_dqblk</code>

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
In fs/quota/quota.c (ffffffff81275382)
Location: fs/quota/quota.c:470
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff812a18f7)
Location: fs/quota/quota.c:498
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff812b72c7)
Location: fs/quota/quota.c:500
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff812c45a0)
Location: fs/quota/quota.c:500
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff812e8430)
Location: fs/quota/quota.c:501
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff81314fa0)
Location: fs/quota/quota.c:502
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff8132bf30)
Location: fs/quota/quota.c:500
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff81353ba6)
Location: fs/quota/quota.c:486
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff8136bf16)
Location: fs/quota/quota.c:486
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_from_xfs_dqblk(struct qc_dqblk *dst, struct fs_disk_quota *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813b3640)
Location: fs/quota/quota.c:484
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_setxquota
```
**Symbols:**

```
ffffffff813b3640-ffffffff813b37a5: copy_from_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_from_xfs_dqblk(struct qc_dqblk *dst, struct fs_disk_quota *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813c4bf0)
Location: fs/quota/quota.c:544
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_setxquota
```
**Symbols:**

```
ffffffff813c4bf0-ffffffff813c4dc1: copy_from_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_from_xfs_dqblk(struct qc_dqblk *dst, struct fs_disk_quota *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813cb900)
Location: fs/quota/quota.c:546
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_setxquota
```
**Symbols:**

```
ffffffff813cb900-ffffffff813cbae3: copy_from_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void copy_from_xfs_dqblk(struct qc_dqblk *dst, struct fs_disk_quota *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8141c9c0)
Location: fs/quota/quota.c:546
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_setxquota
```
**Symbols:**

```
ffffffff8141c9c0-ffffffff8141cba3: copy_from_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void copy_from_xfs_dqblk(struct qc_dqblk *dst, struct fs_disk_quota *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff814943a0)
Location: fs/quota/quota.c:547
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_setxquota
```
**Symbols:**

```
ffffffff814943a0-ffffffff81494591: copy_from_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void copy_from_xfs_dqblk(struct qc_dqblk *dst, struct fs_disk_quota *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81528200)
Location: fs/quota/quota.c:547
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_setxquota
```
**Symbols:**

```
ffffffff81528200-ffffffff815283f1: copy_from_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void copy_from_xfs_dqblk(struct qc_dqblk *dst, struct fs_disk_quota *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81560610)
Location: fs/quota/quota.c:547
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_setxquota
```
**Symbols:**

```
ffffffff81560610-ffffffff81560801: copy_from_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void copy_from_xfs_dqblk(struct qc_dqblk *dst, struct fs_disk_quota *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81596d00)
Location: fs/quota/quota.c:547
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_setxquota
```
**Symbols:**

```
ffffffff81596d00-ffffffff81596ef1: copy_from_xfs_dqblk (STB_LOCAL)
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
In fs/quota/quota.c (ffff800010435b10)
Location: fs/quota/quota.c:486
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (c05fe260)
Location: fs/quota/quota.c:486
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (c000000000547d4c)
Location: fs/quota/quota.c:486
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffe0002d0504)
Location: fs/quota/quota.c:486
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff813644f6)
Location: fs/quota/quota.c:486
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff81355196)
Location: fs/quota/quota.c:486
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff81361fc6)
Location: fs/quota/quota.c:486
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff81375676)
Location: fs/quota/quota.c:486
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
