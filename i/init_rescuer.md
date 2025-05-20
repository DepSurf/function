# Function: <code>init_rescuer</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810aff37)
Location: kernel/workqueue.c:4020
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:workqueue_init
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810aaad0-ffffffff810aab7d: init_rescuer.part.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810b90a7)
Location: kernel/workqueue.c:4043
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:workqueue_init
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810b3a60-ffffffff810b3b0d: init_rescuer.part.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810bebf3)
Location: kernel/workqueue.c:4183
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810b9820-ffffffff810b98c1: init_rescuer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c51f3)
Location: kernel/workqueue.c:4201
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810bfbe0-ffffffff810bfc81: init_rescuer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int init_rescuer(struct workqueue_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7010)
Location: kernel/workqueue.c:4210
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c7010-ffffffff810c70fd: init_rescuer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int init_rescuer(struct workqueue_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c20e0)
Location: kernel/workqueue.c:4223
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c20e0-ffffffff810c21cd: init_rescuer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int init_rescuer(struct workqueue_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3a10)
Location: kernel/workqueue.c:4230
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c3a10-ffffffff810c3ac6: init_rescuer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int init_rescuer(struct workqueue_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d65b0)
Location: kernel/workqueue.c:4269
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810d65b0-ffffffff810d6666: init_rescuer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_rescuer(struct workqueue_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810eff40)
Location: kernel/workqueue.c:4252
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810eff40-ffffffff810f000d: init_rescuer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_rescuer(struct workqueue_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811118f0)
Location: kernel/workqueue.c:4261
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff811118f0-ffffffff811119bd: init_rescuer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_rescuer(struct workqueue_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111dca0)
Location: kernel/workqueue.c:4589
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff8111dca0-ffffffff8111dd88: init_rescuer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_rescuer(struct workqueue_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811278d0)
Location: kernel/workqueue.c:4629
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff811278d0-ffffffff811279b8: init_rescuer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffff8000101236d0)
Location: kernel/workqueue.c:4201
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffff80001011c6e8-ffff80001011c794: init_rescuer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (c0376fa8)
Location: kernel/workqueue.c:4201
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
c03715d4-c0371680: init_rescuer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (c00000000016d698)
Location: kernel/workqueue.c:4201
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
c000000000165d20-c000000000165e00: init_rescuer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffe0000dbd96)
Location: kernel/workqueue.c:4201
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffe0000d6abe-ffffffe0000d6b5a: init_rescuer.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810bf563)
Location: kernel/workqueue.c:4201
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810b9f50-ffffffff810b9ff1: init_rescuer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810add83)
Location: kernel/workqueue.c:4201
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810a8890-ffffffff810a8931: init_rescuer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810beac3)
Location: kernel/workqueue.c:4201
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810b94b0-ffffffff810b9551: init_rescuer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6e33)
Location: kernel/workqueue.c:4201
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c1fd0-ffffffff810c2071: init_rescuer.part.0 (STB_LOCAL)
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
