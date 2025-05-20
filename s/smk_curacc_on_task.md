# Function: <code>smk_curacc_on_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8135eee0)
Location: security/smack/smack_lsm.c:2090
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff8135eee0-ffffffff8135ef64: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813953f0)
Location: security/smack/smack_lsm.c:2106
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff813953f0-ffffffff81395474: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813abb80)
Location: security/smack/smack_lsm.c:2097
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff813abb80-ffffffff813abc04: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c3ba0)
Location: security/smack/smack_lsm.c:2023
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff813c3ba0-ffffffff813c3c2c: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e9ef0)
Location: security/smack/smack_lsm.c:1992
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff813e9ef0-ffffffff813e9f7c: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8141ad60)
Location: security/smack/smack_lsm.c:2111
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff8141ad60-ffffffff8141ade4: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81436e40)
Location: security/smack/smack_lsm.c:1956
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff81436e40-ffffffff81436ecc: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81464f40)
Location: security/smack/smack_lsm.c:2043
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff81464f40-ffffffff81464fc8: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8147ed10)
Location: security/smack/smack_lsm.c:2042
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff8147ed10-ffffffff8147ed98: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814d4370)
Location: security/smack/smack_lsm.c:2030
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff814d4370-ffffffff814d43f8: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f1840)
Location: security/smack/smack_lsm.c:2030
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff814f1840-ffffffff814f18eb: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f84e0)
Location: security/smack/smack_lsm.c:2015
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff814f84e0-ffffffff814f858b: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815530d0)
Location: security/smack/smack_lsm.c:2015
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff815530d0-ffffffff8155317b: smk_curacc_on_task (STB_LOCAL)
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
In security/smack/smack_lsm.c (ffffffff815ed350)
Location: security/smack/smack_lsm.c:2022
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
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
In security/smack/smack_lsm.c (ffffffff8169d470)
Location: security/smack/smack_lsm.c:2082
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
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
In security/smack/smack_lsm.c (ffffffff816d5e10)
Location: security/smack/smack_lsm.c:2145
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
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
In security/smack/smack_lsm.c (ffffffff817126b0)
Location: security/smack/smack_lsm.c:2201
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
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
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff8000105703c8)
Location: security/smack/smack_lsm.c:2042
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffff8000105703c8-ffff800010570460: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0723998)
Location: security/smack/smack_lsm.c:2042
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
c0723998-c0723a3c: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d6ae0)
Location: security/smack/smack_lsm.c:2042
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
c0000000006d6ae0-c0000000006d6b88: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c3146)
Location: security/smack/smack_lsm.c:2042
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffe0003c3146-ffffffe0003c31b8: smk_curacc_on_task (STB_LOCAL)
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
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814772f0)
Location: security/smack/smack_lsm.c:2042
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff814772f0-ffffffff81477378: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81467d10)
Location: security/smack/smack_lsm.c:2042
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff81467d10-ffffffff81467d98: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81473390)
Location: security/smack/smack_lsm.c:2042
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff81473390-ffffffff81473418: smk_curacc_on_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smk_curacc_on_task(struct task_struct *p, int access, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8148ac80)
Location: security/smack/smack_lsm.c:2042
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
```
**Symbols:**

```
ffffffff8148ac80-ffffffff8148ad30: smk_curacc_on_task (STB_LOCAL)
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
