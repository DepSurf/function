# Function: <code>apply_wqattrs_cleanup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81099710)
Location: kernel/workqueue.c:3488
Inline: False
Direct callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
```
**Symbols:**

```
ffffffff81099710-ffffffff810997ac: apply_wqattrs_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109cca0)
Location: kernel/workqueue.c:3589
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff8109cca0-ffffffff8109cd3c: apply_wqattrs_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3920)
Location: kernel/workqueue.c:3617
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810a3920-ffffffff810a39c1: apply_wqattrs_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810a2a94)
Location: kernel/workqueue.c:3622
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff8109ee10-ffffffff8109eeb4: apply_wqattrs_cleanup.part.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810a93c4)
Location: kernel/workqueue.c:3633
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810a5650-ffffffff810a56f4: apply_wqattrs_cleanup.part.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ac2f0)
Location: kernel/workqueue.c:3706
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810ac2f0-ffffffff810ac39e: apply_wqattrs_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b51d0)
Location: kernel/workqueue.c:3729
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810b51d0-ffffffff810b527e: apply_wqattrs_cleanup (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810be763)
Location: kernel/workqueue.c:3870
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810bafe0-ffffffff810bb084: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4d13)
Location: kernel/workqueue.c:3879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810c1240-ffffffff810c12e4: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810cb7ff)
Location: kernel/workqueue.c:3888
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_apply_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_apply_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810ca120-ffffffff810ca224: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c692f)
Location: kernel/workqueue.c:3901
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_apply_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_apply_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810c5250-ffffffff810c5354: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c935f)
Location: kernel/workqueue.c:3908
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810c6b50-ffffffff810c6c41: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810dc05b)
Location: kernel/workqueue.c:3947
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810d9860-ffffffff810d98ff: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810f579a)
Location: kernel/workqueue.c:3930
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810f1950-ffffffff810f19ff: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff81117c93)
Location: kernel/workqueue.c:3937
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff81114f80-ffffffff8111501f: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff81124e63)
Location: kernel/workqueue.c:4265
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff81120f50-ffffffff81120fef: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff8112da19)
Location: kernel/workqueue.c:4319
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_apply_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_apply_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff8112bd00-ffffffff8112bdee: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffff8000101231e4)
Location: kernel/workqueue.c:3879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffff80001011f1d0-ffff80001011f27c: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c03724e8)
Location: kernel/workqueue.c:3879
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
c03724e8-c0372540: apply_wqattrs_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (c00000000016d084)
Location: kernel/workqueue.c:3879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
c0000000001679d0-c000000000167adc: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d8be0)
Location: kernel/workqueue.c:3879
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffe0000d8be0-ffffffe0000d8c30: apply_wqattrs_cleanup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810bf083)
Location: kernel/workqueue.c:3879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810bb5b0-ffffffff810bb654: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810ad8a3)
Location: kernel/workqueue.c:3879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810aa070-ffffffff810aa114: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810be5e3)
Location: kernel/workqueue.c:3879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810bab10-ffffffff810babb4: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6953)
Location: kernel/workqueue.c:3879
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
Direct callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_workqueue_attrs_locked
  - kernel/workqueue.c:apply_wqattrs_prepare
```
**Symbols:**

```
ffffffff810c35b0-ffffffff810c3654: apply_wqattrs_cleanup.part.0 (STB_LOCAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
