# Function: <code>put_css_set_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81114b70)
Location: kernel/cgroup.c:765
Inline: True
Direct callers:
  - kernel/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:css_task_iter_end
```
**Symbols:**

```
ffffffff81114b70-ffffffff81114d37: put_css_set_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111b390)
Location: kernel/cgroup.c:808
Inline: True
Direct callers:
  - kernel/cgroup.c:css_task_iter_end
  - kernel/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup.c:cgroup_taskset_migrate
```
**Symbols:**

```
ffffffff8111b390-ffffffff8111b544: put_css_set_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811236d0)
Location: kernel/cgroup.c:811
Inline: True
Direct callers:
  - kernel/cgroup.c:css_task_iter_end
  - kernel/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup.c:cgroup_taskset_migrate
```
**Symbols:**

```
ffffffff811236d0-ffffffff81123884: put_css_set_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81124010)
Location: kernel/cgroup/cgroup.c:729
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff81124010-ffffffff811241e1: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112fa00)
Location: kernel/cgroup/cgroup.c:856
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff8112fa00-ffffffff8112fc42: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113e0c0)
Location: kernel/cgroup/cgroup.c:859
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff8113e0c0-ffffffff8113e304: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81149af0)
Location: kernel/cgroup/cgroup.c:894
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff81149af0-ffffffff81149d34: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81155150)
Location: kernel/cgroup/cgroup.c:934
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff81155150-ffffffff8115539d: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81160d80)
Location: kernel/cgroup/cgroup.c:934
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff81160d80-ffffffff81160fcd: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811723d0)
Location: kernel/cgroup/cgroup.c:926
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff81172410-ffffffff81172650: put_css_set_locked.part.0 (STB_LOCAL)
ffffffff811723d0-ffffffff81172408: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116f070)
Location: kernel/cgroup/cgroup.c:923
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff8116f0b0-ffffffff8116f30e: put_css_set_locked.part.0 (STB_LOCAL)
ffffffff8116f070-ffffffff8116f0a8: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116fca0)
Location: kernel/cgroup/cgroup.c:923
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff8116fce0-ffffffff8116ff3b: put_css_set_locked.part.0 (STB_LOCAL)
ffffffff8116fca0-ffffffff8116fcd8: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81196060)
Location: kernel/cgroup/cgroup.c:954
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff811960a0-ffffffff81196379: put_css_set_locked.part.0 (STB_LOCAL)
ffffffff81196060-ffffffff81196098: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c5f60)
Location: kernel/cgroup/cgroup.c:956
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff811c5fc0-ffffffff811c629d: put_css_set_locked.part.0 (STB_LOCAL)
ffffffff811c5f60-ffffffff811c5fbc: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81208a10)
Location: kernel/cgroup/cgroup.c:961
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff81208a80-ffffffff81208d5d: put_css_set_locked.part.0 (STB_LOCAL)
ffffffff81208a10-ffffffff81208a6c: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121e130)
Location: kernel/cgroup/cgroup.c:945
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff8121e1a0-ffffffff8121e47b: put_css_set_locked.part.0 (STB_LOCAL)
ffffffff8121e130-ffffffff8121e18c: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81235d90)
Location: kernel/cgroup/cgroup.c:925
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff81235e00-ffffffff812360db: put_css_set_locked.part.0 (STB_LOCAL)
ffffffff81235d90-ffffffff81235dec: put_css_set_locked (STB_GLOBAL)
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
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d2078)
Location: kernel/cgroup/cgroup.c:934
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffff8000101d2078-ffff8000101d22d0: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0414f54)
Location: kernel/cgroup/cgroup.c:934
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
c0414f54-c04151f0: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023cbe0)
Location: kernel/cgroup/cgroup.c:934
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
c00000000023cbe0-c00000000023cf70: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe0001518a4)
Location: kernel/cgroup/cgroup.c:934
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffe00014ba60-ffffffe00014bc66: put_css_set_locked.part.0 (STB_LOCAL)
ffffffe00014ba24-ffffffe00014ba60: put_css_set_locked (STB_GLOBAL)
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
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811593a0)
Location: kernel/cgroup/cgroup.c:934
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff811593a0-ffffffff811595ed: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114c6b0)
Location: kernel/cgroup/cgroup.c:934
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff8114c6b0-ffffffff8114c8fd: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157170)
Location: kernel/cgroup/cgroup.c:934
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff81157170-ffffffff811573bd: put_css_set_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_css_set_locked(struct css_set *cset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81164190)
Location: kernel/cgroup/cgroup.c:934
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffffffff81164190-ffffffff81164411: put_css_set_locked (STB_GLOBAL)
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
