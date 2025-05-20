# Function: <code>forget_original_parent</code>

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
In kernel/exit.c (ffffffff81083bd5)
Location: kernel/exit.c:551
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff81086cfe)
Location: kernel/exit.c:626
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff8108bc6d)
Location: kernel/exit.c:635
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff81088e0f)
Location: kernel/exit.c:661
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff8108fb3d)
Location: kernel/exit.c:661
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff810936a0)
Location: kernel/exit.c:661
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff8109b969)
Location: kernel/exit.c:670
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff8109ffd8)
Location: kernel/exit.c:672
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff810a6651)
Location: kernel/exit.c:606
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void forget_original_parent(struct task_struct *father, struct list_head *dead);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ac800)
Location: kernel/exit.c:603
Inline: False
Direct callers:
  - kernel/exit.c:exit_notify
```
**Symbols:**

```
ffffffff810ac800-ffffffff810acaaa: forget_original_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void forget_original_parent(struct task_struct *father, struct list_head *dead);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7ec0)
Location: kernel/exit.c:622
Inline: False
Direct callers:
  - kernel/exit.c:exit_notify
```
**Symbols:**

```
ffffffff810a7ec0-ffffffff810a816a: forget_original_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void forget_original_parent(struct task_struct *father, struct list_head *dead);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8cd0)
Location: kernel/exit.c:622
Inline: False
Direct callers:
  - kernel/exit.c:exit_notify
```
**Symbols:**

```
ffffffff810a8cd0-ffffffff810a9024: forget_original_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void forget_original_parent(struct task_struct *father, struct list_head *dead);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ba7c0)
Location: kernel/exit.c:622
Inline: False
Direct callers:
  - kernel/exit.c:exit_notify
```
**Symbols:**

```
ffffffff810ba7c0-ffffffff810bab15: forget_original_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void forget_original_parent(struct task_struct *father, struct list_head *dead);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d1380)
Location: kernel/exit.c:631
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff810d1380-ffffffff810d16ea: forget_original_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void forget_original_parent(struct task_struct *father, struct list_head *dead);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810efdc0)
Location: kernel/exit.c:684
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff810efdc0-ffffffff810f012a: forget_original_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void forget_original_parent(struct task_struct *father, struct list_head *dead);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fbd80)
Location: kernel/exit.c:688
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff810fbd80-ffffffff810fc0e7: forget_original_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void forget_original_parent(struct task_struct *father, struct list_head *dead);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81105290)
Location: kernel/exit.c:690
Inline: False
Direct callers:
  - kernel/exit.c:exit_notify
```
**Symbols:**

```
ffffffff81105290-ffffffff811055ec: forget_original_parent (STB_LOCAL)
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
In kernel/exit.c (ffff8000100fd5b8)
Location: kernel/exit.c:606
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (c035a77c)
Location: kernel/exit.c:606
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (c0000000001444bc)
Location: kernel/exit.c:606
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffe0000c5e20)
Location: kernel/exit.c:606
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff8109ff71)
Location: kernel/exit.c:606
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff8108e9a1)
Location: kernel/exit.c:606
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff8109ff21)
Location: kernel/exit.c:606
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff810a7e8c)
Location: kernel/exit.c:606
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
