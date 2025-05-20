# Function: <code>quota_send_warning</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (ffffffff812766c0)
Location: fs/quota/netlink.c:44
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff812766c0-ffffffff81276914: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (ffffffff812a2f00)
Location: fs/quota/netlink.c:42
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff812a2f00-ffffffff812a3160: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (ffffffff812b88e0)
Location: fs/quota/netlink.c:36
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff812b88e0-ffffffff812b8b40: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (ffffffff812c5cb0)
Location: fs/quota/netlink.c:36
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff812c5cb0-ffffffff812c5eed: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (ffffffff812e9b60)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff812e9b60-ffffffff812e9d9d: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff81316c6f-ffffffff81316ca7: quota_send_warning.cold.4 (STB_LOCAL)
ffffffff81316a60-ffffffff81316c6f: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff8132dc1f-ffffffff8132dc57: quota_send_warning.cold.4 (STB_LOCAL)
ffffffff8132da10-ffffffff8132dc1f: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff81355960-ffffffff81355998: quota_send_warning.cold (STB_LOCAL)
ffffffff81355750-ffffffff81355960: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff8136dca0-ffffffff8136dcd8: quota_send_warning.cold (STB_LOCAL)
ffffffff8136da90-ffffffff8136dca0: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff813b57d0-ffffffff813b5808: quota_send_warning.cold (STB_LOCAL)
ffffffff813b55c0-ffffffff813b57d0: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81bebc59-ffffffff81bebc91: quota_send_warning.cold (STB_LOCAL)
ffffffff813c6df0-ffffffff813c6fff: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81bddc68-ffffffff81bddca0: quota_send_warning.cold (STB_LOCAL)
ffffffff813cde80-ffffffff813ce08f: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81cc7ebd-ffffffff81cc7ef5: quota_send_warning.cold (STB_LOCAL)
ffffffff8141f1b0-ffffffff8141f3bf: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81e7aabd-ffffffff81e7aafa: quota_send_warning.cold (STB_LOCAL)
ffffffff81496ff0-ffffffff81497212: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (ffffffff8152b000)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff8152b000-ffffffff8152b265: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (ffffffff81563390)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81563390-ffffffff815635f5: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (ffffffff81599a80)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81599a80-ffffffff81599ceb: quota_send_warning (STB_GLOBAL)
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (ffff8000104374f0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffff8000104374f0-ffff800010437738: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (c05ff134)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
c05ff134-c05ff3bc: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (c0000000005498e0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
c0000000005498e0-c000000000549bb8: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (ffffffe0002d1772)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffe0002d1772-ffffffe0002d194a: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff81366280-ffffffff813662b8: quota_send_warning.cold (STB_LOCAL)
ffffffff81366070-ffffffff81366280: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff81356f20-ffffffff81356f58: quota_send_warning.cold (STB_LOCAL)
ffffffff81356d10-ffffffff81356f20: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff81363d50-ffffffff81363d88: quota_send_warning.cold (STB_LOCAL)
ffffffff81363b40-ffffffff81363d50: quota_send_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/netlink.c (0)
Location: fs/quota/netlink.c:37
Inline: False
Direct callers:
  - fs/quota/dquot.c:flush_warnings
```
**Symbols:**

```
ffffffff81377400-ffffffff81377438: quota_send_warning.cold (STB_LOCAL)
ffffffff813771f0-ffffffff81377400: quota_send_warning (STB_GLOBAL)
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
