# Function: <code>l1tf_show_state</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t l1tf_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81043710)
Location: arch/x86/kernel/cpu/bugs.c:776
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
```
**Symbols:**

```
ffffffff81043710-ffffffff810437aa: l1tf_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t l1tf_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81044d20)
Location: arch/x86/kernel/cpu/bugs.c:1075
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
```
**Symbols:**

```
ffffffff81044d20-ffffffff81044daf: l1tf_show_state (STB_LOCAL)
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8104755a)
Location: arch/x86/kernel/cpu/bugs.c:1291
Inline: True
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81047ce0)
Location: arch/x86/kernel/cpu/bugs.c:1424
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t l1tf_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b8a0)
Location: arch/x86/kernel/cpu/bugs.c:1541
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
```
**Symbols:**

```
ffffffff8104b8a0-ffffffff8104b92f: l1tf_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t l1tf_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104ade0)
Location: arch/x86/kernel/cpu/bugs.c:1549
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
```
**Symbols:**

```
ffffffff8104ade0-ffffffff8104ae6f: l1tf_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t l1tf_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c6c0)
Location: arch/x86/kernel/cpu/bugs.c:1549
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
```
**Symbols:**

```
ffffffff8104c6c0-ffffffff8104c74f: l1tf_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t l1tf_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810539b0)
Location: arch/x86/kernel/cpu/bugs.c:1704
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
```
**Symbols:**

```
ffffffff810539b0-ffffffff81053aa1: l1tf_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t l1tf_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8105f480)
Location: arch/x86/kernel/cpu/bugs.c:2206
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
```
**Symbols:**

```
ffffffff8105f480-ffffffff8105f5ad: l1tf_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t l1tf_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106dbf0)
Location: arch/x86/kernel/cpu/bugs.c:2257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
```
**Symbols:**

```
ffffffff8106dbf0-ffffffff8106dd1a: l1tf_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t l1tf_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106f510)
Location: arch/x86/kernel/cpu/bugs.c:2532
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
```
**Symbols:**

```
ffffffff8106f510-ffffffff8106f63a: l1tf_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t l1tf_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810768d0)
Location: arch/x86/kernel/cpu/bugs.c:2670
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
```
**Symbols:**

```
ffffffff810768d0-ffffffff810769fa: l1tf_show_state (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047e50)
Location: arch/x86/kernel/cpu/bugs.c:1424
Inline: True
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81037160)
Location: arch/x86/kernel/cpu/bugs.c:1424
Inline: True
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81047c90)
Location: arch/x86/kernel/cpu/bugs.c:1424
Inline: True
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
In arch/x86/kernel/cpu/bugs.c (ffffffff810490a0)
Location: arch/x86/kernel/cpu/bugs.c:1424
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
