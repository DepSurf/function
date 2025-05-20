# Function: <code>check_all_holdout_tasks</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void check_all_holdout_tasks(struct list_head *hop, bool needreport, bool *firstreport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:450
Inline: False
```
**Symbols:**

```
ffffffff81130770-ffffffff81130897: check_all_holdout_tasks (STB_LOCAL)
ffffffff811314ff-ffffffff8113157a: check_all_holdout_tasks.cold (STB_LOCAL)
```
</details>
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
void check_all_holdout_tasks(struct list_head *hop, bool needreport, bool *firstreport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:838
Inline: False
```
**Symbols:**

```
ffffffff811743c0-ffffffff81174547: check_all_holdout_tasks (STB_LOCAL)
ffffffff81e5e63a-ffffffff81e5e66d: check_all_holdout_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void check_all_holdout_tasks(struct list_head *hop, bool needreport, bool *firstreport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:886
Inline: False
```
**Symbols:**

```
ffffffff811aa2e0-ffffffff811aa489: check_all_holdout_tasks (STB_LOCAL)
ffffffff82059d70-ffffffff82059d8b: check_all_holdout_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void check_all_holdout_tasks(struct list_head *hop, bool needreport, bool *firstreport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:908
Inline: False
```
**Symbols:**

```
ffffffff811bc210-ffffffff811bc3b9: check_all_holdout_tasks (STB_LOCAL)
ffffffff820d8549-ffffffff820d8564: check_all_holdout_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void check_all_holdout_tasks(struct list_head *hop, bool needreport, bool *firstreport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cd070)
Location: kernel/rcu/tasks.h:1001
Inline: False
```
**Symbols:**

```
ffffffff811cd070-ffffffff811cd0e7: check_all_holdout_tasks (STB_LOCAL)
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
