# Function: <code>free_signal_struct</code>

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
In kernel/fork.c (ffffffff8107e29c)
Location: kernel/fork.c:240
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffff8107ff3c)
Location: kernel/fork.c:247
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffff810846fc)
Location: kernel/fork.c:368
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffff8108164c)
Location: kernel/fork.c:392
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffff81087f24)
Location: kernel/fork.c:398
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffff8108b51c)
Location: kernel/fork.c:660
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffff8109341c)
Location: kernel/fork.c:703
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffff81099a41)
Location: kernel/fork.c:708
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffff8109fec5)
Location: kernel/fork.c:720
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_signal_struct(struct signal_struct *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a50d5)
Location: kernel/fork.c:728
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810a4490-ffffffff810a4526: free_signal_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_signal_struct(struct signal_struct *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a07f8)
Location: kernel/fork.c:713
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8109f940-ffffffff8109f9d6: free_signal_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_signal_struct(struct signal_struct *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1680)
Location: kernel/fork.c:717
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810a06d0-ffffffff810a0766: free_signal_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_signal_struct(struct signal_struct *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b2ab8)
Location: kernel/fork.c:729
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810b1ae0-ffffffff810b1b76: free_signal_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_signal_struct(struct signal_struct *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c8cc8)
Location: kernel/fork.c:819
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810c8070-ffffffff810c8110: free_signal_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_signal_struct(struct signal_struct *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e6168)
Location: kernel/fork.c:829
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810e5240-ffffffff810e52e0: free_signal_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_signal_struct(struct signal_struct *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f19e0)
Location: kernel/fork.c:956
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810f08e0-ffffffff810f097f: free_signal_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_signal_struct(struct signal_struct *sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fad40)
Location: kernel/fork.c:951
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810f9cd0-ffffffff810f9d6f: free_signal_struct (STB_LOCAL)
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
In kernel/fork.c (ffff8000100f4558)
Location: kernel/fork.c:720
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (c0352e5c)
Location: kernel/fork.c:720
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (c000000000139e90)
Location: kernel/fork.c:720
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffe0000c0b68)
Location: kernel/fork.c:720
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffff810997e5)
Location: kernel/fork.c:720
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffff8108822b)
Location: kernel/fork.c:720
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffff81099795)
Location: kernel/fork.c:720
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
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
In kernel/fork.c (ffffffff810a13fe)
Location: kernel/fork.c:720
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
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
