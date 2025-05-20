# Function: <code>quota_getxstate</code>

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
In fs/quota/quota.c (ffffffff81275e5e)
Location: fs/quota/quota.c:367
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
In fs/quota/quota.c (ffffffff812a295b)
Location: fs/quota/quota.c:395
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
In fs/quota/quota.c (ffffffff812b83b9)
Location: fs/quota/quota.c:394
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
In fs/quota/quota.c (ffffffff812c55ab)
Location: fs/quota/quota.c:394
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
In fs/quota/quota.c (ffffffff812e9451)
Location: fs/quota/quota.c:395
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
In fs/quota/quota.c (ffffffff813160d6)
Location: fs/quota/quota.c:396
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
In fs/quota/quota.c (ffffffff8132d098)
Location: fs/quota/quota.c:394
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
In fs/quota/quota.c (ffffffff81354c91)
Location: fs/quota/quota.c:387
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
In fs/quota/quota.c (ffffffff8136d001)
Location: fs/quota/quota.c:387
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffff813b4df3)
Location: fs/quota/quota.c:385
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/quota.c (ffffffff813c6813)
Location: fs/quota/quota.c:432
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int quota_getxstate(struct super_block *sb, int type, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813cc610)
Location: fs/quota/quota.c:433
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff813cc610-ffffffff813cc7bc: quota_getxstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int quota_getxstate(struct super_block *sb, int type, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff8141d8d0)
Location: fs/quota/quota.c:433
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff8141d8d0-ffffffff8141da7c: quota_getxstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int quota_getxstate(struct super_block *sb, int type, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff814953b0)
Location: fs/quota/quota.c:434
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff814953b0-ffffffff81495580: quota_getxstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int quota_getxstate(struct super_block *sb, int type, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff815292b0)
Location: fs/quota/quota.c:434
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff815292b0-ffffffff81529480: quota_getxstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int quota_getxstate(struct super_block *sb, int type, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81561770)
Location: fs/quota/quota.c:434
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81561770-ffffffff81561940: quota_getxstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int quota_getxstate(struct super_block *sb, int type, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff81597e60)
Location: fs/quota/quota.c:434
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
```
**Symbols:**

```
ffffffff81597e60-ffffffff81598030: quota_getxstate (STB_LOCAL)
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
In fs/quota/quota.c (ffff800010436cd0)
Location: fs/quota/quota.c:387
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
In fs/quota/quota.c (c05fe74c)
Location: fs/quota/quota.c:387
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
In fs/quota/quota.c (c000000000548df4)
Location: fs/quota/quota.c:387
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
In fs/quota/quota.c (ffffffe0002d1068)
Location: fs/quota/quota.c:387
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
In fs/quota/quota.c (ffffffff813655e1)
Location: fs/quota/quota.c:387
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
In fs/quota/quota.c (ffffffff81356281)
Location: fs/quota/quota.c:387
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
In fs/quota/quota.c (ffffffff813630b1)
Location: fs/quota/quota.c:387
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
In fs/quota/quota.c (ffffffff81376761)
Location: fs/quota/quota.c:387
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
