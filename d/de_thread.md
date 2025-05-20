# Function: <code>de_thread</code>

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
In fs/exec.c (ffffffff812132ef)
Location: fs/exec.c:905
Inline: True
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
In fs/exec.c (ffffffff81239e32)
Location: fs/exec.c:1052
Inline: True
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
In fs/exec.c (ffffffff8124cb62)
Location: fs/exec.c:1057
Inline: True
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
In fs/exec.c (ffffffff81258bc2)
Location: fs/exec.c:1083
Inline: True
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
In fs/exec.c (ffffffff8127ad62)
Location: fs/exec.c:1064
Inline: True
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
In fs/exec.c (ffffffff812a212e)
Location: fs/exec.c:1068
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
In fs/exec.c (ffffffff812b70ae)
Location: fs/exec.c:1071
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d4930)
Location: fs/exec.c:1072
Inline: False
```
**Symbols:**

```
ffffffff812d4930-ffffffff812d4da7: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e64b0)
Location: fs/exec.c:1073
Inline: False
```
**Symbols:**

```
ffffffff812e64b0-ffffffff812e6927: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131de20)
Location: fs/exec.c:1134
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff8131de20-ffffffff8131e1e2: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81329330)
Location: fs/exec.c:1046
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff81329330-ffffffff813296f2: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132f140)
Location: fs/exec.c:1038
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff8132f140-ffffffff8132f502: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137c920)
Location: fs/exec.c:1038
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff8137c920-ffffffff8137cce2: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813fbc60)
Location: fs/exec.c:1045
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff813fbc60-ffffffff813fc07f: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81484d10)
Location: fs/exec.c:1040
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff81484d10-ffffffff8148512f: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814b9c90)
Location: fs/exec.c:1043
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff814b9c90-ffffffff814ba0af: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ec200)
Location: fs/exec.c:1058
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff814ec200-ffffffff814ec62b: de_thread (STB_LOCAL)
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
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038e650)
Location: fs/exec.c:1073
Inline: False
```
**Symbols:**

```
ffff80001038e650-ffff80001038ec20: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0574ca4)
Location: fs/exec.c:1073
Inline: False
```
**Symbols:**

```
c0574ca4-c057517c: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000485540)
Location: fs/exec.c:1073
Inline: False
```
**Symbols:**

```
c000000000485540-c000000000485b84: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025e1ac)
Location: fs/exec.c:1073
Inline: False
```
**Symbols:**

```
ffffffe00025e1ac-ffffffe00025e65a: de_thread (STB_LOCAL)
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
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dea90)
Location: fs/exec.c:1073
Inline: False
```
**Symbols:**

```
ffffffff812dea90-ffffffff812def07: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cebd0)
Location: fs/exec.c:1073
Inline: False
```
**Symbols:**

```
ffffffff812cebd0-ffffffff812cf020: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dc8a0)
Location: fs/exec.c:1073
Inline: False
```
**Symbols:**

```
ffffffff812dc8a0-ffffffff812dcd17: de_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int de_thread(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ed660)
Location: fs/exec.c:1073
Inline: False
```
**Symbols:**

```
ffffffff812ed660-ffffffff812edb02: de_thread (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
