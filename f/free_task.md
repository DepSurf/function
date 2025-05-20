# Function: <code>free_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107e190)
Location: kernel/fork.c:227
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8107e190-ffffffff8107e1ec: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107fdf0)
Location: kernel/fork.c:234
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff8107fdf0-ffffffff8107fe82: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810845d0)
Location: kernel/fork.c:343
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810845d0-ffffffff81084642: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081540)
Location: kernel/fork.c:367
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff81081540-ffffffff81081593: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087e20)
Location: kernel/fork.c:373
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff81087e20-ffffffff81087e73: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b420)
Location: kernel/fork.c:399
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff8108b420-ffffffff8108b475: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81093320)
Location: kernel/fork.c:442
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff81093320-ffffffff81093375: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097420)
Location: kernel/fork.c:448
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff81097420-ffffffff81097479: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109dac0)
Location: kernel/fork.c:457
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff8109dac0-ffffffff8109db19: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a4fc0)
Location: kernel/fork.c:462
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810a4fc0-ffffffff810a501b: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a06d0)
Location: kernel/fork.c:448
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810a06d0-ffffffff810a0723: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1550)
Location: kernel/fork.c:452
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810a1550-ffffffff810a15a3: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b2980)
Location: kernel/fork.c:452
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810b2980-ffffffff810b29da: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c8b90)
Location: kernel/fork.c:543
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810c8b90-ffffffff810c8bef: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e6010)
Location: kernel/fork.c:541
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810e6010-ffffffff810e6080: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f1880)
Location: kernel/fork.c:605
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810f1880-ffffffff810f18f8: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fabe0)
Location: kernel/fork.c:585
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810fabe0-ffffffff810fac58: free_task (STB_GLOBAL)
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
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f2678)
Location: kernel/fork.c:457
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffff8000100f2678-ffff8000100f2700: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0350f60)
Location: kernel/fork.c:457
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
c0350f60-c0351020: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0000000001380d0)
Location: kernel/fork.c:457
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
c0000000001380d0-c0000000001381a8: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bf31a)
Location: kernel/fork.c:457
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffe0000bf31a-ffffffe0000bf390: free_task (STB_GLOBAL)
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
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810973e0)
Location: kernel/fork.c:457
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810973e0-ffffffff81097439: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085e60)
Location: kernel/fork.c:457
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff81085e60-ffffffff81085eb9: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097390)
Location: kernel/fork.c:457
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff81097390-ffffffff810973e9: free_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109ef90)
Location: kernel/fork.c:457
Inline: False
Direct callers:
  - kernel/fork.c:__delayed_free_task
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff8109ef90-ffffffff8109efe9: free_task (STB_GLOBAL)
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
