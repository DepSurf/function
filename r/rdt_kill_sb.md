# Function: <code>rdt_kill_sb</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043cb0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:891
Inline: False
```
**Symbols:**

```
ffffffff81043cb0-ffffffff81043ef2: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042c20)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1307
Inline: False
```
**Symbols:**

```
ffffffff81042c20-ffffffff81042eba: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810460c0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1376
Inline: False
```
**Symbols:**

```
ffffffff810460c0-ffffffff8104635a: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048190)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1473
Inline: False
```
**Symbols:**

```
ffffffff81048190-ffffffff8104841a: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81057b70)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2217
Inline: False
```
**Symbols:**

```
ffffffff81057b70-ffffffff81057e2d: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ade0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2258
Inline: False
```
**Symbols:**

```
ffffffff8105ade0-ffffffff8105b0b0: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b6d0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2264
Inline: False
```
**Symbols:**

```
ffffffff8105b6d0-ffffffff8105b9be: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060e80)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2363
Inline: False
```
**Symbols:**

```
ffffffff81060e80-ffffffff81060f39: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f090)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2399
Inline: False
```
**Symbols:**

```
ffffffff8105f090-ffffffff8105f149: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f530)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2395
Inline: False
```
**Symbols:**

```
ffffffff8105f530-ffffffff8105f814: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2445
Inline: False
```
**Symbols:**

```
ffffffff81069d70-ffffffff8106a0bd: rdt_kill_sb (STB_LOCAL)
ffffffff81c9c9c7-ffffffff81c9c9dc: rdt_kill_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2445
Inline: False
```
**Symbols:**

```
ffffffff810770a0-ffffffff810772fc: rdt_kill_sb (STB_LOCAL)
ffffffff81e4bcf9-ffffffff81e4bd0e: rdt_kill_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2493
Inline: False
```
**Symbols:**

```
ffffffff81087c10-ffffffff81087e6c: rdt_kill_sb (STB_LOCAL)
ffffffff82053371-ffffffff82053386: rdt_kill_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2775
Inline: False
```
**Symbols:**

```
ffffffff8108ab80-ffffffff8108ad9a: rdt_kill_sb (STB_LOCAL)
ffffffff820d1993-ffffffff820d19a8: rdt_kill_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2903
Inline: False
```
**Symbols:**

```
ffffffff81092380-ffffffff810925c8: rdt_kill_sb (STB_LOCAL)
ffffffff821ac707-ffffffff821ac71c: rdt_kill_sb.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b250)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2264
Inline: False
```
**Symbols:**

```
ffffffff8105b250-ffffffff8105b53e: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b3c0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2264
Inline: False
```
**Symbols:**

```
ffffffff8104b3c0-ffffffff8104b6ae: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b680)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2264
Inline: False
```
**Symbols:**

```
ffffffff8105b680-ffffffff8105b96e: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rdt_kill_sb(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cb30)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2264
Inline: False
```
**Symbols:**

```
ffffffff8105cb30-ffffffff8105ce3c: rdt_kill_sb (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
