# Function: <code>quota_getxquota</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81275900)
Location: fs/quota/quota.c:606
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff81275900-ffffffff81275b4b: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812a1e80)
Location: fs/quota/quota.c:634
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812a1e80-ffffffff812a1fc1: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812b7850)
Location: fs/quota/quota.c:636
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812b7850-ffffffff812b7991: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812c4c00)
Location: fs/quota/quota.c:636
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812c4c00-ffffffff812c4d44: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812e8aa0)
Location: fs/quota/quota.c:637
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812e8aa0-ffffffff812e8bea: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81315420)
Location: fs/quota/quota.c:638
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff81315420-ffffffff8131556a: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8132c5a0)
Location: fs/quota/quota.c:636
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff8132c5a0-ffffffff8132c6ea: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81354220)
Location: fs/quota/quota.c:622
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81354220-ffffffff81354372: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8136c590)
Location: fs/quota/quota.c:622
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff8136c590-ffffffff8136c6e2: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813b4440)
Location: fs/quota/quota.c:620
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff813b4440-ffffffff813b4590: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813c5b70)
Location: fs/quota/quota.c:702
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff813c5b70-ffffffff813c5cc0: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813cc7c0)
Location: fs/quota/quota.c:704
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff813cc7c0-ffffffff813cc910: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8141da80)
Location: fs/quota/quota.c:704
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff8141da80-ffffffff8141dbcd: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81495580)
Location: fs/quota/quota.c:705
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81495580-ffffffff8149570a: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81529490)
Location: fs/quota/quota.c:705
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81529490-ffffffff8152961a: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81561950)
Location: fs/quota/quota.c:705
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81561950-ffffffff81561ade: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81598040)
Location: fs/quota/quota.c:705
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81598040-ffffffff815981ce: quota_getxquota (STB_LOCAL)
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
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffff8000104363d8)
Location: fs/quota/quota.c:622
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffff8000104363d8-ffff800010436568: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (c05fd70c)
Location: fs/quota/quota.c:622
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
c05fd70c-c05fd8b8: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (c000000000548570)
Location: fs/quota/quota.c:622
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
c000000000548570-c00000000054872c: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffe0002d0ae6)
Location: fs/quota/quota.c:622
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffe0002d0ae6-ffffffe0002d0bf8: quota_getxquota (STB_LOCAL)
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
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81364b70)
Location: fs/quota/quota.c:622
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81364b70-ffffffff81364cc2: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81355810)
Location: fs/quota/quota.c:622
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81355810-ffffffff81355962: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81362640)
Location: fs/quota/quota.c:622
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81362640-ffffffff81362792: quota_getxquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int quota_getxquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81375cf0)
Location: fs/quota/quota.c:622
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81375cf0-ffffffff81375e42: quota_getxquota (STB_LOCAL)
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
