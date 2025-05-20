# Function: <code>pseudo_lock_region_init</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105d495)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060825)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810610d5)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pseudo_lock_region_init(struct pseudo_lock_region *plr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065ff0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff81065ff0-ffffffff8106610a: pseudo_lock_region_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pseudo_lock_region_init(struct pseudo_lock_region *plr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810642a0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff810642a0-ffffffff810643ba: pseudo_lock_region_init (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064935)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106e9e5)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:279
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107c155)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:279
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e2d6)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:279
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81091186)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:279
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098546)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060c55)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810510b5)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061085)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062645)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
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
