# Function: <code>amd_get_topology</code>

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
In arch/x86/kernel/cpu/amd.c (ffffffff81042de1)
Location: arch/x86/kernel/cpu/amd.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81042d6b)
Location: arch/x86/kernel/cpu/amd.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81042860)
Location: arch/x86/kernel/cpu/amd.c:305
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81040949)
Location: arch/x86/kernel/cpu/amd.c:307
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81043cb8)
Location: arch/x86/kernel/cpu/amd.c:323
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81045e98)
Location: arch/x86/kernel/cpu/amd.c:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff810478bc)
Location: arch/x86/kernel/cpu/amd.c:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104a625)
Location: arch/x86/kernel/cpu/amd.c:334
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104afc0)
Location: arch/x86/kernel/cpu/amd.c:336
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void amd_get_topology(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f350)
Location: arch/x86/kernel/cpu/amd.c:330
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104f350-ffffffff8104f4c9: amd_get_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void amd_get_topology(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104e620)
Location: arch/x86/kernel/cpu/amd.c:330
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104e620-ffffffff8104e7a8: amd_get_topology (STB_LOCAL)
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
In arch/x86/kernel/cpu/amd.c (ffffffff81050706)
Location: arch/x86/kernel/cpu/amd.c:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81058a3f)
Location: arch/x86/kernel/cpu/amd.c:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void amd_get_topology(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff810646b0)
Location: arch/x86/kernel/cpu/amd.c:330
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff810646b0-ffffffff8106488e: amd_get_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_get_topology(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81073920)
Location: arch/x86/kernel/cpu/amd.c:330
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81073920-ffffffff81073afe: amd_get_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void amd_get_topology(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff810757d0)
Location: arch/x86/kernel/cpu/amd.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff810757d0-ffffffff810759ae: amd_get_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void amd_get_topology(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8107cc30)
Location: arch/x86/kernel/cpu/amd.c:325
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8107cc30-ffffffff8107cdb7: amd_get_topology (STB_LOCAL)
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104b130)
Location: arch/x86/kernel/cpu/amd.c:336
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8103a5c0)
Location: arch/x86/kernel/cpu/amd.c:336
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104af70)
Location: arch/x86/kernel/cpu/amd.c:336
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104c380)
Location: arch/x86/kernel/cpu/amd.c:336
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
