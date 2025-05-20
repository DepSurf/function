# Function: <code>ftrace_hash_move</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ftrace_hash_move(struct ftrace_ops *ops, int enable, struct ftrace_hash **dst, struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811425e0)
Location: kernel/trace/ftrace.c:1412
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff811425e0-ffffffff811427ac: ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ftrace_hash_move(struct ftrace_ops *ops, int enable, struct ftrace_hash **dst, struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114a230)
Location: kernel/trace/ftrace.c:1381
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff8114a230-ffffffff8114a402: ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ftrace_hash_move(struct ftrace_ops *ops, int enable, struct ftrace_hash **dst, struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811540b0)
Location: kernel/trace/ftrace.c:1387
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff811540b0-ffffffff81154282: ftrace_hash_move (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff811580fd)
Location: kernel/trace/ftrace.c:1507
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
In kernel/trace/ftrace.c (ffffffff81164bfd)
Location: kernel/trace/ftrace.c:1483
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
In kernel/trace/ftrace.c (ffffffff8117391f)
Location: kernel/trace/ftrace.c:1472
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
In kernel/trace/ftrace.c (ffffffff8118156f)
Location: kernel/trace/ftrace.c:1421
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
In kernel/trace/ftrace.c (ffffffff8118e373)
Location: kernel/trace/ftrace.c:1418
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
In kernel/trace/ftrace.c (ffffffff8119a2f3)
Location: kernel/trace/ftrace.c:1419
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
In kernel/trace/ftrace.c (ffffffff811afee3)
Location: kernel/trace/ftrace.c:1412
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
In kernel/trace/ftrace.c (ffffffff811ad8a3)
Location: kernel/trace/ftrace.c:1411
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
In kernel/trace/ftrace.c (ffffffff811ae413)
Location: kernel/trace/ftrace.c:1411
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
In kernel/trace/ftrace.c (ffffffff811d81e3)
Location: kernel/trace/ftrace.c:1412
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
In kernel/trace/ftrace.c (ffffffff8120dab1)
Location: kernel/trace/ftrace.c:1406
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
In kernel/trace/ftrace.c (ffffffff81256aa1)
Location: kernel/trace/ftrace.c:1412
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
In kernel/trace/ftrace.c (ffffffff8126df8f)
Location: kernel/trace/ftrace.c:1443
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
In kernel/trace/ftrace.c (ffffffff81288482)
Location: kernel/trace/ftrace.c:1442
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
In kernel/trace/ftrace.c (ffff800010212fbc)
Location: kernel/trace/ftrace.c:1419
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
In kernel/trace/ftrace.c (c0451d04)
Location: kernel/trace/ftrace.c:1419
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
In kernel/trace/ftrace.c (c00000000029317c)
Location: kernel/trace/ftrace.c:1419
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
In kernel/trace/ftrace.c (ffffffe0001732d6)
Location: kernel/trace/ftrace.c:1419
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
In kernel/trace/ftrace.c (ffffffff81192913)
Location: kernel/trace/ftrace.c:1419
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
In kernel/trace/ftrace.c (ffffffff81185a23)
Location: kernel/trace/ftrace.c:1419
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
In kernel/trace/ftrace.c (ffffffff811906e3)
Location: kernel/trace/ftrace.c:1419
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
In kernel/trace/ftrace.c (ffffffff8119e273)
Location: kernel/trace/ftrace.c:1419
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
