# Function: <code>alloc_and_link_pwqs</code>

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
In kernel/workqueue.c (ffffffff8109d6d9)
Location: kernel/workqueue.c:3750
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
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
In kernel/workqueue.c (ffffffff810a0d35)
Location: kernel/workqueue.c:3848
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
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
In kernel/workqueue.c (ffffffff810a5e05)
Location: kernel/workqueue.c:3876
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
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
In kernel/workqueue.c (ffffffff810a2e5e)
Location: kernel/workqueue.c:3885
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
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
In kernel/workqueue.c (ffffffff810a978e)
Location: kernel/workqueue.c:3896
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
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
In kernel/workqueue.c (ffffffff810afef3)
Location: kernel/workqueue.c:3969
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
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
In kernel/workqueue.c (ffffffff810b9063)
Location: kernel/workqueue.c:3992
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
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
In kernel/workqueue.c (ffffffff810beb84)
Location: kernel/workqueue.c:4132
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
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
In kernel/workqueue.c (ffffffff810c5128)
Location: kernel/workqueue.c:4145
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int alloc_and_link_pwqs(struct workqueue_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810cb560)
Location: kernel/workqueue.c:4154
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810cb560-ffffffff810cb74d: alloc_and_link_pwqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int alloc_and_link_pwqs(struct workqueue_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6690)
Location: kernel/workqueue.c:4167
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c6690-ffffffff810c687d: alloc_and_link_pwqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int alloc_and_link_pwqs(struct workqueue_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7fd0)
Location: kernel/workqueue.c:4174
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c7fd0-ffffffff810c81bd: alloc_and_link_pwqs (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810dc480)
Location: kernel/workqueue.c:4213
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
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
In kernel/workqueue.c (ffffffff810f5bb7)
Location: kernel/workqueue.c:4196
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
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
In kernel/workqueue.c (ffffffff811180f7)
Location: kernel/workqueue.c:4205
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
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
In kernel/workqueue.c (ffffffff81125329)
Location: kernel/workqueue.c:4533
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int alloc_and_link_pwqs(struct workqueue_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112d620)
Location: kernel/workqueue.c:4551
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff8112d620-ffffffff8112d94a: alloc_and_link_pwqs (STB_LOCAL)
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
In kernel/workqueue.c (ffff8000101235e4)
Location: kernel/workqueue.c:4145
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
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
In kernel/workqueue.c (c0376ee0)
Location: kernel/workqueue.c:4145
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
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
In kernel/workqueue.c (c00000000016d5bc)
Location: kernel/workqueue.c:4145
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
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
In kernel/workqueue.c (ffffffe0000dbd2c)
Location: kernel/workqueue.c:4145
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
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
In kernel/workqueue.c (ffffffff810bf498)
Location: kernel/workqueue.c:4145
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
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
In kernel/workqueue.c (ffffffff810adcb8)
Location: kernel/workqueue.c:4145
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
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
In kernel/workqueue.c (ffffffff810be9f8)
Location: kernel/workqueue.c:4145
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
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
In kernel/workqueue.c (ffffffff810c6d68)
Location: kernel/workqueue.c:4145
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
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
</ul>
