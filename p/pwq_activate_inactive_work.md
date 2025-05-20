# Function: <code>pwq_activate_inactive_work</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pwq_activate_inactive_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d6fb0)
Location: kernel/workqueue.c:1165
Inline: False
Direct callers:
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810d6fb0-ffffffff810d7096: pwq_activate_inactive_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pwq_activate_inactive_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f0ba0)
Location: kernel/workqueue.c:1161
Inline: False
Direct callers:
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810f0ba0-ffffffff810f0cb6: pwq_activate_inactive_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pwq_activate_inactive_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81112860)
Location: kernel/workqueue.c:1161
Inline: False
Direct callers:
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff81112860-ffffffff81112976: pwq_activate_inactive_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pwq_activate_inactive_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111ee60)
Location: kernel/workqueue.c:1359
Inline: False
Direct callers:
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff8111ee60-ffffffff8111ef76: pwq_activate_inactive_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pwq_activate_inactive_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81128410)
Location: kernel/workqueue.c:1456
Inline: False
Direct callers:
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff81128410-ffffffff81128526: pwq_activate_inactive_work (STB_LOCAL)
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
