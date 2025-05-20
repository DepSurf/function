# Function: <code>copy_to_xfs_dqblk</code>

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
In fs/quota/quota.c (ffffffff812759d7)
Location: fs/quota/quota.c:577
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getxquota
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812a11f0)
Location: fs/quota/quota.c:605
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff812a11f0-ffffffff812a12e7: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812b6ba0)
Location: fs/quota/quota.c:607
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff812b6ba0-ffffffff812b6c97: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812c3e20)
Location: fs/quota/quota.c:607
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff812c3e20-ffffffff812c3f17: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812e7c90)
Location: fs/quota/quota.c:608
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff812e7c90-ffffffff812e7d87: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81314870)
Location: fs/quota/quota.c:609
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff81314870-ffffffff81314967: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8132b910)
Location: fs/quota/quota.c:607
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff8132b910-ffffffff8132ba07: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81353870)
Location: fs/quota/quota.c:593
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff81353870-ffffffff81353985: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8136bbe0)
Location: fs/quota/quota.c:593
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff8136bbe0-ffffffff8136bcf5: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813b39f0)
Location: fs/quota/quota.c:591
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff813b39f0-ffffffff813b3ae7: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813c5310)
Location: fs/quota/quota.c:667
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff813c5310-ffffffff813c5488: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813cbe30)
Location: fs/quota/quota.c:669
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff813cbe30-ffffffff813cbf9f: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8141cf50)
Location: fs/quota/quota.c:669
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff8141cf50-ffffffff8141d0bf: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81494950)
Location: fs/quota/quota.c:670
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff81494950-ffffffff81494ad6: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff815287f0)
Location: fs/quota/quota.c:670
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff815287f0-ffffffff8152897f: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81560f50)
Location: fs/quota/quota.c:670
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff81560f50-ffffffff815610df: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81597640)
Location: fs/quota/quota.c:670
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff81597640-ffffffff815977cf: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffff800010435660)
Location: fs/quota/quota.c:593
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffff800010435660-ffff800010435784: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (c05fd298)
Location: fs/quota/quota.c:593
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
c05fd298-c05fd41c: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (c000000000547930)
Location: fs/quota/quota.c:593
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
c000000000547930-c000000000547a7c: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffe0002d0262)
Location: fs/quota/quota.c:593
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffe0002d0262-ffffffe0002d0370: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813641c0)
Location: fs/quota/quota.c:593
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff813641c0-ffffffff813642d5: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81354e60)
Location: fs/quota/quota.c:593
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff81354e60-ffffffff81354f75: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81361c90)
Location: fs/quota/quota.c:593
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff81361c90-ffffffff81361da5: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota *dst, struct qc_dqblk *src, int type, qid_t id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81375340)
Location: fs/quota/quota.c:593
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
```
**Symbols:**

```
ffffffff81375340-ffffffff81375455: copy_to_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
