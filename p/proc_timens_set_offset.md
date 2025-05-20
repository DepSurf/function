# Function: <code>proc_timens_set_offset</code>

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
int proc_timens_set_offset(struct file *file, struct task_struct *p, struct proc_timens_offset *offsets, int noffsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8115a3b0)
Location: kernel/time/namespace.c:373
Inline: False
Direct callers:
  - fs/proc/base.c:timens_offsets_write
```
**Symbols:**

```
ffffffff8115a3b0-ffffffff8115a603: proc_timens_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int proc_timens_set_offset(struct file *file, struct task_struct *p, struct proc_timens_offset *offsets, int noffsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81156400)
Location: kernel/time/namespace.c:362
Inline: False
Direct callers:
  - fs/proc/base.c:timens_offsets_write
```
**Symbols:**

```
ffffffff81156400-ffffffff8115665e: proc_timens_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int proc_timens_set_offset(struct file *file, struct task_struct *p, struct proc_timens_offset *offsets, int noffsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81157800)
Location: kernel/time/namespace.c:362
Inline: False
Direct callers:
  - fs/proc/base.c:timens_offsets_write
```
**Symbols:**

```
ffffffff81157800-ffffffff81157a5e: proc_timens_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int proc_timens_set_offset(struct file *file, struct task_struct *p, struct proc_timens_offset *offsets, int noffsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/namespace.c (0)
Location: kernel/time/namespace.c:362
Inline: False
Direct callers:
  - fs/proc/base.c:timens_offsets_write
```
**Symbols:**

```
ffffffff81cb22f9-ffffffff81cb230e: proc_timens_set_offset.cold (STB_LOCAL)
ffffffff8117c670-ffffffff8117c8d4: proc_timens_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int proc_timens_set_offset(struct file *file, struct task_struct *p, struct proc_timens_offset *offsets, int noffsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/namespace.c (0)
Location: kernel/time/namespace.c:362
Inline: False
Direct callers:
  - fs/proc/base.c:timens_offsets_write
```
**Symbols:**

```
ffffffff81e6387c-ffffffff81e638ba: proc_timens_set_offset.cold (STB_LOCAL)
ffffffff811b1f10-ffffffff811b2243: proc_timens_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int proc_timens_set_offset(struct file *file, struct task_struct *p, struct proc_timens_offset *offsets, int noffsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/namespace.c (0)
Location: kernel/time/namespace.c:380
Inline: False
Direct callers:
  - fs/proc/base.c:timens_offsets_write
```
**Symbols:**

```
ffffffff8205bf3c-ffffffff8205bf7a: proc_timens_set_offset.cold (STB_LOCAL)
ffffffff811f2d40-ffffffff811f3073: proc_timens_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int proc_timens_set_offset(struct file *file, struct task_struct *p, struct proc_timens_offset *offsets, int noffsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/namespace.c (0)
Location: kernel/time/namespace.c:380
Inline: False
Direct callers:
  - fs/proc/base.c:timens_offsets_write
```
**Symbols:**

```
ffffffff820da72e-ffffffff820da759: proc_timens_set_offset.cold (STB_LOCAL)
ffffffff812074c0-ffffffff81207800: proc_timens_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int proc_timens_set_offset(struct file *file, struct task_struct *p, struct proc_timens_offset *offsets, int noffsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/namespace.c (0)
Location: kernel/time/namespace.c:380
Inline: False
Direct callers:
  - fs/proc/base.c:timens_offsets_write
```
**Symbols:**

```
ffffffff821b629e-ffffffff821b62c9: proc_timens_set_offset.cold (STB_LOCAL)
ffffffff8121e6d0-ffffffff8121ea10: proc_timens_set_offset (STB_GLOBAL)
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
