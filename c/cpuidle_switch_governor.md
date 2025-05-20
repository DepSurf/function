# Function: <code>cpuidle_switch_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff816bc210)
Location: drivers/cpuidle/governor.c:44
Inline: True
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff816bc210-ffffffff816bc2f8: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff8171db20)
Location: drivers/cpuidle/governor.c:44
Inline: True
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff8171db20-ffffffff8171dc08: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81750690)
Location: drivers/cpuidle/governor.c:43
Inline: True
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff81750690-ffffffff8175074b: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff8176f130)
Location: drivers/cpuidle/governor.c:43
Inline: True
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff8176f130-ffffffff8176f1eb: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff817e4990)
Location: drivers/cpuidle/governor.c:43
Inline: True
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff817e4990-ffffffff817e4a4b: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff8182dd6b)
Location: drivers/cpuidle/governor.c:43
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff8182dbc0-ffffffff8182dc6d: cpuidle_switch_governor.part.2 (STB_LOCAL)
ffffffff8182dc70-ffffffff8182dc97: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81859f25)
Location: drivers/cpuidle/governor.c:46
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff81859d40-ffffffff81859ded: cpuidle_switch_governor.part.2 (STB_LOCAL)
ffffffff81859df0-ffffffff81859e17: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff8189d875)
Location: drivers/cpuidle/governor.c:46
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff8189d680-ffffffff8189d731: cpuidle_switch_governor.part.0 (STB_LOCAL)
ffffffff8189d740-ffffffff8189d767: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff818cfd14)
Location: drivers/cpuidle/governor.c:47
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff818cfaf0-ffffffff818cfba1: cpuidle_switch_governor.part.0 (STB_LOCAL)
ffffffff818cfc10-ffffffff818cfc37: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff819a2385)
Location: drivers/cpuidle/governor.c:47
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff819a2130-ffffffff819a21e1: cpuidle_switch_governor.part.0 (STB_LOCAL)
ffffffff819a2250-ffffffff819a2277: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff819a5345)
Location: drivers/cpuidle/governor.c:47
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff819a50f0-ffffffff819a51a1: cpuidle_switch_governor.part.0 (STB_LOCAL)
ffffffff819a5210-ffffffff819a5237: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81989fb5)
Location: drivers/cpuidle/governor.c:47
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff81989d60-ffffffff81989e11: cpuidle_switch_governor.part.0 (STB_LOCAL)
ffffffff81989e80-ffffffff81989ea7: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81a34915)
Location: drivers/cpuidle/governor.c:47
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff81a346c0-ffffffff81a34771: cpuidle_switch_governor.part.0 (STB_LOCAL)
ffffffff81a347e0-ffffffff81a34807: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81ba0f90)
Location: drivers/cpuidle/governor.c:47
Inline: False
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff81ba0f90-ffffffff81ba1063: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81d42c70)
Location: drivers/cpuidle/governor.c:47
Inline: False
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff81d42c70-ffffffff81d42d4d: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81dace90)
Location: drivers/cpuidle/governor.c:47
Inline: False
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff81dace90-ffffffff81dacf6d: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81e64f30)
Location: drivers/cpuidle/governor.c:47
Inline: False
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff81e64f30-ffffffff81e6500d: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffff800010b27ffc)
Location: drivers/cpuidle/governor.c:47
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffff800010b27d70-ffff800010b27e44: cpuidle_switch_governor.part.0 (STB_LOCAL)
ffff800010b27ed0-ffff800010b27f20: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (c0c02ca0)
Location: drivers/cpuidle/governor.c:47
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
c0c02a5c-c0c02b0c: cpuidle_switch_governor.part.0 (STB_LOCAL)
c0c02b7c-c0c02bc4: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (c000000000c1f4a4)
Location: drivers/cpuidle/governor.c:47
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
c000000000c1f180-c000000000c1f290: cpuidle_switch_governor.part.0 (STB_LOCAL)
c000000000c1f360-c000000000c1f3a0: cpuidle_switch_governor (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff818737b4)
Location: drivers/cpuidle/governor.c:47
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff81873590-ffffffff81873641: cpuidle_switch_governor.part.0 (STB_LOCAL)
ffffffff818736b0-ffffffff818736d7: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff8183d5a4)
Location: drivers/cpuidle/governor.c:47
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff8183d380-ffffffff8183d431: cpuidle_switch_governor.part.0 (STB_LOCAL)
ffffffff8183d4a0-ffffffff8183d4c7: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff818c51c4)
Location: drivers/cpuidle/governor.c:47
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff818c4fa0-ffffffff818c5051: cpuidle_switch_governor.part.0 (STB_LOCAL)
ffffffff818c50c0-ffffffff818c50e7: cpuidle_switch_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_switch_governor(struct cpuidle_governor *gov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff818e1624)
Location: drivers/cpuidle/governor.c:47
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/sysfs.c:store_current_governor
```
**Symbols:**

```
ffffffff818e1400-ffffffff818e14b1: cpuidle_switch_governor.part.0 (STB_LOCAL)
ffffffff818e1520-ffffffff818e1547: cpuidle_switch_governor (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
