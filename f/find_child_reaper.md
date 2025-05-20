# Function: <code>find_child_reaper</code>

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
In kernel/exit.c (ffffffff81083be9)
Location: kernel/exit.c:453
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
In kernel/exit.c (ffffffff81086d15)
Location: kernel/exit.c:528
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
In kernel/exit.c (ffffffff8108bc84)
Location: kernel/exit.c:537
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
In kernel/exit.c (ffffffff81088e26)
Location: kernel/exit.c:560
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
In kernel/exit.c (ffffffff8108fb54)
Location: kernel/exit.c:560
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
In kernel/exit.c (ffffffff810936b7)
Location: kernel/exit.c:560
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
In kernel/exit.c (ffffffff8109b980)
Location: kernel/exit.c:561
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
In kernel/exit.c (ffffffff8109ffef)
Location: kernel/exit.c:563
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
In kernel/exit.c (ffffffff810a6668)
Location: kernel/exit.c:501
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
struct task_struct *find_child_reaper(struct task_struct *father, struct list_head *dead);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ac730)
Location: kernel/exit.c:498
Inline: False
Direct callers:
  - kernel/exit.c:forget_original_parent
```
**Symbols:**

```
ffffffff810ac730-ffffffff810ac7fa: find_child_reaper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *find_child_reaper(struct task_struct *father, struct list_head *dead);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7df0)
Location: kernel/exit.c:517
Inline: False
Direct callers:
  - kernel/exit.c:forget_original_parent
```
**Symbols:**

```
ffffffff810a7df0-ffffffff810a7eba: find_child_reaper (STB_LOCAL)
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
In kernel/exit.c (ffffffff810a8d04)
Location: kernel/exit.c:517
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
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
In kernel/exit.c (ffffffff810ba7f4)
Location: kernel/exit.c:517
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
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
In kernel/exit.c (ffffffff810d13b4)
Location: kernel/exit.c:526
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
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
In kernel/exit.c (ffffffff810efdf4)
Location: kernel/exit.c:579
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
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
In kernel/exit.c (ffffffff810fbdb4)
Location: kernel/exit.c:583
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
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
In kernel/exit.c (ffffffff811052c4)
Location: kernel/exit.c:585
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
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
In kernel/exit.c (ffff8000100fd5c8)
Location: kernel/exit.c:501
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
In kernel/exit.c (c035a790)
Location: kernel/exit.c:501
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
In kernel/exit.c (c0000000001444cc)
Location: kernel/exit.c:501
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
In kernel/exit.c (ffffffe0000c5e2c)
Location: kernel/exit.c:501
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
In kernel/exit.c (ffffffff8109ff88)
Location: kernel/exit.c:501
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
In kernel/exit.c (ffffffff8108e9b8)
Location: kernel/exit.c:501
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
In kernel/exit.c (ffffffff8109ff38)
Location: kernel/exit.c:501
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
In kernel/exit.c (ffffffff810a7ea3)
Location: kernel/exit.c:501
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
</ul>
