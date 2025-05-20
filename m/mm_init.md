# Function: <code>mm_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81f59de4)
Location: init/main.c:482
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff8107da50)
Location: kernel/fork.c:593
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8107da50-ffffffff8107dc19: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81f81db2)
Location: init/main.c:464
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff8107f640)
Location: kernel/fork.c:606
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff8107f640-ffffffff8107f801: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81fbddfb)
Location: init/main.c:467
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff81083cf0)
Location: kernel/fork.c:755
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff81083cf0-ffffffff81083eee: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8209defc)
Location: init/main.c:494
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff81080c20)
Location: kernel/fork.c:800
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff81080c20-ffffffff81080e39: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff826a3ec3)
Location: init/main.c:496
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff81087590)
Location: kernel/fork.c:813
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff81087590-ffffffff810877fb: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff826ccf62)
Location: init/main.c:513
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff8108aab0)
Location: kernel/fork.c:920
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff8108aab0-ffffffff8108ad21: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82882f43)
Location: init/main.c:513
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff81092ab0)
Location: kernel/fork.c:975
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff81092ab0-ffffffff81092d2c: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82899ecc)
Location: init/main.c:549
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff81096a80)
Location: kernel/fork.c:992
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff81096a80-ffffffff81096d29: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8289ceb1)
Location: init/main.c:549
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff8109d2c0)
Location: kernel/fork.c:1008
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff8109d2c0-ffffffff8109d55d: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82cc3480)
Location: init/main.c:806
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff810a4120)
Location: kernel/fork.c:1022
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff810a4120-ffffffff810a43bd: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82faf4e5)
Location: init/main.c:820
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff8109fd20)
Location: kernel/fork.c:1016
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff8109fd20-ffffffff810a0009: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff831b9506)
Location: init/main.c:821
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff810a0a30)
Location: kernel/fork.c:1022
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff810a0a30-ffffffff810a0d12: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83299860)
Location: init/main.c:836
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff810b1ea0)
Location: kernel/fork.c:1041
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff810b1ea0-ffffffff810b2185: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83447a9f)
Location: init/main.c:829
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff810c8820)
Location: kernel/fork.c:1114
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff810c8820-ffffffff810c8aeb: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83e61279)
Location: init/main.c:834
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff810e5ba0)
Location: kernel/fork.c:1125
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff810e5ba0-ffffffff810e5f23: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mm_struct *mm_init(struct mm_struct *mm, struct task_struct *p, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f12f0)
Location: kernel/fork.c:1257
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff810f12f0-ffffffff810f1796: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mm_struct *mm_init(struct mm_struct *mm, struct task_struct *p, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fa6c0)
Location: kernel/fork.c:1256
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff810fa6c0-ffffffff810faafb: mm_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffff800011430ec8)
Location: init/main.c:549
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffff8000100f1b90)
Location: kernel/fork.c:1008
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffff8000100f1b90-ffff8000100f1d04: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (c1500e5c)
Location: init/main.c:549
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (c0350a60)
Location: kernel/fork.c:1008
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
c0350a60-c0350c0c: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (c000000001343fc0)
Location: init/main.c:549
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (c0000000001372b0)
Location: kernel/fork.c:1008
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
c0000000001372b0-c00000000013757c: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffe000000b84)
Location: init/main.c:549
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffe0000bebc2)
Location: kernel/fork.c:1008
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffe0000bebc2-ffffffe0000bed36: mm_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8288aeb1)
Location: init/main.c:549
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff81096be0)
Location: kernel/fork.c:1008
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff81096be0-ffffffff81096e7d: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82888e51)
Location: init/main.c:549
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff81085660)
Location: kernel/fork.c:1008
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff81085660-ffffffff810858fd: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8289deb1)
Location: init/main.c:549
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff81096b90)
Location: kernel/fork.c:1008
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff81096b90-ffffffff81096e2d: mm_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void mm_init();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8289deb1)
Location: init/main.c:549
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/fork.c (ffffffff8109ea30)
Location: kernel/fork.c:1008
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
```
**Symbols:**

```
ffffffff8109ea30-ffffffff8109eccd: mm_init (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param added. </b>
<code>struct task_struct *p</code>
</li>
<li>
<b>Param added. </b>
<code>struct user_namespace *user_ns</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct mm_struct *</code>
</li>
</ul>
</details>
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
