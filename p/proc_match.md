# Function: <code>proc_match</code>

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
In fs/proc/generic.c (ffffffff8127ec7f)
Location: fs/proc/generic.c:31
Inline: True
Inline callers:
  - fs/proc/generic.c:pde_subdir_find
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
In fs/proc/generic.c (ffffffff812abc9f)
Location: fs/proc/generic.c:31
Inline: True
Inline callers:
  - fs/proc/generic.c:pde_subdir_find
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
In fs/proc/generic.c (ffffffff812c156f)
Location: fs/proc/generic.c:31
Inline: True
Inline callers:
  - fs/proc/generic.c:pde_subdir_find
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (ffffffff812cea31)
Location: fs/proc/generic.c:31
Inline: True
Inline callers:
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
ffffffff812ce9e0-ffffffff812cea02: proc_match.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3201)
Location: fs/proc/generic.c:31
Inline: True
Inline callers:
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
ffffffff812f31b0-ffffffff812f31d2: proc_match.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (ffffffff81320688)
Location: fs/proc/generic.c:45
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
ffffffff81320110-ffffffff81320129: proc_match.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (ffffffff8133777b)
Location: fs/proc/generic.c:45
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
ffffffff813371f0-ffffffff81337209: proc_match.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (ffffffff8135f8ea)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
ffffffff8135f310-ffffffff8135f329: proc_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (ffffffff81377b4a)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
ffffffff81377570-ffffffff81377589: proc_match.part.0 (STB_LOCAL)
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
In fs/proc/generic.c (ffffffff813c035d)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:pde_subdir_insert
  - fs/proc/generic.c:pde_subdir_insert
  - fs/proc/generic.c:pde_subdir_find
  - fs/proc/generic.c:pde_subdir_find
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
In fs/proc/generic.c (ffffffff813d21ad)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:pde_subdir_insert
  - fs/proc/generic.c:pde_subdir_insert
  - fs/proc/generic.c:pde_subdir_find
  - fs/proc/generic.c:pde_subdir_find
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
In fs/proc/generic.c (ffffffff813d9642)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
  - fs/proc/generic.c:pde_subdir_find
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
In fs/proc/generic.c (ffffffff8142ad72)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
  - fs/proc/generic.c:pde_subdir_find
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
In fs/proc/generic.c (ffffffff814a43ba)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
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
In fs/proc/generic.c (ffffffff8153981a)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_match(const char *name, struct proc_dir_entry *de, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81571170)
Location: fs/proc/generic.c:46
Inline: False
Direct callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff81571170-ffffffff815711c8: proc_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_match(const char *name, struct proc_dir_entry *de, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815a9b10)
Location: fs/proc/generic.c:46
Inline: False
Direct callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff815a9b10-ffffffff815a9b68: proc_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (ffff8000104438f8)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
ffff800010443190-ffff8000104431d4: proc_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (c0608b68)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
c06084e4-c0608504: proc_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (c000000000558fc0)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
c000000000558700-c000000000558738: proc_match.part.0 (STB_LOCAL)
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
In fs/proc/generic.c (ffffffe0002da45c)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
  - fs/proc/generic.c:pde_subdir_find
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (ffffffff8137012a)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
ffffffff8136fb50-ffffffff8136fb69: proc_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (ffffffff81360bba)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
ffffffff813605e0-ffffffff813605f9: proc_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (ffffffff8136dbfa)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
ffffffff8136d620-ffffffff8136d639: proc_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (ffffffff8138152a)
Location: fs/proc/generic.c:46
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
Direct callers:
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:pde_subdir_find
```
**Symbols:**

```
ffffffff81380f50-ffffffff81380f69: proc_match.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
