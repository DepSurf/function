# Function: <code>dquot_load_quota_sb</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int dquot_load_quota_sb(struct super_block *sb, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b2fd0)
Location: fs/quota/dquot.c:2332
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_resume
```
**Symbols:**

```
ffffffff813b2fd0-ffffffff813b320c: dquot_load_quota_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dquot_load_quota_sb(struct super_block *sb, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c45c0)
Location: fs/quota/dquot.c:2333
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_resume
```
**Symbols:**

```
ffffffff813c45c0-ffffffff813c47fc: dquot_load_quota_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dquot_load_quota_sb(struct super_block *sb, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813cb100)
Location: fs/quota/dquot.c:2331
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_resume
```
**Symbols:**

```
ffffffff813cb100-ffffffff813cb5b4: dquot_load_quota_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dquot_load_quota_sb(struct super_block *sb, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:2336
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_resume
```
**Symbols:**

```
ffffffff81cc7e4a-ffffffff81cc7e7f: dquot_load_quota_sb.cold (STB_LOCAL)
ffffffff8141c010-ffffffff8141c65e: dquot_load_quota_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dquot_load_quota_sb(struct super_block *sb, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:2346
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_resume
```
**Symbols:**

```
ffffffff81e7aa0f-ffffffff81e7aa3f: dquot_load_quota_sb.cold (STB_LOCAL)
ffffffff81491960-ffffffff81491f5d: dquot_load_quota_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dquot_load_quota_sb(struct super_block *sb, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:2355
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_resume
```
**Symbols:**

```
ffffffff8206b923-ffffffff8206b953: dquot_load_quota_sb.cold (STB_LOCAL)
ffffffff815255c0-ffffffff81525bbd: dquot_load_quota_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dquot_load_quota_sb(struct super_block *sb, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:2413
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_resume
```
**Symbols:**

```
ffffffff820eb7d7-ffffffff820eb807: dquot_load_quota_sb.cold (STB_LOCAL)
ffffffff8155da40-ffffffff8155e08a: dquot_load_quota_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dquot_load_quota_sb(struct super_block *sb, int type, int format_id, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:2381
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - fs/quota/dquot.c:dquot_resume
```
**Symbols:**

```
ffffffff821c8a01-ffffffff821c8a31: dquot_load_quota_sb.cold (STB_LOCAL)
ffffffff81594120-ffffffff8159474c: dquot_load_quota_sb (STB_GLOBAL)
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
