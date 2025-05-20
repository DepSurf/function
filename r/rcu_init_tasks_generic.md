# Function: <code>rcu_init_tasks_generic</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_init_tasks_generic();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff82fdcd49)
Location: kernel/rcu/tasks.h:1227
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff82fdcd49-ffffffff82fdcdbe: rcu_init_tasks_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_init_tasks_generic();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff831e7aa7)
Location: kernel/rcu/tasks.h:1337
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff831e7aa7-ffffffff831e7b1c: rcu_init_tasks_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_init_tasks_generic();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff832cbba8)
Location: kernel/rcu/tasks.h:1391
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff832cbba8-ffffffff832cbc1d: rcu_init_tasks_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_init_tasks_generic();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8347f3a2)
Location: kernel/rcu/tasks.h:1760
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff8347f3a2-ffffffff8347f497: rcu_init_tasks_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_init_tasks_generic();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff83eab720)
Location: kernel/rcu/tasks.h:1925
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff83eab720-ffffffff83eab80a: rcu_init_tasks_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_init_tasks_generic();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff836d06e0)
Location: kernel/rcu/tasks.h:1960
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff836d06e0-ffffffff836d07ca: rcu_init_tasks_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_init_tasks_generic();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff83901b40)
Location: kernel/rcu/tasks.h:2089
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff83901b40-ffffffff83901c6c: rcu_init_tasks_generic (STB_GLOBAL)
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
