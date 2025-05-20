# Function: <code>show_one_workqueue</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void show_one_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4795
Inline: False
Direct callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff81e54c45-ffffffff81e54ccb: show_one_workqueue.cold (STB_LOCAL)
ffffffff810f4a90-ffffffff810f4afa: show_one_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void show_one_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81116e80)
Location: kernel/workqueue.c:4804
Inline: False
Direct callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff81116e80-ffffffff81116f68: show_one_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void show_one_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81123e10)
Location: kernel/workqueue.c:5176
Inline: False
Direct callers:
  - kernel/workqueue.c:show_freezable_workqueues
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff81123e10-ffffffff81123ef8: show_one_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void show_one_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112e490)
Location: kernel/workqueue.c:5199
Inline: False
Direct callers:
  - kernel/workqueue.c:show_freezable_workqueues
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff8112e490-ffffffff8112e578: show_one_workqueue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
