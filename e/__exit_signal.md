# Function: <code>__exit_signal</code>

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
In kernel/exit.c (ffffffff810824a3)
Location: kernel/exit.c:83
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (ffffffff81085471)
Location: kernel/exit.c:82
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (ffffffff8108a3e1)
Location: kernel/exit.c:83
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (ffffffff81087435)
Location: kernel/exit.c:90
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (ffffffff8108e1c5)
Location: kernel/exit.c:90
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (ffffffff81091cf3)
Location: kernel/exit.c:90
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
In kernel/exit.c (ffffffff81099fe3)
Location: kernel/exit.c:91
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
In kernel/exit.c (ffffffff8109e60a)
Location: kernel/exit.c:92
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (ffffffff810a4b91)
Location: kernel/exit.c:92
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __exit_signal(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810abe30)
Location: kernel/exit.c:91
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810abe30-ffffffff810ac162: __exit_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __exit_signal(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a74d0)
Location: kernel/exit.c:92
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810a74d0-ffffffff810a7802: __exit_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __exit_signal(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8560)
Location: kernel/exit.c:92
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810a8560-ffffffff810a8892: __exit_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __exit_signal(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ba040)
Location: kernel/exit.c:92
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810ba040-ffffffff810ba372: __exit_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __exit_signal(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d0b10)
Location: kernel/exit.c:94
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810d0b10-ffffffff810d0e49: __exit_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __exit_signal(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ef4f0)
Location: kernel/exit.c:142
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810ef4f0-ffffffff810ef829: __exit_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __exit_signal(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fb4b0)
Location: kernel/exit.c:143
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810fb4b0-ffffffff810fb7e8: __exit_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __exit_signal(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff811048a0)
Location: kernel/exit.c:146
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff811048a0-ffffffff81104c11: __exit_signal (STB_LOCAL)
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
In kernel/exit.c (ffff8000100faa10)
Location: kernel/exit.c:92
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (c0358804)
Location: kernel/exit.c:92
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (c000000000141d7c)
Location: kernel/exit.c:92
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (ffffffe0000c47a2)
Location: kernel/exit.c:92
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (ffffffff8109e4b1)
Location: kernel/exit.c:92
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (ffffffff8108ced0)
Location: kernel/exit.c:92
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (ffffffff8109e461)
Location: kernel/exit.c:92
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
In kernel/exit.c (ffffffff810a637b)
Location: kernel/exit.c:92
Inline: True
Inline callers:
  - kernel/exit.c:release_task
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
