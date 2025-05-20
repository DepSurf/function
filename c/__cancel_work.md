# Function: <code>__cancel_work</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __cancel_work(struct work_struct *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0f80)
Location: kernel/workqueue.c:2991
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:cancel_work
```
**Symbols:**

```
ffffffff810a0f80-ffffffff810a104f: __cancel_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __cancel_work(struct work_struct *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e4f0)
Location: kernel/workqueue.c:2990
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:cancel_work
```
**Symbols:**

```
ffffffff8109e4f0-ffffffff8109e58e: __cancel_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __cancel_work(struct work_struct *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a4d40)
Location: kernel/workqueue.c:3004
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:cancel_work
```
**Symbols:**

```
ffffffff810a4d40-ffffffff810a4dd6: __cancel_work (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810ac5a0)
Location: kernel/workqueue.c:3086
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (ffffffff810b5480)
Location: kernel/workqueue.c:3109
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (ffffffff810bb2a2)
Location: kernel/workqueue.c:3209
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (ffffffff810c1500)
Location: kernel/workqueue.c:3218
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ca960)
Location: kernel/workqueue.c:3215
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5a90)
Location: kernel/workqueue.c:3221
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (ffffffff810c73c0)
Location: kernel/workqueue.c:3222
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (ffffffff810da0e0)
Location: kernel/workqueue.c:3261
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (ffffffff810f1850)
Location: kernel/workqueue.c:3244
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __cancel_work(struct work_struct *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811147f0)
Location: kernel/workqueue.c:3242
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:cancel_work
```
**Symbols:**

```
ffffffff811147f0-ffffffff811148af: __cancel_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __cancel_work(struct work_struct *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81120780)
Location: kernel/workqueue.c:3558
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:cancel_work
```
**Symbols:**

```
ffffffff81120780-ffffffff8112083f: __cancel_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __cancel_work(struct work_struct *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81129110)
Location: kernel/workqueue.c:3579
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:cancel_work
```
**Symbols:**

```
ffffffff81129110-ffffffff811291cf: __cancel_work (STB_LOCAL)
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
In kernel/workqueue.c (ffff80001011f784)
Location: kernel/workqueue.c:3218
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (c03727f8)
Location: kernel/workqueue.c:3218
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (c000000000166840)
Location: kernel/workqueue.c:3218
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (ffffffe0000d9bb8)
Location: kernel/workqueue.c:3218
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (ffffffff810bb870)
Location: kernel/workqueue.c:3218
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (ffffffff810aa310)
Location: kernel/workqueue.c:3218
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (ffffffff810badd0)
Location: kernel/workqueue.c:3218
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
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
In kernel/workqueue.c (ffffffff810c4290)
Location: kernel/workqueue.c:3218
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
