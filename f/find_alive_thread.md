# Function: <code>find_alive_thread</code>

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
In kernel/exit.c (ffffffff810841e3)
Location: kernel/exit.c:442
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff81087331)
Location: kernel/exit.c:517
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff8108c294)
Location: kernel/exit.c:526
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff81089417)
Location: kernel/exit.c:549
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff810901a3)
Location: kernel/exit.c:549
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff81093c2d)
Location: kernel/exit.c:549
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff8109bf39)
Location: kernel/exit.c:550
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff810a0552)
Location: kernel/exit.c:552
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff810a6b3d)
Location: kernel/exit.c:490
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *find_alive_thread(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810abbd0)
Location: kernel/exit.c:487
Inline: False
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:find_child_reaper
```
**Symbols:**

```
ffffffff810abbd0-ffffffff810abc15: find_alive_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *find_alive_thread(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a71c0)
Location: kernel/exit.c:506
Inline: False
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:find_child_reaper
```
**Symbols:**

```
ffffffff810a71c0-ffffffff810a7205: find_alive_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *find_alive_thread(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8260)
Location: kernel/exit.c:506
Inline: False
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
**Symbols:**

```
ffffffff810a8260-ffffffff810a82a5: find_alive_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/exit.c (ffffffff810b9f70)
Location: kernel/exit.c:506
Inline: True
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
**Symbols:**

```
ffffffff810b9f70-ffffffff810b9fae: find_alive_thread.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/exit.c (ffffffff810d0ac0)
Location: kernel/exit.c:515
Inline: True
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
**Symbols:**

```
ffffffff810d0ac0-ffffffff810d0b0e: find_alive_thread.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/exit.c (ffffffff810ef490)
Location: kernel/exit.c:568
Inline: True
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
**Symbols:**

```
ffffffff810ef490-ffffffff810ef4de: find_alive_thread.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *find_alive_thread(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fb0c0)
Location: kernel/exit.c:572
Inline: False
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
**Symbols:**

```
ffffffff810fb0c0-ffffffff810fb119: find_alive_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *find_alive_thread(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81104570)
Location: kernel/exit.c:574
Inline: False
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
**Symbols:**

```
ffffffff81104570-ffffffff811045c9: find_alive_thread (STB_LOCAL)
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
In kernel/exit.c (ffff8000100fda30)
Location: kernel/exit.c:490
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (c035ac24)
Location: kernel/exit.c:490
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (c000000000144ab8)
Location: kernel/exit.c:490
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffe0000c61a4)
Location: kernel/exit.c:490
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff810a045d)
Location: kernel/exit.c:490
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff8108ee89)
Location: kernel/exit.c:490
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff810a040d)
Location: kernel/exit.c:490
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
In kernel/exit.c (ffffffff810a8398)
Location: kernel/exit.c:490
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
