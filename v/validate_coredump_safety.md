# Function: <code>validate_coredump_safety</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (ffffffff81087c80)
Location: kernel/sysctl.c:2299
Inline: True
```
**Symbols:**

```
ffffffff81087c80-ffffffff81087ca7: validate_coredump_safety.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (ffffffff8108ab00)
Location: kernel/sysctl.c:2445
Inline: True
```
**Symbols:**

```
ffffffff8108ab00-ffffffff8108ab27: validate_coredump_safety.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (ffffffff8108fa50)
Location: kernel/sysctl.c:2430
Inline: True
```
**Symbols:**

```
ffffffff8108fa50-ffffffff8108fa77: validate_coredump_safety.part.6 (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff8108cb30)
Location: kernel/sysctl.c:2646
Inline: True
```
**Symbols:**

```
ffffffff8108cb30-ffffffff8108cb58: validate_coredump_safety.part.5 (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff810937a0)
Location: kernel/sysctl.c:2679
Inline: True
```
**Symbols:**

```
ffffffff810937a0-ffffffff810937c8: validate_coredump_safety.part.5 (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff810974a5)
Location: kernel/sysctl.c:2687
Inline: True
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
In kernel/sysctl.c (ffffffff8109f580)
Location: kernel/sysctl.c:2744
Inline: True
```
**Symbols:**

```
ffffffff8109f580-ffffffff8109f5a7: validate_coredump_safety.part.7 (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff810a3ef6)
Location: kernel/sysctl.c:2823
Inline: True
```
**Symbols:**

```
ffffffff810a3c60-ffffffff810a3c7f: validate_coredump_safety.part.0 (STB_LOCAL)
ffffffff810a5ab2-ffffffff810a5ac3: validate_coredump_safety.part.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff810aa4d6)
Location: kernel/sysctl.c:2825
Inline: True
```
**Symbols:**

```
ffffffff810aa230-ffffffff810aa24f: validate_coredump_safety.part.0 (STB_LOCAL)
ffffffff810ac092-ffffffff810ac0a3: validate_coredump_safety.part.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff810b23b6)
Location: kernel/sysctl.c:1066
Inline: True
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
In kernel/sysctl.c (ffffffff810adbe6)
Location: kernel/sysctl.c:1065
Inline: True
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
In kernel/sysctl.c (ffffffff810aedf6)
Location: kernel/sysctl.c:1136
Inline: True
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
In kernel/sysctl.c (ffffffff810c1116)
Location: kernel/sysctl.c:1180
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void validate_coredump_safety();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/coredump.c (ffffffff8148547c)
Location: fs/coredump.c:905
Inline: True
Inline callers:
  - fs/coredump.c:proc_dostring_coredump
  - fs/coredump.c:proc_dostring_coredump
Direct callers:
  - fs/exec.c:proc_dointvec_minmax_coredump
```
**Symbols:**

```
ffffffff81e79c7e-ffffffff81e79c98: validate_coredump_safety.cold (STB_LOCAL)
ffffffff814861a0-ffffffff814861d3: validate_coredump_safety (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void validate_coredump_safety();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81518a3c)
Location: fs/coredump.c:940
Inline: True
Inline callers:
  - fs/coredump.c:proc_dostring_coredump
  - fs/coredump.c:proc_dostring_coredump
Direct callers:
  - fs/exec.c:proc_dointvec_minmax_coredump
```
**Symbols:**

```
ffffffff81519a50-ffffffff81519a90: validate_coredump_safety (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void validate_coredump_safety();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8155033c)
Location: fs/coredump.c:940
Inline: True
Inline callers:
  - fs/coredump.c:proc_dostring_coredump
  - fs/coredump.c:proc_dostring_coredump
Direct callers:
  - fs/exec.c:proc_dointvec_minmax_coredump
```
**Symbols:**

```
ffffffff81551340-ffffffff81551380: validate_coredump_safety (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void validate_coredump_safety();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff815861cc)
Location: fs/coredump.c:979
Inline: True
Inline callers:
  - fs/coredump.c:proc_dostring_coredump
  - fs/coredump.c:proc_dostring_coredump
Direct callers:
  - fs/exec.c:proc_dointvec_minmax_coredump
```
**Symbols:**

```
ffffffff81587240-ffffffff81587280: validate_coredump_safety (STB_GLOBAL)
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
In kernel/sysctl.c (ffff800010102650)
Location: kernel/sysctl.c:2825
Inline: True
```
**Symbols:**

```
ffff800010102650-ffff800010102690: validate_coredump_safety.part.0 (STB_LOCAL)
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
In kernel/sysctl.c (c035e8e8)
Location: kernel/sysctl.c:2825
Inline: True
```
**Symbols:**

```
c035e8e8-c035e924: validate_coredump_safety.part.0 (STB_LOCAL)
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
In kernel/sysctl.c (c000000000149db0)
Location: kernel/sysctl.c:2825
Inline: True
```
**Symbols:**

```
c000000000149db0-c000000000149e08: validate_coredump_safety.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (ffffffe0000c924a)
Location: kernel/sysctl.c:2825
Inline: True
```
**Symbols:**

```
ffffffe0000c924a-ffffffe0000c928e: validate_coredump_safety.part.0 (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff810a3df6)
Location: kernel/sysctl.c:2825
Inline: True
```
**Symbols:**

```
ffffffff810a3b50-ffffffff810a3b6f: validate_coredump_safety.part.0 (STB_LOCAL)
ffffffff810a59b2-ffffffff810a59c3: validate_coredump_safety.part.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff810927d6)
Location: kernel/sysctl.c:2825
Inline: True
```
**Symbols:**

```
ffffffff81092530-ffffffff8109254f: validate_coredump_safety.part.0 (STB_LOCAL)
ffffffff81094392-ffffffff810943a3: validate_coredump_safety.part.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff810a3da6)
Location: kernel/sysctl.c:2825
Inline: True
```
**Symbols:**

```
ffffffff810a3b00-ffffffff810a3b1f: validate_coredump_safety.part.0 (STB_LOCAL)
ffffffff810a5962-ffffffff810a5973: validate_coredump_safety.part.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff810abe66)
Location: kernel/sysctl.c:2825
Inline: True
```
**Symbols:**

```
ffffffff810abbc0-ffffffff810abbdf: validate_coredump_safety.part.0 (STB_LOCAL)
ffffffff810ada22-ffffffff810ada33: validate_coredump_safety.part.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
