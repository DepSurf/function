# Function: <code>name_to_int</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127dd00)
Location: fs/proc/internal.h:115
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
```
```
In fs/proc/generic.c (ffffffff8127f017)
Location: fs/proc/internal.h:115
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/fd.c (ffffffff8128143f)
Location: fs/proc/internal.h:115
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfd_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812aacd0)
Location: fs/proc/internal.h:115
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
```
```
In fs/proc/generic.c (ffffffff812ac063)
Location: fs/proc/internal.h:115
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/fd.c (ffffffff812ae4f3)
Location: fs/proc/internal.h:115
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfd_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812c05a0)
Location: fs/proc/internal.h:115
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
```
```
In fs/proc/generic.c (ffffffff812c194b)
Location: fs/proc/internal.h:115
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/fd.c (ffffffff812c3ed3)
Location: fs/proc/internal.h:115
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfd_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812cd902)
Location: fs/proc/internal.h:107
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
```
```
In fs/proc/generic.c (ffffffff812cee01)
Location: fs/proc/internal.h:107
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/fd.c (ffffffff812d1233)
Location: fs/proc/internal.h:107
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfd_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff812f78f0)
Location: fs/proc/util.c:3
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffffffff812f78f0-ffffffff812f7940: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff81324c70)
Location: fs/proc/util.c:3
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffffffff81324c70-ffffffff81324cc6: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff8133be10)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffffffff8133be10-ffffffff8133be66: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff81364040)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffffffff81364040-ffffffff81364099: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff8137c2d0)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffffffff8137c2d0-ffffffff8137c329: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff813c5be0)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff813c5be0-ffffffff813c5c39: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff813d7b80)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffffffff813d7b80-ffffffff813d7bd9: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff813dea30)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff813dea30-ffffffff813dea89: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff814303a0)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff814303a0-ffffffff814303f9: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff814aa070)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff814aa070-ffffffff814aa0cd: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff8153fc30)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff8153fc30-ffffffff8153fc8d: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff81577fb0)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff81577fb0-ffffffff8157800d: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff815b06e0)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffffffff815b06e0-ffffffff815b073d: name_to_int (STB_GLOBAL)
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
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffff800010448a88)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffff800010448a88-ffff800010448b10: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (c060dc04)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
c060dc04-c060dc7c: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (c00000000055f1c0)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
c00000000055f1c0-c00000000055f254: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffe0002de5ae)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffffffe0002de5ae-ffffffe0002de626: name_to_int (STB_GLOBAL)
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
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff813748b0)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffffffff813748b0-ffffffff81374909: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff81365380)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffffffff81365380-ffffffff813653d9: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff81372380)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffffffff81372380-ffffffff813723d9: name_to_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr *qstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/util.c (ffffffff81385d60)
Location: fs/proc/util.c:4
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/generic.c:__proc_create
  - fs/proc/fd.c:proc_lookupfd_common
```
**Symbols:**

```
ffffffff81385d60-ffffffff81385db9: name_to_int (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
