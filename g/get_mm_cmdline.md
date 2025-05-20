# Function: <code>get_mm_cmdline</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131e2aa)
Location: fs/proc/base.c:208
Inline: True
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
In fs/proc/base.c (ffffffff81334e6a)
Location: fs/proc/base.c:212
Inline: True
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
In fs/proc/base.c (ffffffff8135bb37)
Location: fs/proc/base.c:253
Inline: True
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
In fs/proc/base.c (ffffffff81373f87)
Location: fs/proc/base.c:253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t get_mm_cmdline(struct mm_struct *mm, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:255
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff813bcee0-ffffffff813bd1c0: get_mm_cmdline (STB_LOCAL)
ffffffff813c0085-ffffffff813c0091: get_mm_cmdline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t get_mm_cmdline(struct mm_struct *mm, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:255
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff813ceb30-ffffffff813cee10: get_mm_cmdline (STB_LOCAL)
ffffffff81bebcbd-ffffffff81bebcc9: get_mm_cmdline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t get_mm_cmdline(struct mm_struct *mm, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:254
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff813d6390-ffffffff813d6698: get_mm_cmdline (STB_LOCAL)
ffffffff81bddccc-ffffffff81bddcd8: get_mm_cmdline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t get_mm_cmdline(struct mm_struct *mm, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:256
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff81427c60-ffffffff81427f68: get_mm_cmdline (STB_LOCAL)
ffffffff81cc80ce-ffffffff81cc80da: get_mm_cmdline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t get_mm_cmdline(struct mm_struct *mm, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8149e240)
Location: fs/proc/base.c:255
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff8149e240-ffffffff8149e468: get_mm_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t get_mm_cmdline(struct mm_struct *mm, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81532f20)
Location: fs/proc/base.c:256
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff81532f20-ffffffff81533148: get_mm_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t get_mm_cmdline(struct mm_struct *mm, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156b110)
Location: fs/proc/base.c:257
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff8156b110-ffffffff8156b338: get_mm_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t get_mm_cmdline(struct mm_struct *mm, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a3af0)
Location: fs/proc/base.c:257
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff815a3af0-ffffffff815a3d18: get_mm_cmdline (STB_LOCAL)
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
In fs/proc/base.c (ffff80001043fc4c)
Location: fs/proc/base.c:253
Inline: True
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
In fs/proc/base.c (c0604aec)
Location: fs/proc/base.c:253
Inline: True
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
In fs/proc/base.c (c000000000553c90)
Location: fs/proc/base.c:253
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_cmdline_read
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
In fs/proc/base.c (ffffffe0002d6ebc)
Location: fs/proc/base.c:253
Inline: True
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
In fs/proc/base.c (ffffffff8136c567)
Location: fs/proc/base.c:253
Inline: True
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
In fs/proc/base.c (ffffffff8135cff7)
Location: fs/proc/base.c:253
Inline: True
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
In fs/proc/base.c (ffffffff8136a037)
Location: fs/proc/base.c:253
Inline: True
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
In fs/proc/base.c (ffffffff8137d907)
Location: fs/proc/base.c:253
Inline: True
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
