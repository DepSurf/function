# Function: <code>free_workqueue_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81097370)
Location: kernel/workqueue.c:2996
Inline: True
Inline callers:
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff8109b510-ffffffff8109b526: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109f74d)
Location: kernel/workqueue.c:3096
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
```
**Symbols:**

```
ffffffff8109eb00-ffffffff8109eb16: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3860)
Location: kernel/workqueue.c:3122
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
```
**Symbols:**

```
ffffffff810a3860-ffffffff810a3887: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810a1767)
Location: kernel/workqueue.c:3121
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
```
**Symbols:**

```
ffffffff8109dd10-ffffffff8109dd31: free_workqueue_attrs.part.31 (STB_LOCAL)
ffffffff810a0b10-ffffffff810a0b27: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810a7fc7)
Location: kernel/workqueue.c:3135
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
```
**Symbols:**

```
ffffffff810a4430-ffffffff810a4451: free_workqueue_attrs.part.32 (STB_LOCAL)
ffffffff810a7390-ffffffff810a73a7: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810aeb77)
Location: kernel/workqueue.c:3209
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
```
**Symbols:**

```
ffffffff810aa990-ffffffff810aa9b1: free_workqueue_attrs.part.36 (STB_LOCAL)
ffffffff810adf30-ffffffff810adf46: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810b7cd7)
Location: kernel/workqueue.c:3232
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
```
**Symbols:**

```
ffffffff810b3b10-ffffffff810b3b31: free_workqueue_attrs.part.37 (STB_LOCAL)
ffffffff810b7040-ffffffff810b7056: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd767)
Location: kernel/workqueue.c:3332
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
```
**Symbols:**

```
ffffffff810b9760-ffffffff810b9783: free_workqueue_attrs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3d47)
Location: kernel/workqueue.c:3341
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
```
**Symbols:**

```
ffffffff810bfc90-ffffffff810bfcb3: free_workqueue_attrs.part.0 (STB_LOCAL)
ffffffff810c3150-ffffffff810c3166: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810cba62)
Location: kernel/workqueue.c:3338
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/padata.c:__padata_set_cpumasks
```
**Symbols:**

```
ffffffff810cabc0-ffffffff810cabeb: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6cc2)
Location: kernel/workqueue.c:3344
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:__padata_set_cpumasks
```
**Symbols:**

```
ffffffff810c5cf0-ffffffff810c5d1b: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c8467)
Location: kernel/workqueue.c:3345
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
ffffffff810c7630-ffffffff810c765b: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810db007)
Location: kernel/workqueue.c:3384
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
ffffffff810da390-ffffffff810da3bb: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f47fa)
Location: kernel/workqueue.c:3367
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff810f3aa0-ffffffff810f3ad6: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81116b67)
Location: kernel/workqueue.c:3374
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81115c60-ffffffff81115c96: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81123a8d)
Location: kernel/workqueue.c:3690
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811229c0-ffffffff811229f6: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112e1a7)
Location: kernel/workqueue.c:3711
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_affinity_strict_store
  - kernel/workqueue.c:wq_affinity_strict_store
  - kernel/workqueue.c:wq_affn_scope_store
  - kernel/workqueue.c:wq_affn_scope_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff8112c990-ffffffff8112c9cf: free_workqueue_attrs (STB_GLOBAL)
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
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010121af4)
Location: kernel/workqueue.c:3341
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
Direct callers:
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
ffff800010120f08-ffff800010120f38: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0375548)
Location: kernel/workqueue.c:3341
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
Direct callers:
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
c0374e60-c0374e84: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016b318)
Location: kernel/workqueue.c:3341
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
Direct callers:
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
c00000000016a3e0-c00000000016a41c: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000da750)
Location: kernel/workqueue.c:3341
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
Direct callers:
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
ffffffe0000d9e88-ffffffe0000d9eb4: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810be0b7)
Location: kernel/workqueue.c:3341
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
```
**Symbols:**

```
ffffffff810ba000-ffffffff810ba023: free_workqueue_attrs.part.0 (STB_LOCAL)
ffffffff810bd4c0-ffffffff810bd4d6: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810ac8e7)
Location: kernel/workqueue.c:3341
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
```
**Symbols:**

```
ffffffff810a8940-ffffffff810a8963: free_workqueue_attrs.part.0 (STB_LOCAL)
ffffffff810abcf0-ffffffff810abd06: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd617)
Location: kernel/workqueue.c:3341
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
```
**Symbols:**

```
ffffffff810b9560-ffffffff810b9583: free_workqueue_attrs.part.0 (STB_LOCAL)
ffffffff810bca20-ffffffff810bca36: free_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5997)
Location: kernel/workqueue.c:3341
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:rcu_free_pool
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:alloc_workqueue_attrs
```
**Symbols:**

```
ffffffff810c2570-ffffffff810c2593: free_workqueue_attrs.part.0 (STB_LOCAL)
ffffffff810c4da0-ffffffff810c4db6: free_workqueue_attrs (STB_GLOBAL)
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
