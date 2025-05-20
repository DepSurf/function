# Function: <code>task_stopped_code</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81082210)
Location: kernel/exit.c:1120
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff81082210-ffffffff8108225c: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81085250)
Location: kernel/exit.c:1206
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff81085250-ffffffff8108529c: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108a1c0)
Location: kernel/exit.c:1196
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff8108a1c0-ffffffff8108a20d: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810872f0)
Location: kernel/exit.c:1181
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810872f0-ffffffff8108733d: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108e060)
Location: kernel/exit.c:1180
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff8108e060-ffffffff8108e0ad: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81091b20)
Location: kernel/exit.c:1180
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff81091b20-ffffffff81091b67: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81099e00)
Location: kernel/exit.c:1183
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff81099e00-ffffffff81099e47: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e420)
Location: kernel/exit.c:1187
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff8109e420-ffffffff8109e467: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a4980)
Location: kernel/exit.c:1103
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810a4980-ffffffff810a49c7: task_stopped_code (STB_LOCAL)
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
In kernel/exit.c (ffffffff810ac1a0)
Location: kernel/exit.c:1107
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
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
In kernel/exit.c (ffffffff810a7840)
Location: kernel/exit.c:1126
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
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
In kernel/exit.c (ffffffff810a88d0)
Location: kernel/exit.c:1126
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
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
In kernel/exit.c (ffffffff810ba3b0)
Location: kernel/exit.c:1126
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
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
In kernel/exit.c (ffffffff810d0f49)
Location: kernel/exit.c:1130
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
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
In kernel/exit.c (ffffffff810ef949)
Location: kernel/exit.c:1224
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
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
In kernel/exit.c (ffffffff810fb909)
Location: kernel/exit.c:1229
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
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
In kernel/exit.c (ffffffff81104e09)
Location: kernel/exit.c:1201
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_stopped
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fa5b0)
Location: kernel/exit.c:1103
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffff8000100fa5b0-ffff8000100fa618: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c0358598)
Location: kernel/exit.c:1103
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
c0358598-c03585f4: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c0000000001419a0)
Location: kernel/exit.c:1103
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
c0000000001419a0-c0000000001419fc: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c463e)
Location: kernel/exit.c:1103
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffe0000c463e-ffffffe0000c469c: task_stopped_code (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e2a0)
Location: kernel/exit.c:1103
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff8109e2a0-ffffffff8109e2e7: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108ccb0)
Location: kernel/exit.c:1103
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff8108ccb0-ffffffff8108ccf7: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e250)
Location: kernel/exit.c:1103
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff8109e250-ffffffff8109e297: task_stopped_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int *task_stopped_code(struct task_struct *p, bool ptrace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a6150)
Location: kernel/exit.c:1103
Inline: True
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810a6150-ffffffff810a6197: task_stopped_code (STB_LOCAL)
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
