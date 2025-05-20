# Function: <code>kmem_dump_obj</code>

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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void kmem_dump_obj(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:582
Inline: False
```
**Symbols:**

```
ffffffff81bd90b3-ffffffff81bd91d7: kmem_dump_obj.cold (STB_LOCAL)
ffffffff8128d4c0-ffffffff8128d5a8: kmem_dump_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void kmem_dump_obj(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:586
Inline: False
```
**Symbols:**

```
ffffffff81cbb177-ffffffff81cbb366: kmem_dump_obj.cold (STB_LOCAL)
ffffffff812cc960-ffffffff812cca50: kmem_dump_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void kmem_dump_obj(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:584
Inline: False
```
**Symbols:**

```
ffffffff81e6cd81-ffffffff81e6cfa7: kmem_dump_obj.cold (STB_LOCAL)
ffffffff8132bc80-ffffffff8132bdc1: kmem_dump_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kmem_dump_obj(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a1410)
Location: mm/slab_common.c:573
Inline: False
```
**Symbols:**

```
ffffffff813a1410-ffffffff813a1793: kmem_dump_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kmem_dump_obj(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d4680)
Location: mm/slab_common.c:573
Inline: False
```
**Symbols:**

```
ffffffff813d4680-ffffffff813d4a03: kmem_dump_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool kmem_dump_obj(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fe230)
Location: mm/slab_common.c:548
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff813fe230-ffffffff813fe59a: kmem_dump_obj (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
</ul>
