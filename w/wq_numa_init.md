# Function: <code>wq_numa_init</code>

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
In kernel/workqueue.c (ffffffff81f7c2e6)
Location: kernel/workqueue.c:5180
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
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
In kernel/workqueue.c (ffffffff81fa5089)
Location: kernel/workqueue.c:5416
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
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
In kernel/workqueue.c (ffffffff81fe09ee)
Location: kernel/workqueue.c:5446
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
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
In kernel/workqueue.c (ffffffff820c183d)
Location: kernel/workqueue.c:5489
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
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
In kernel/workqueue.c (ffffffff826c9a2e)
Location: kernel/workqueue.c:5518
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wq_numa_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff826f3c08)
Location: kernel/workqueue.c:5635
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff826f3c08-ffffffff826f3d69: wq_numa_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wq_numa_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff828aa9f0)
Location: kernel/workqueue.c:5658
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff828aa9f0-ffffffff828aab51: wq_numa_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wq_numa_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff828c31e7)
Location: kernel/workqueue.c:5805
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff828c31e7-ffffffff828c333a: wq_numa_init (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff828cb7e9)
Location: kernel/workqueue.c:5839
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wq_numa_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff82ced786)
Location: kernel/workqueue.c:5862
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff82ced786-ffffffff82ced8e2: wq_numa_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wq_numa_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff82fd9de0)
Location: kernel/workqueue.c:5883
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff82fd9de0-ffffffff82fd9f3c: wq_numa_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wq_numa_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff831e4797)
Location: kernel/workqueue.c:5892
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff831e4797-ffffffff831e48dc: wq_numa_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wq_numa_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff832c8453)
Location: kernel/workqueue.c:5952
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff832c8453-ffffffff832c8625: wq_numa_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wq_numa_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8347b55f)
Location: kernel/workqueue.c:5937
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff8347b55f-ffffffff8347b72e: wq_numa_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wq_numa_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff83ea63e0)
Location: kernel/workqueue.c:5935
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff83ea63e0-ffffffff83ea6627: wq_numa_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wq_numa_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff836caba0)
Location: kernel/workqueue.c:6396
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff836caba0-ffffffff836cade7: wq_numa_init (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void wq_numa_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800011442ed4)
Location: kernel/workqueue.c:5839
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffff800011442ed4-ffff800011443088: wq_numa_init (STB_LOCAL)
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
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:5839
Inline: True
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
In kernel/workqueue.c (c000000001366e5c)
Location: kernel/workqueue.c:5839
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
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
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:5839
Inline: True
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
In kernel/workqueue.c (ffffffff828b45dc)
Location: kernel/workqueue.c:5839
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
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
In kernel/workqueue.c (ffffffff828ac75d)
Location: kernel/workqueue.c:5839
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
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
In kernel/workqueue.c (ffffffff828c74db)
Location: kernel/workqueue.c:5839
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
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
In kernel/workqueue.c (ffffffff828cc832)
Location: kernel/workqueue.c:5839
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
</ul>
<b>Arch</b>
<ul>
</ul>
