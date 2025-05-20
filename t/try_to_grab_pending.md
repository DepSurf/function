# Function: <code>try_to_grab_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81098780)
Location: kernel/workqueue.c:1183
Inline: True
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff81098780-ffffffff810988d2: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109bd40)
Location: kernel/workqueue.c:1204
Inline: True
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff8109bd40-ffffffff8109be92: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0d80)
Location: kernel/workqueue.c:1206
Inline: True
Direct callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810a0d80-ffffffff810a0ed2: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e300)
Location: kernel/workqueue.c:1206
Inline: True
Direct callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff8109e300-ffffffff8109e450: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a4b60)
Location: kernel/workqueue.c:1208
Inline: True
Direct callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810a4b60-ffffffff810a4ca0: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ac440)
Location: kernel/workqueue.c:1206
Inline: True
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810ac440-ffffffff810ac577: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b5320)
Location: kernel/workqueue.c:1226
Inline: True
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810b5320-ffffffff810b5457: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bb130)
Location: kernel/workqueue.c:1234
Inline: True
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810bb130-ffffffff810bb273: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c1390)
Location: kernel/workqueue.c:1235
Inline: True
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810c1390-ffffffff810c14d3: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ca550)
Location: kernel/workqueue.c:1232
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810ca550-ffffffff810ca6c2: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5680)
Location: kernel/workqueue.c:1235
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810c5680-ffffffff810c5800: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6f90)
Location: kernel/workqueue.c:1236
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810c6f90-ffffffff810c7113: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d9cc0)
Location: kernel/workqueue.c:1262
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810d9cc0-ffffffff810d9e3c: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f16a0)
Location: kernel/workqueue.c:1258
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810f16a0-ffffffff810f1826: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81114640)
Location: kernel/workqueue.c:1258
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff81114640-ffffffff811147d5: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811205d0)
Location: kernel/workqueue.c:1456
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff811205d0-ffffffff81120765: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81128620)
Location: kernel/workqueue.c:1553
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff81128620-ffffffff811287b5: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011f378)
Location: kernel/workqueue.c:1235
Inline: True
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffff80001011f378-ffff80001011f554: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c037261c)
Location: kernel/workqueue.c:1235
Inline: True
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
c037261c-c03727cc: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0000000001664d0)
Location: kernel/workqueue.c:1235
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
c0000000001664d0-c000000000166728: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d97f4)
Location: kernel/workqueue.c:1235
Inline: True
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffe0000d97f4-ffffffe0000d9984: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bb700)
Location: kernel/workqueue.c:1235
Inline: True
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810bb700-ffffffff810bb843: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aa1c0)
Location: kernel/workqueue.c:1235
Inline: True
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810aa1c0-ffffffff810aa2ee: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bac60)
Location: kernel/workqueue.c:1235
Inline: True
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810bac60-ffffffff810bada3: try_to_grab_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int try_to_grab_pending(struct work_struct *work, bool is_dwork, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3ea0)
Location: kernel/workqueue.c:1235
Inline: True
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:mod_delayed_work_on
```
**Symbols:**

```
ffffffff810c3ea0-ffffffff810c3ff2: try_to_grab_pending (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
