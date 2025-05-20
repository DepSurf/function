# Function: <code>get_mm_proctitle</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135bd6e)
Location: fs/proc/base.c:216
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
In fs/proc/base.c (ffffffff813741be)
Location: fs/proc/base.c:216
Inline: True
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
In fs/proc/base.c (ffffffff813bd0c9)
Location: fs/proc/base.c:218
Inline: True
Inline callers:
  - fs/proc/base.c:get_mm_cmdline
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
In fs/proc/base.c (ffffffff813ced19)
Location: fs/proc/base.c:218
Inline: True
Inline callers:
  - fs/proc/base.c:get_mm_cmdline
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
In fs/proc/base.c (ffffffff813d657e)
Location: fs/proc/base.c:217
Inline: True
Inline callers:
  - fs/proc/base.c:get_mm_cmdline
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
In fs/proc/base.c (ffffffff81427e4e)
Location: fs/proc/base.c:219
Inline: True
Inline callers:
  - fs/proc/base.c:get_mm_cmdline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t get_mm_proctitle(struct mm_struct *mm, char *buf, size_t count, long unsigned int pos, long unsigned int arg_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (0)
Location: fs/proc/base.c:218
Inline: False
Direct callers:
  - fs/proc/base.c:get_mm_cmdline
```
**Symbols:**

```
ffffffff8149e0e0-ffffffff8149e235: get_mm_proctitle (STB_LOCAL)
ffffffff81e7ac76-ffffffff81e7ac82: get_mm_proctitle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t get_mm_proctitle(struct mm_struct *mm, char *buf, size_t count, long unsigned int pos, long unsigned int arg_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81532db0)
Location: fs/proc/base.c:219
Inline: False
Direct callers:
  - fs/proc/base.c:get_mm_cmdline
```
**Symbols:**

```
ffffffff81532db0-ffffffff81532f0c: get_mm_proctitle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t get_mm_proctitle(struct mm_struct *mm, char *buf, size_t count, long unsigned int pos, long unsigned int arg_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156afa0)
Location: fs/proc/base.c:220
Inline: False
Direct callers:
  - fs/proc/base.c:get_mm_cmdline
```
**Symbols:**

```
ffffffff8156afa0-ffffffff8156b0fc: get_mm_proctitle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t get_mm_proctitle(struct mm_struct *mm, char *buf, size_t count, long unsigned int pos, long unsigned int arg_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a3980)
Location: fs/proc/base.c:220
Inline: False
Direct callers:
  - fs/proc/base.c:get_mm_cmdline
```
**Symbols:**

```
ffffffff815a3980-ffffffff815a3adc: get_mm_proctitle (STB_LOCAL)
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
In fs/proc/base.c (ffff80001043fe98)
Location: fs/proc/base.c:216
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
In fs/proc/base.c (c0604d10)
Location: fs/proc/base.c:216
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
In fs/proc/base.c (c000000000553f8c)
Location: fs/proc/base.c:216
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
In fs/proc/base.c (ffffffe0002d704e)
Location: fs/proc/base.c:216
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
In fs/proc/base.c (ffffffff8136c79e)
Location: fs/proc/base.c:216
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
In fs/proc/base.c (ffffffff8135d22e)
Location: fs/proc/base.c:216
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
In fs/proc/base.c (ffffffff8136a26e)
Location: fs/proc/base.c:216
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
In fs/proc/base.c (ffffffff8137db44)
Location: fs/proc/base.c:216
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
