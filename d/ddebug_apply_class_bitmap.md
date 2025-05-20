# Function: <code>ddebug_apply_class_bitmap</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ddebug_apply_class_bitmap(const struct ddebug_class_param *dcp, long unsigned int *new_bits, long unsigned int *old_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8188e990)
Location: lib/dynamic_debug.c:600
Inline: False
Direct callers:
  - lib/dynamic_debug.c:param_set_dyndbg_classes
  - lib/dynamic_debug.c:param_set_dyndbg_classes
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
```
**Symbols:**

```
ffffffff8188e990-ffffffff8188eb02: ddebug_apply_class_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ddebug_apply_class_bitmap(const struct ddebug_class_param *dcp, long unsigned int *new_bits, long unsigned int *old_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff818d0f00)
Location: lib/dynamic_debug.c:600
Inline: False
Direct callers:
  - lib/dynamic_debug.c:param_set_dyndbg_classes
  - lib/dynamic_debug.c:param_set_dyndbg_classes
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
```
**Symbols:**

```
ffffffff818d0f00-ffffffff818d106f: ddebug_apply_class_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ddebug_apply_class_bitmap(const struct ddebug_class_param *dcp, long unsigned int *new_bits, long unsigned int *old_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81922ef0)
Location: lib/dynamic_debug.c:601
Inline: False
Direct callers:
  - lib/dynamic_debug.c:param_set_dyndbg_classes
  - lib/dynamic_debug.c:param_set_dyndbg_classes
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
```
**Symbols:**

```
ffffffff81922ef0-ffffffff8192305f: ddebug_apply_class_bitmap (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
