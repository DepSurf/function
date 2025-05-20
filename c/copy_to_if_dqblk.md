# Function: <code>copy_to_if_dqblk</code>

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
In fs/quota/quota.c (ffffffff8127562d)
Location: fs/quota/quota.c:189
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getquota
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
In fs/quota/quota.c (ffffffff812a208b)
Location: fs/quota/quota.c:189
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
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
In fs/quota/quota.c (ffffffff812b7a5b)
Location: fs/quota/quota.c:185
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812c3da0)
Location: fs/quota/quota.c:185
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff812c3da0-ffffffff812c3e12: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff812e7c10)
Location: fs/quota/quota.c:186
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff812e7c10-ffffffff812e7c82: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813147f0)
Location: fs/quota/quota.c:187
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff813147f0-ffffffff81314862: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8132b890)
Location: fs/quota/quota.c:185
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff8132b890-ffffffff8132b902: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813534d0)
Location: fs/quota/quota.c:185
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff813534d0-ffffffff81353561: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8136b840)
Location: fs/quota/quota.c:185
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff8136b840-ffffffff8136b8d1: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813b38c0)
Location: fs/quota/quota.c:183
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff813b38c0-ffffffff813b3932: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813c51e0)
Location: fs/quota/quota.c:185
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff813c51e0-ffffffff813c5252: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813cbdb0)
Location: fs/quota/quota.c:186
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff813cbdb0-ffffffff813cbe22: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8141ced0)
Location: fs/quota/quota.c:186
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff8141ced0-ffffffff8141cf42: copy_to_if_dqblk (STB_LOCAL)
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
In fs/quota/quota.c (ffffffff8149599d)
Location: fs/quota/quota.c:187
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
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
In fs/quota/quota.c (ffffffff815298cd)
Location: fs/quota/quota.c:187
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81560c20)
Location: fs/quota/quota.c:187
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff81560c20-ffffffff81560ca0: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81597310)
Location: fs/quota/quota.c:187
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff81597310-ffffffff81597390: copy_to_if_dqblk (STB_LOCAL)
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
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffff8000104352d0)
Location: fs/quota/quota.c:185
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffff8000104352d0-ffff800010435364: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (c05fcf20)
Location: fs/quota/quota.c:185
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
c05fcf20-c05fcfd0: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (c000000000547530)
Location: fs/quota/quota.c:185
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
c000000000547530-c0000000005475dc: copy_to_if_dqblk (STB_LOCAL)
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
In fs/quota/quota.c (ffffffe0002d0ca0)
Location: fs/quota/quota.c:185
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
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
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81363e20)
Location: fs/quota/quota.c:185
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff81363e20-ffffffff81363eb1: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81354ac0)
Location: fs/quota/quota.c:185
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff81354ac0-ffffffff81354b51: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813618f0)
Location: fs/quota/quota.c:185
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff813618f0-ffffffff81361981: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk *dst, struct qc_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81374fa0)
Location: fs/quota/quota.c:185
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff81374fa0-ffffffff81375031: copy_to_if_dqblk (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
