# Function: <code>dup_task_struct</code>

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
In kernel/fork.c (ffffffff8107e76d)
Location: kernel/fork.c:339
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810803e3)
Location: kernel/fork.c:346
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
In kernel/fork.c (ffffffff81084d4c)
Location: kernel/fork.c:478
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
In kernel/fork.c (ffffffff81081c19)
Location: kernel/fork.c:509
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
In kernel/fork.c (ffffffff810884db)
Location: kernel/fork.c:517
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
In kernel/fork.c (ffffffff8108c22e)
Location: kernel/fork.c:797
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
In kernel/fork.c (ffffffff81093b60)
Location: kernel/fork.c:841
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
In kernel/fork.c (ffffffff81098303)
Location: kernel/fork.c:847
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff8109e8d0)
Location: kernel/fork.c:861
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *dup_task_struct(struct task_struct *orig, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a5a20)
Location: kernel/fork.c:871
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810a5a20-ffffffff810a5bc5: dup_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *dup_task_struct(struct task_struct *orig, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a12d0)
Location: kernel/fork.c:856
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810a12d0-ffffffff810a15aa: dup_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *dup_task_struct(struct task_struct *orig, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a2040)
Location: kernel/fork.c:861
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810a2040-ffffffff810a232a: dup_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *dup_task_struct(struct task_struct *orig, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b2e20)
Location: kernel/fork.c:879
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810b2e20-ffffffff810b3128: dup_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *dup_task_struct(struct task_struct *orig, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9140)
Location: kernel/fork.c:967
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810c9140-ffffffff810c92f2: dup_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *dup_task_struct(struct task_struct *orig, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e6630)
Location: kernel/fork.c:977
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810e6630-ffffffff810e67e0: dup_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *dup_task_struct(struct task_struct *orig, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f1fa0)
Location: kernel/fork.c:1103
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810f1fa0-ffffffff810f2167: dup_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *dup_task_struct(struct task_struct *orig, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fbc00)
Location: kernel/fork.c:1102
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810fbc00-ffffffff810fbda2: dup_task_struct (STB_LOCAL)
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
struct task_struct *dup_task_struct(struct task_struct *orig, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f2ff0)
Location: kernel/fork.c:861
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffff8000100f2ff0-ffff8000100f331c: dup_task_struct (STB_LOCAL)
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
In kernel/fork.c (c0351d28)
Location: kernel/fork.c:861
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (c000000000139354)
Location: kernel/fork.c:861
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffe0000bfd52)
Location: kernel/fork.c:861
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810981f0)
Location: kernel/fork.c:861
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff81086c4a)
Location: kernel/fork.c:861
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810981a0)
Location: kernel/fork.c:861
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff8109fd97)
Location: kernel/fork.c:861
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
<b>Arch</b>
<ul>
</ul>
