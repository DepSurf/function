# Function: <code>mem_dump_obj</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_dump_obj(void *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/util.c (ffffffff81282894)
Location: mm/util.c:988
Inline: True
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
**Symbols:**

```
ffffffff81bd8c6f-ffffffff81bd8cad: mem_dump_obj.cold (STB_LOCAL)
ffffffff81282860-ffffffff812828a9: mem_dump_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_dump_obj(void *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/util.c (ffffffff812c0914)
Location: mm/util.c:1019
Inline: True
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
**Symbols:**

```
ffffffff81cbaa86-ffffffff81cbaac4: mem_dump_obj.cold (STB_LOCAL)
ffffffff812c08e0-ffffffff812c0929: mem_dump_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_dump_obj(void *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/util.c (ffffffff8131d517)
Location: mm/util.c:1144
Inline: True
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
**Symbols:**

```
ffffffff81e6c3a4-ffffffff81e6c3e2: mem_dump_obj.cold (STB_LOCAL)
ffffffff8131d4d0-ffffffff8131d52c: mem_dump_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mem_dump_obj(void *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81391130)
Location: mm/util.c:1039
Inline: True
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
**Symbols:**

```
ffffffff81391130-ffffffff813911c8: mem_dump_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mem_dump_obj(void *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c3ae0)
Location: mm/util.c:1062
Inline: True
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
**Symbols:**

```
ffffffff813c3ae0-ffffffff813c3b8d: mem_dump_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mem_dump_obj(void *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ee6a0)
Location: mm/util.c:1070
Inline: True
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
**Symbols:**

```
ffffffff813ee6a0-ffffffff813ee738: mem_dump_obj (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
