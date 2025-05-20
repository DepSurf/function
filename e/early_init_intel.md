# Function: <code>early_init_intel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81041e30)
Location: arch/x86/kernel/cpu/intel.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81041e30-ffffffff8104218a: early_init_intel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81041e00)
Location: arch/x86/kernel/cpu/intel.c:64
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81041e00-ffffffff8104215a: early_init_intel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81041850)
Location: arch/x86/kernel/cpu/intel.c:107
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81041850-ffffffff81041be3: early_init_intel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8103f9d0)
Location: arch/x86/kernel/cpu/intel.c:104
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8103f9d0-ffffffff8103fce7: early_init_intel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81042c70)
Location: arch/x86/kernel/cpu/intel.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81042c70-ffffffff81043084: early_init_intel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81044b10-ffffffff81044eb1: early_init_intel (STB_LOCAL)
ffffffff81045342-ffffffff81045401: early_init_intel.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81046520-ffffffff810468c1: early_init_intel (STB_LOCAL)
ffffffff81046d8b-ffffffff81046e4a: early_init_intel.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81048f00-ffffffff810492d6: early_init_intel (STB_LOCAL)
ffffffff8104976c-ffffffff8104982b: early_init_intel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff810497d0-ffffffff81049baa: early_init_intel (STB_LOCAL)
ffffffff8104a082-ffffffff8104a141: early_init_intel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:180
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8104df00-ffffffff8104e2e8: early_init_intel (STB_LOCAL)
ffffffff8104e782-ffffffff8104e841: early_init_intel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8104d430-ffffffff8104d825: early_init_intel (STB_LOCAL)
ffffffff81bd52ed-ffffffff81bd53ac: early_init_intel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8104eec0-ffffffff8104f2b5: early_init_intel (STB_LOCAL)
ffffffff81bc76f5-ffffffff81bc77b4: early_init_intel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81056fb0-ffffffff81057406: early_init_intel (STB_LOCAL)
ffffffff81c9b086-ffffffff81c9b145: early_init_intel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:219
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81063320-ffffffff8106377d: early_init_intel (STB_LOCAL)
ffffffff81e4a5bd-ffffffff81e4a67c: early_init_intel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81072330)
Location: arch/x86/kernel/cpu/intel.c:361
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81072330-ffffffff81072863: early_init_intel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81073f10)
Location: arch/x86/kernel/cpu/intel.c:361
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81073f10-ffffffff81074457: early_init_intel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8107b450)
Location: arch/x86/kernel/cpu/intel.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8107b450-ffffffff8107b93c: early_init_intel (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81049940-ffffffff81049d1a: early_init_intel (STB_LOCAL)
ffffffff8104a1f2-ffffffff8104a2b1: early_init_intel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81038cf0-ffffffff81039088: early_init_intel (STB_LOCAL)
ffffffff81039628-ffffffff810396e7: early_init_intel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81049780-ffffffff81049b5a: early_init_intel (STB_LOCAL)
ffffffff8104a032-ffffffff8104a0f1: early_init_intel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void early_init_intel(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8104ab90-ffffffff8104af6a: early_init_intel (STB_LOCAL)
ffffffff8104b442-ffffffff8104b501: early_init_intel.cold (STB_LOCAL)
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
