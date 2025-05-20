# Function: <code>get_ksymbol_ftrace_mod</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_ksymbol_ftrace_mod(struct kallsym_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81126d20)
Location: kernel/kallsyms.c:506
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81126d20-ffffffff81126d69: get_ksymbol_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_ksymbol_ftrace_mod(struct kallsym_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81134c00)
Location: kernel/kallsyms.c:460
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81134c00-ffffffff81134c4e: get_ksymbol_ftrace_mod (STB_LOCAL)
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
In kernel/kallsyms.c (ffffffff81140d2f)
Location: kernel/kallsyms.c:481
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (ffffffff8114c130)
Location: kernel/kallsyms.c:484
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (ffffffff81157e00)
Location: kernel/kallsyms.c:484
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (ffffffff81168908)
Location: kernel/kallsyms.c:483
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter_mod
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
In kernel/kallsyms.c (ffffffff81164f2a)
Location: kernel/kallsyms.c:490
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter_mod
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
In kernel/kallsyms.c (ffffffff81165cfa)
Location: kernel/kallsyms.c:541
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter_mod
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
In kernel/kallsyms.c (ffffffff8118b4ba)
Location: kernel/kallsyms.c:605
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter_mod
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
In kernel/kallsyms.c (ffffffff811ba7ee)
Location: kernel/kallsyms.c:629
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter_mod
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
In kernel/kallsyms.c (ffffffff811fc4be)
Location: kernel/kallsyms.c:702
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter_mod
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
In kernel/kallsyms.c (ffffffff81210824)
Location: kernel/kallsyms.c:648
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter_mod
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
In kernel/kallsyms.c (ffffffff81227ea4)
Location: kernel/kallsyms.c:646
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter_mod
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
In kernel/kallsyms.c (ffff8000101c72f8)
Location: kernel/kallsyms.c:484
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (c040e240)
Location: kernel/kallsyms.c:484
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (c00000000022f55c)
Location: kernel/kallsyms.c:484
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (ffffffe0001475ec)
Location: kernel/kallsyms.c:484
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (ffffffff81150420)
Location: kernel/kallsyms.c:484
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (ffffffff811436d0)
Location: kernel/kallsyms.c:484
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (ffffffff8114e2d0)
Location: kernel/kallsyms.c:484
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (ffffffff8115b0b0)
Location: kernel/kallsyms.c:484
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
