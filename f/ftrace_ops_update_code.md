# Function: <code>ftrace_ops_update_code</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ftrace_ops_update_code(struct ftrace_ops *ops, struct ftrace_ops_hash *old_hash);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81143b50)
Location: kernel/trace/ftrace.c:4085
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_regex_release
```
**Symbols:**

```
ffffffff81143b50-ffffffff81143be9: ftrace_ops_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ftrace_ops_update_code(struct ftrace_ops *ops, struct ftrace_ops_hash *old_hash);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114b950)
Location: kernel/trace/ftrace.c:4122
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
ffffffff8114b950-ffffffff8114b9e9: ftrace_ops_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ftrace_ops_update_code(struct ftrace_ops *ops, struct ftrace_ops_hash *old_hash);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81155840)
Location: kernel/trace/ftrace.c:4151
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
ffffffff81155840-ffffffff811558d9: ftrace_ops_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81158195)
Location: kernel/trace/ftrace.c:3882
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81164c95)
Location: kernel/trace/ftrace.c:3850
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811739a5)
Location: kernel/trace/ftrace.c:3839
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811815f5)
Location: kernel/trace/ftrace.c:3798
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118e3f9)
Location: kernel/trace/ftrace.c:3834
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119a379)
Location: kernel/trace/ftrace.c:3858
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aff93)
Location: kernel/trace/ftrace.c:3985
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ad953)
Location: kernel/trace/ftrace.c:4063
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ae4ad)
Location: kernel/trace/ftrace.c:4063
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d8293)
Location: kernel/trace/ftrace.c:4064
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120db4b)
Location: kernel/trace/ftrace.c:4204
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81256b3a)
Location: kernel/trace/ftrace.c:4225
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126e027)
Location: kernel/trace/ftrace.c:4380
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81288502)
Location: kernel/trace/ftrace.c:4346
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010213034)
Location: kernel/trace/ftrace.c:3858
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0451d90)
Location: kernel/trace/ftrace.c:3858
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c00000000029320c)
Location: kernel/trace/ftrace.c:3858
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe00017335c)
Location: kernel/trace/ftrace.c:3858
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81192999)
Location: kernel/trace/ftrace.c:3858
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81185aa9)
Location: kernel/trace/ftrace.c:3858
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81190769)
Location: kernel/trace/ftrace.c:3858
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119e2f9)
Location: kernel/trace/ftrace.c:3858
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
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
