# Function: <code>optimize_all_kprobes</code>

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
In kernel/kprobes.c (ffffffff8112eb2a)
Location: kernel/kprobes.c:779
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
In kernel/kprobes.c (ffffffff81136daa)
Location: kernel/kprobes.c:779
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
In kernel/kprobes.c (ffffffff81140b2a)
Location: kernel/kprobes.c:779
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
In kernel/kprobes.c (ffffffff8114228a)
Location: kernel/kprobes.c:821
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
In kernel/kprobes.c (ffffffff8114f04a)
Location: kernel/kprobes.c:823
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
In kernel/kprobes.c (ffffffff8115daf1)
Location: kernel/kprobes.c:821
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
In kernel/kprobes.c (ffffffff8116a711)
Location: kernel/kprobes.c:831
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
In kernel/kprobes.c (ffffffff81177472)
Location: kernel/kprobes.c:816
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
In kernel/kprobes.c (ffffffff81183392)
Location: kernel/kprobes.c:837
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
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
In kernel/kprobes.c (ffffffff8119728b)
Location: kernel/kprobes.c:842
Inline: True
Inline callers:
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void optimize_all_kprobes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81192c60)
Location: kernel/kprobes.c:864
Inline: False
Direct callers:
  - kernel/kprobes.c:init_optprobes
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
**Symbols:**

```
ffffffff81192c60-ffffffff81192cef: optimize_all_kprobes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void optimize_all_kprobes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81193bb0)
Location: kernel/kprobes.c:865
Inline: False
Direct callers:
  - kernel/kprobes.c:init_optprobes
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
**Symbols:**

```
ffffffff81193bb0-ffffffff81193c42: optimize_all_kprobes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void optimize_all_kprobes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:875
Inline: False
Direct callers:
  - kernel/kprobes.c:init_optprobes
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
**Symbols:**

```
ffffffff811bc2f0-ffffffff811bc398: optimize_all_kprobes (STB_LOCAL)
ffffffff81cb3791-ffffffff81cb37a5: optimize_all_kprobes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void optimize_all_kprobes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:887
Inline: False
Direct callers:
  - kernel/kprobes.c:init_optprobes
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
**Symbols:**

```
ffffffff811efb60-ffffffff811efc12: optimize_all_kprobes (STB_LOCAL)
ffffffff81e6458d-ffffffff81e645a1: optimize_all_kprobes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void optimize_all_kprobes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:884
Inline: False
Direct callers:
  - kernel/kprobes.c:init_optprobes
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
**Symbols:**

```
ffffffff812365c0-ffffffff81236678: optimize_all_kprobes (STB_LOCAL)
ffffffff8205c697-ffffffff8205c6ab: optimize_all_kprobes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void optimize_all_kprobes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:884
Inline: False
Direct callers:
  - kernel/kprobes.c:init_optprobes
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
**Symbols:**

```
ffffffff8124d3e0-ffffffff8124d498: optimize_all_kprobes (STB_LOCAL)
ffffffff820daff4-ffffffff820db008: optimize_all_kprobes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void optimize_all_kprobes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:884
Inline: False
Direct callers:
  - kernel/kprobes.c:init_optprobes
  - kernel/kprobes.c:proc_kprobes_optimization_handler
```
**Symbols:**

```
ffffffff812672e0-ffffffff81267398: optimize_all_kprobes (STB_LOCAL)
ffffffff821b6d4a-ffffffff821b6d5e: optimize_all_kprobes.cold (STB_LOCAL)
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
In kernel/kprobes.c (c0438c18)
Location: kernel/kprobes.c:837
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
In kernel/kprobes.c (c00000000026fc30)
Location: kernel/kprobes.c:837
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
In kernel/kprobes.c (ffffffff8117b9b2)
Location: kernel/kprobes.c:837
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
In kernel/kprobes.c (ffffffff8116eb52)
Location: kernel/kprobes.c:837
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
In kernel/kprobes.c (ffffffff81179782)
Location: kernel/kprobes.c:837
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
In kernel/kprobes.c (ffffffff81187092)
Location: kernel/kprobes.c:837
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
