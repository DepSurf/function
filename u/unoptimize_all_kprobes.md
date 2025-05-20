# Function: <code>unoptimize_all_kprobes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8112eb35)
Location: kernel/kprobes.c:802
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81136db5)
Location: kernel/kprobes.c:802
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81140b35)
Location: kernel/kprobes.c:802
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff81142295)
Location: kernel/kprobes.c:846
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff8114f055)
Location: kernel/kprobes.c:848
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff8115db24)
Location: kernel/kprobes.c:846
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff8116a744)
Location: kernel/kprobes.c:856
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff811774a6)
Location: kernel/kprobes.c:841
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff811833c6)
Location: kernel/kprobes.c:862
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unoptimize_all_kprobes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81196fa0)
Location: kernel/kprobes.c:867
Inline: False
Direct callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
**Symbols:**

```
ffffffff81196fa0-ffffffff81197042: unoptimize_all_kprobes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unoptimize_all_kprobes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81194120)
Location: kernel/kprobes.c:890
Inline: False
Direct callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
**Symbols:**

```
ffffffff81194120-ffffffff811941c2: unoptimize_all_kprobes (STB_LOCAL)
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
In kernel/kprobes.c (ffffffff811953da)
Location: kernel/kprobes.c:891
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff811be320)
Location: kernel/kprobes.c:901
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff811f141d)
Location: kernel/kprobes.c:913
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff812381fc)
Location: kernel/kprobes.c:910
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff8124f2dc)
Location: kernel/kprobes.c:910
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff8126920c)
Location: kernel/kprobes.c:910
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c0438c44)
Location: kernel/kprobes.c:862
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (c00000000026fc90)
Location: kernel/kprobes.c:862
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
</details>
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
In kernel/kprobes.c (ffffffff8117b9e6)
Location: kernel/kprobes.c:862
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff8116eb86)
Location: kernel/kprobes.c:862
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff811797b6)
Location: kernel/kprobes.c:862
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff811870c6)
Location: kernel/kprobes.c:862
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
</ul>
