# Function: <code>rcu_check_callbacks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rcu_check_callbacks(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e7e50)
Location: kernel/rcu/tree.c:2751
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810e7e50-ffffffff810e8634: rcu_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rcu_check_callbacks(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ee090)
Location: kernel/rcu/tree.c:2834
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810ee090-ffffffff810ee8cb: rcu_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rcu_check_callbacks(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5170)
Location: kernel/rcu/tree.c:2837
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810f5170-ffffffff810f59b8: rcu_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_check_callbacks(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5ef0)
Location: kernel/rcu/tree.c:2828
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810f5ef0-ffffffff810f6759: rcu_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_check_callbacks(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ffd90)
Location: kernel/rcu/tree.c:2809
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810ffd90-ffffffff81100682: rcu_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void rcu_check_callbacks(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2613
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8110901d-ffffffff8110941e: rcu_check_callbacks.cold.78 (STB_LOCAL)
ffffffff811080b0-ffffffff811084df: rcu_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void rcu_check_callbacks(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2516
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81114864-ffffffff81114be9: rcu_check_callbacks.cold.75 (STB_LOCAL)
ffffffff811135d0-ffffffff81113958: rcu_check_callbacks (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
