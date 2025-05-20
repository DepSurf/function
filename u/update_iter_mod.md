# Function: <code>update_iter_mod</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8111bb7b)
Location: kernel/kallsyms.c:532
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (ffffffff81127118)
Location: kernel/kallsyms.c:555
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (ffffffff8113501a)
Location: kernel/kallsyms.c:509
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
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
In kernel/kallsyms.c (ffffffff81140c7d)
Location: kernel/kallsyms.c:536
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
In kernel/kallsyms.c (ffffffff8114c060)
Location: kernel/kallsyms.c:539
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
In kernel/kallsyms.c (ffffffff81157d30)
Location: kernel/kallsyms.c:539
Inline: True
Inline callers:
  - kernel/kallsyms.c:update_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int update_iter_mod(struct kallsym_iter *iter, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811687e0)
Location: kernel/kallsyms.c:538
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811687e0-ffffffff81168947: update_iter_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int update_iter_mod(struct kallsym_iter *iter, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81164dd0)
Location: kernel/kallsyms.c:568
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81164dd0-ffffffff81164fc3: update_iter_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int update_iter_mod(struct kallsym_iter *iter, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81165ba0)
Location: kernel/kallsyms.c:619
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81165ba0-ffffffff81165d93: update_iter_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int update_iter_mod(struct kallsym_iter *iter, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8118b360)
Location: kernel/kallsyms.c:683
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff8118b360-ffffffff8118b553: update_iter_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int update_iter_mod(struct kallsym_iter *iter, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811ba670)
Location: kernel/kallsyms.c:707
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811ba670-ffffffff811ba88b: update_iter_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int update_iter_mod(struct kallsym_iter *iter, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811fc340)
Location: kernel/kallsyms.c:780
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811fc340-ffffffff811fc55b: update_iter_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int update_iter_mod(struct kallsym_iter *iter, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81210700)
Location: kernel/kallsyms.c:725
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81210700-ffffffff812108a6: update_iter_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int update_iter_mod(struct kallsym_iter *iter, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81227d80)
Location: kernel/kallsyms.c:723
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81227d80-ffffffff81227f26: update_iter_mod (STB_LOCAL)
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
In kernel/kallsyms.c (ffff8000101c724c)
Location: kernel/kallsyms.c:539
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
In kernel/kallsyms.c (c040e154)
Location: kernel/kallsyms.c:539
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
In kernel/kallsyms.c (c00000000022f460)
Location: kernel/kallsyms.c:539
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
In kernel/kallsyms.c (ffffffe000147580)
Location: kernel/kallsyms.c:539
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
In kernel/kallsyms.c (ffffffff81150350)
Location: kernel/kallsyms.c:539
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
In kernel/kallsyms.c (ffffffff81143600)
Location: kernel/kallsyms.c:539
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
In kernel/kallsyms.c (ffffffff8114e200)
Location: kernel/kallsyms.c:539
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
In kernel/kallsyms.c (ffffffff8115afe0)
Location: kernel/kallsyms.c:539
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
