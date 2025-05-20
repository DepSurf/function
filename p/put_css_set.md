# Function: <code>put_css_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void put_css_set(struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81114d40)
Location: kernel/cgroup.c:795
Inline: True
Direct callers:
  - kernel/cgroup.c:free_cgroup_ns
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_free
  - kernel/cgroup.c:copy_cgroup_ns
```
**Symbols:**

```
ffffffff81114d40-ffffffff81114d9f: put_css_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void put_css_set(struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111b550)
Location: kernel/cgroup.c:838
Inline: True
Direct callers:
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/cgroup.c:free_cgroup_ns
  - kernel/cgroup.c:cgroup_free
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
```
**Symbols:**

```
ffffffff8111b550-ffffffff8111b5b7: put_css_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void put_css_set(struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81123890)
Location: kernel/cgroup.c:841
Inline: True
Direct callers:
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/cgroup.c:free_cgroup_ns
  - kernel/cgroup.c:cgroup_free
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
```
**Symbols:**

```
ffffffff81123890-ffffffff811238f7: put_css_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112883d)
Location: kernel/cgroup/cgroup-internal.h:132
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
```
```
In kernel/cgroup/namespace.c (ffffffff81128f34)
Location: kernel/cgroup/cgroup-internal.h:132
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81134e93)
Location: kernel/cgroup/cgroup-internal.h:133
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81135bce)
Location: kernel/cgroup/cgroup-internal.h:133
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811435d6)
Location: kernel/cgroup/cgroup-internal.h:133
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff811444d3)
Location: kernel/cgroup/cgroup-internal.h:133
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f106)
Location: kernel/cgroup/cgroup-internal.h:161
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8114ffe3)
Location: kernel/cgroup/cgroup-internal.h:161
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115ae14)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8115bef6)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166ac4)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81167b16)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81177c74)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8117946e)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174974)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff811761a3)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175534)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81176d0e)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119caa4)
Location: kernel/cgroup/cgroup-internal.h:199
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8119e58e)
Location: kernel/cgroup/cgroup-internal.h:199
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811ccd73)
Location: kernel/cgroup/cgroup-internal.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff811cea00)
Location: kernel/cgroup/cgroup-internal.h:198
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81210313)
Location: kernel/cgroup/cgroup-internal.h:196
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81212280)
Location: kernel/cgroup/cgroup-internal.h:196
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81225d23)
Location: kernel/cgroup/cgroup-internal.h:196
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81227be7)
Location: kernel/cgroup/cgroup-internal.h:196
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123d9b3)
Location: kernel/cgroup/cgroup-internal.h:196
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8123f9f7)
Location: kernel/cgroup/cgroup-internal.h:196
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_css_set(struct css_set *cset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d888c)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
Direct callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffff8000101da438)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
**Symbols:**

```
ffff8000101d22d0-ffff8000101d2398: put_css_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041b4f4)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (c041cc7c)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000245aa4)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (c0000000002476e4)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000151878)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffe000152aee)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f0e4)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81160136)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81152374)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff811533a0)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115ceb4)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8115df06)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81169fd4)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8116b170)
Location: kernel/cgroup/cgroup-internal.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
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
</ul>
<b>Arch</b>
<ul>
</ul>
