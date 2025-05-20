# Function: <code>quota_setinfo</code>

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
In fs/quota/quota.c (ffffffff812761a8)
Location: fs/quota/quota.c:149
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
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
In fs/quota/quota.c (ffffffff812a29ce)
Location: fs/quota/quota.c:149
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
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
In fs/quota/quota.c (ffffffff812b83e9)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
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
In fs/quota/quota.c (ffffffff812c55d8)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
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
In fs/quota/quota.c (ffffffff812e947e)
Location: fs/quota/quota.c:146
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
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
In fs/quota/quota.c (ffffffff813161c8)
Location: fs/quota/quota.c:147
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
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
In fs/quota/quota.c (ffffffff8132d14b)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
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
In fs/quota/quota.c (ffffffff81354b7b)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffff8136ceeb)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int quota_setinfo(struct super_block *sb, int type, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813b3af0)
Location: fs/quota/quota.c:143
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff813b3af0-ffffffff813b3bf6: quota_setinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int quota_setinfo(struct super_block *sb, int type, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813c5490)
Location: fs/quota/quota.c:145
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff813c5490-ffffffff813c5596: quota_setinfo (STB_LOCAL)
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
In fs/quota/quota.c (ffffffff813cd41d)
Location: fs/quota/quota.c:146
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffff8141e6dd)
Location: fs/quota/quota.c:146
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffff8149641d)
Location: fs/quota/quota.c:147
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffff8152a37d)
Location: fs/quota/quota.c:147
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffff8156274b)
Location: fs/quota/quota.c:147
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffff81598e3b)
Location: fs/quota/quota.c:147
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffff800010436da4)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (c05fe86c)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (c000000000548fe4)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffe0002d10f2)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffff813654cb)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffff8135616b)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffff81362f9b)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffff8137664b)
Location: fs/quota/quota.c:145
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
