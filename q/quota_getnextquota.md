# Function: <code>quota_getnextquota</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812a1fd0)
Location: fs/quota/quota.c:229
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812a1fd0-ffffffff812a21ad: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812b79a0)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812b79a0-ffffffff812b7b7d: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812c4d50)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812c4d50-ffffffff812c4eb6: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812e8bf0)
Location: fs/quota/quota.c:226
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812e8bf0-ffffffff812e8d5c: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813156e0)
Location: fs/quota/quota.c:227
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff813156e0-ffffffff81315849: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8132c6f0)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff8132c6f0-ffffffff8132c859: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81354380)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81354380-ffffffff813544e9: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8136c6f0)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff8136c6f0-ffffffff8136c859: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813b4590)
Location: fs/quota/quota.c:223
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff813b4590-ffffffff813b46f7: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813c5cc0)
Location: fs/quota/quota.c:235
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff813c5cc0-ffffffff813c5e27: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813cc910)
Location: fs/quota/quota.c:236
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff813cc910-ffffffff813cca77: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8141dbd0)
Location: fs/quota/quota.c:236
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff8141dbd0-ffffffff8141dd34: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff814958b0)
Location: fs/quota/quota.c:237
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff814958b0-ffffffff81495ac7: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff815297e0)
Location: fs/quota/quota.c:237
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff815297e0-ffffffff815299f7: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81561af0)
Location: fs/quota/quota.c:237
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81561af0-ffffffff81561c89: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff815981e0)
Location: fs/quota/quota.c:237
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff815981e0-ffffffff81598379: quota_getnextquota (STB_LOCAL)
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
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffff800010436568)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffff800010436568-ffff800010436708: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (c05fd8b8)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
c05fd8b8-c05fda78: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (c000000000548730)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
c000000000548730-c000000000548900: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffe0002d0bf8)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffe0002d0bf8-ffffffe0002d0d66: quota_getnextquota (STB_LOCAL)
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
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81364cd0)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81364cd0-ffffffff81364e39: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81355970)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81355970-ffffffff81355ad9: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813627a0)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff813627a0-ffffffff81362909: quota_getnextquota (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int quota_getnextquota(struct super_block *sb, int type, qid_t id, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81375e50)
Location: fs/quota/quota.c:225
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81375e50-ffffffff81375fb9: quota_getnextquota (STB_LOCAL)
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
