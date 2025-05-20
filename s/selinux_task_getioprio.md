# Function: <code>selinux_task_getioprio</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3840
Inline: False
```
**Symbols:**

```
ffffffff81377670-ffffffff81377680: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3912
Inline: False
```
**Symbols:**

```
ffffffff8138e080-ffffffff8138e090: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a42f0)
Location: security/selinux/hooks.c:3875
Inline: False
```
**Symbols:**

```
ffffffff813a42f0-ffffffff813a433a: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813ca3d0)
Location: security/selinux/hooks.c:3890
Inline: False
```
**Symbols:**

```
ffffffff813ca3d0-ffffffff813ca41a: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813f9790)
Location: security/selinux/hooks.c:4116
Inline: False
```
**Symbols:**

```
ffffffff813f9790-ffffffff813f97da: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81415640)
Location: security/selinux/hooks.c:3836
Inline: False
```
**Symbols:**

```
ffffffff81415640-ffffffff81415692: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81443030)
Location: security/selinux/hooks.c:4024
Inline: False
```
**Symbols:**

```
ffffffff81443030-ffffffff81443082: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145cb70)
Location: security/selinux/hooks.c:4082
Inline: False
```
**Symbols:**

```
ffffffff8145cb70-ffffffff8145cbca: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814afe80)
Location: security/selinux/hooks.c:4075
Inline: True
```
**Symbols:**

```
ffffffff814afe80-ffffffff814afeda: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d0f40)
Location: security/selinux/hooks.c:4091
Inline: False
```
**Symbols:**

```
ffffffff814d0f40-ffffffff814d0fa9: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d6f90)
Location: security/selinux/hooks.c:4255
Inline: True
```
**Symbols:**

```
ffffffff814d6f90-ffffffff814d6ff9: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81530140)
Location: security/selinux/hooks.c:4240
Inline: True
```
**Symbols:**

```
ffffffff81530140-ffffffff815301a9: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c6ce0)
Location: security/selinux/hooks.c:4136
Inline: False
```
**Symbols:**

```
ffffffff815c6ce0-ffffffff815c6d60: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81673bd0)
Location: security/selinux/hooks.c:4154
Inline: False
```
**Symbols:**

```
ffffffff81673bd0-ffffffff81673c50: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816abf50)
Location: security/selinux/hooks.c:4122
Inline: False
```
**Symbols:**

```
ffffffff816abf50-ffffffff816abfc5: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e9460)
Location: security/selinux/hooks.c:4210
Inline: False
```
**Symbols:**

```
ffffffff816e9460-ffffffff816e94db: selinux_task_getioprio (STB_LOCAL)
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
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010549830)
Location: security/selinux/hooks.c:4082
Inline: False
```
**Symbols:**

```
ffff800010549830-ffff8000105498a0: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06ff55c)
Location: security/selinux/hooks.c:4082
Inline: False
```
**Symbols:**

```
c06ff55c-c06ff5dc: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a0f10)
Location: security/selinux/hooks.c:4082
Inline: False
```
**Symbols:**

```
c0000000006a0f10-c0000000006a0f88: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a4686)
Location: security/selinux/hooks.c:4082
Inline: False
```
**Symbols:**

```
ffffffe0003a4686-ffffffe0003a46de: selinux_task_getioprio (STB_LOCAL)
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
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81455150)
Location: security/selinux/hooks.c:4082
Inline: False
```
**Symbols:**

```
ffffffff81455150-ffffffff814551aa: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81445b90)
Location: security/selinux/hooks.c:4082
Inline: False
```
**Symbols:**

```
ffffffff81445b90-ffffffff81445bea: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814511f0)
Location: security/selinux/hooks.c:4082
Inline: False
```
**Symbols:**

```
ffffffff814511f0-ffffffff8145124a: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int selinux_task_getioprio(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81469da0)
Location: security/selinux/hooks.c:4082
Inline: False
```
**Symbols:**

```
ffffffff81469da0-ffffffff81469e11: selinux_task_getioprio (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
