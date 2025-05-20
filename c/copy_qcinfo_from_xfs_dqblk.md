# Function: <code>copy_qcinfo_from_xfs_dqblk</code>

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
In fs/quota/quota.c (ffffffff812752af)
Location: fs/quota/quota.c:520
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
In fs/quota/quota.c (ffffffff812a1826)
Location: fs/quota/quota.c:548
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
In fs/quota/quota.c (ffffffff812b71f6)
Location: fs/quota/quota.c:550
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
In fs/quota/quota.c (ffffffff812c4788)
Location: fs/quota/quota.c:550
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
In fs/quota/quota.c (ffffffff812e861e)
Location: fs/quota/quota.c:551
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
In fs/quota/quota.c (ffffffff8131518e)
Location: fs/quota/quota.c:552
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
In fs/quota/quota.c (ffffffff8132c11e)
Location: fs/quota/quota.c:550
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
In fs/quota/quota.c (ffffffff81353d99)
Location: fs/quota/quota.c:536
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
In fs/quota/quota.c (ffffffff8136c109)
Location: fs/quota/quota.c:536
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
void copy_qcinfo_from_xfs_dqblk(struct qc_info *dst, struct fs_disk_quota *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813b3940)
Location: fs/quota/quota.c:534
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_setxquota
```
**Symbols:**

```
ffffffff813b3940-ffffffff813b39e6: copy_qcinfo_from_xfs_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_qcinfo_from_xfs_dqblk(struct qc_info *dst, struct fs_disk_quota *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813c5260)
Location: fs/quota/quota.c:597
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_setxquota
```
**Symbols:**

```
ffffffff813c5260-ffffffff813c5306: copy_qcinfo_from_xfs_dqblk (STB_LOCAL)
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
In fs/quota/quota.c (ffffffff813cc0b1)
Location: fs/quota/quota.c:599
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff8141d1be)
Location: fs/quota/quota.c:599
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff81494c27)
Location: fs/quota/quota.c:600
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff81528ad7)
Location: fs/quota/quota.c:600
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff81560df9)
Location: fs/quota/quota.c:600
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffffffff815974e9)
Location: fs/quota/quota.c:600
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
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
In fs/quota/quota.c (ffff800010435cdc)
Location: fs/quota/quota.c:536
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
In fs/quota/quota.c (c05fe14c)
Location: fs/quota/quota.c:536
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
In fs/quota/quota.c (c000000000547fc0)
Location: fs/quota/quota.c:536
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
In fs/quota/quota.c (ffffffe0002d06dc)
Location: fs/quota/quota.c:536
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
In fs/quota/quota.c (ffffffff813646e9)
Location: fs/quota/quota.c:536
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
In fs/quota/quota.c (ffffffff81355389)
Location: fs/quota/quota.c:536
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
In fs/quota/quota.c (ffffffff813621b9)
Location: fs/quota/quota.c:536
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
In fs/quota/quota.c (ffffffff81375869)
Location: fs/quota/quota.c:536
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
</ul>
