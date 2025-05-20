# Function: <code>apply_workqueue_attrs_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109c3f0)
Location: kernel/workqueue.c:3610
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffff8109c3f0-ffffffff8109c473: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109f5f0)
Location: kernel/workqueue.c:3711
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffff8109f5f0-ffffffff8109f66e: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a44f0)
Location: kernel/workqueue.c:3739
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffff810a44f0-ffffffff810a456e: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a1620)
Location: kernel/workqueue.c:3744
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffff810a1620-ffffffff810a1687: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a7e80)
Location: kernel/workqueue.c:3755
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffff810a7e80-ffffffff810a7eea: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ae9e0)
Location: kernel/workqueue.c:3827
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffff810ae9e0-ffffffff810aea49: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b7b40)
Location: kernel/workqueue.c:3850
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffff810b7b40-ffffffff810b7ba9: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3991
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810bd580-ffffffff810bd5e1: apply_workqueue_attrs_locked (STB_LOCAL)
ffffffff810bf0b6-ffffffff810bf0e6: apply_workqueue_attrs_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3c00)
Location: kernel/workqueue.c:4000
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffff810c3c00-ffffffff810c3c69: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810cb4f0)
Location: kernel/workqueue.c:4009
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
```
**Symbols:**

```
ffffffff810cb4f0-ffffffff810cb55b: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6620)
Location: kernel/workqueue.c:4022
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
```
**Symbols:**

```
ffffffff810c6620-ffffffff810c668b: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7f60)
Location: kernel/workqueue.c:4029
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
```
**Symbols:**

```
ffffffff810c7f60-ffffffff810c7fcb: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810dacf0)
Location: kernel/workqueue.c:4068
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810dacf0-ffffffff810dad5b: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f4480)
Location: kernel/workqueue.c:4051
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810f4480-ffffffff810f4508: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81116700)
Location: kernel/workqueue.c:4060
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff81116700-ffffffff8111678f: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81123500)
Location: kernel/workqueue.c:4388
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff81123500-ffffffff8112358f: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112d580)
Location: kernel/workqueue.c:4417
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_affinity_strict_store
  - kernel/workqueue.c:wq_affn_scope_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
```
**Symbols:**

```
ffffffff8112d580-ffffffff8112d610: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010121978)
Location: kernel/workqueue.c:4000
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffff800010121978-ffff800010121a0c: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c03753e4)
Location: kernel/workqueue.c:4000
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
c03753e4-c0375484: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016b130)
Location: kernel/workqueue.c:4000
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
c00000000016b130-c00000000016b1e4: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000da5e4)
Location: kernel/workqueue.c:4000
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffe0000da5e4-ffffffe0000da66a: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bdf70)
Location: kernel/workqueue.c:4000
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffff810bdf70-ffffffff810bdfd9: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ac7a0)
Location: kernel/workqueue.c:4000
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffff810ac7a0-ffffffff810ac809: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd4d0)
Location: kernel/workqueue.c:4000
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffff810bd4d0-ffffffff810bd539: apply_workqueue_attrs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int apply_workqueue_attrs_locked(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5850)
Location: kernel/workqueue.c:4000
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:apply_workqueue_attrs
```
**Symbols:**

```
ffffffff810c5850-ffffffff810c58b9: apply_workqueue_attrs_locked (STB_LOCAL)
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
