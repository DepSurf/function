# Function: <code>sel_avc_get_stat_idx</code>

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
In security/selinux/selinuxfs.c (ffffffff81349f16)
Location: security/selinux/selinuxfs.c:1363
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
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
In security/selinux/selinuxfs.c (ffffffff8137fcc5)
Location: security/selinux/selinuxfs.c:1409
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
In security/selinux/selinuxfs.c (ffffffff81396755)
Location: security/selinux/selinuxfs.c:1411
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
In security/selinux/selinuxfs.c (ffffffff813acb15)
Location: security/selinux/selinuxfs.c:1419
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
In security/selinux/selinuxfs.c (ffffffff813d2bc5)
Location: security/selinux/selinuxfs.c:1419
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
In security/selinux/selinuxfs.c (ffffffff81402e05)
Location: security/selinux/selinuxfs.c:1502
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
In security/selinux/selinuxfs.c (ffffffff8141e915)
Location: security/selinux/selinuxfs.c:1502
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct avc_cache_stats *sel_avc_get_stat_idx(loff_t *idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8144c550)
Location: security/selinux/selinuxfs.c:1501
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
**Symbols:**

```
ffffffff8144c550-ffffffff8144c5a2: sel_avc_get_stat_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct avc_cache_stats *sel_avc_get_stat_idx(loff_t *idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81466340)
Location: security/selinux/selinuxfs.c:1501
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
**Symbols:**

```
ffffffff81466340-ffffffff81466392: sel_avc_get_stat_idx (STB_LOCAL)
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
In security/selinux/selinuxfs.c (ffffffff814bb655)
Location: security/selinux/selinuxfs.c:1537
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
In security/selinux/selinuxfs.c (ffffffff814d9035)
Location: security/selinux/selinuxfs.c:1608
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
In security/selinux/selinuxfs.c (ffffffff814df9b5)
Location: security/selinux/selinuxfs.c:1611
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
In security/selinux/selinuxfs.c (ffffffff815388e5)
Location: security/selinux/selinuxfs.c:1611
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
In security/selinux/selinuxfs.c (ffffffff815cfe65)
Location: security/selinux/selinuxfs.c:1615
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
In security/selinux/selinuxfs.c (ffffffff8167db45)
Location: security/selinux/selinuxfs.c:1615
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
In security/selinux/selinuxfs.c (ffffffff816b5d45)
Location: security/selinux/selinuxfs.c:1541
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
In security/selinux/selinuxfs.c (ffffffff816f28d5)
Location: security/selinux/selinuxfs.c:1510
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
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
struct avc_cache_stats *sel_avc_get_stat_idx(loff_t *idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffff800010554488)
Location: security/selinux/selinuxfs.c:1501
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
**Symbols:**

```
ffff800010554488-ffff800010554548: sel_avc_get_stat_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct avc_cache_stats *sel_avc_get_stat_idx(loff_t *idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c070956c)
Location: security/selinux/selinuxfs.c:1501
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
**Symbols:**

```
c070956c-c070962c: sel_avc_get_stat_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct avc_cache_stats *sel_avc_get_stat_idx(loff_t *idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c0000000006b1240)
Location: security/selinux/selinuxfs.c:1501
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
**Symbols:**

```
c0000000006b1240-c0000000006b1368: sel_avc_get_stat_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct avc_cache_stats *sel_avc_get_stat_idx(loff_t *idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffe0003ac9ae)
Location: security/selinux/selinuxfs.c:1501
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
**Symbols:**

```
ffffffe0003ac9ae-ffffffe0003aca46: sel_avc_get_stat_idx (STB_LOCAL)
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
struct avc_cache_stats *sel_avc_get_stat_idx(loff_t *idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8145e920)
Location: security/selinux/selinuxfs.c:1501
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
**Symbols:**

```
ffffffff8145e920-ffffffff8145e972: sel_avc_get_stat_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct avc_cache_stats *sel_avc_get_stat_idx(loff_t *idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8144f350)
Location: security/selinux/selinuxfs.c:1501
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
**Symbols:**

```
ffffffff8144f350-ffffffff8144f3a2: sel_avc_get_stat_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct avc_cache_stats *sel_avc_get_stat_idx(loff_t *idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8145a9c0)
Location: security/selinux/selinuxfs.c:1501
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
**Symbols:**

```
ffffffff8145a9c0-ffffffff8145aa12: sel_avc_get_stat_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct avc_cache_stats *sel_avc_get_stat_idx(loff_t *idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81472160)
Location: security/selinux/selinuxfs.c:1501
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
**Symbols:**

```
ffffffff81472160-ffffffff814721b2: sel_avc_get_stat_idx (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
