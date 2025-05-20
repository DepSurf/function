# Function: <code>hv_cpu_die</code>

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
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102aee0)
Location: arch/x86/hyperv/hv_init.c:231
Inline: False
```
**Symbols:**

```
ffffffff8102aee0-ffffffff8102afcf: hv_cpu_die (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102b610)
Location: arch/x86/hyperv/hv_init.c:232
Inline: False
```
**Symbols:**

```
ffffffff8102b610-ffffffff8102b6ff: hv_cpu_die (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102d3a0)
Location: arch/x86/hyperv/hv_init.c:185
Inline: False
```
**Symbols:**

```
ffffffff8102d3a0-ffffffff8102d48f: hv_cpu_die (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102dcb0)
Location: arch/x86/hyperv/hv_init.c:199
Inline: False
```
**Symbols:**

```
ffffffff8102dcb0-ffffffff8102dd9f: hv_cpu_die (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81030010)
Location: arch/x86/hyperv/hv_init.c:210
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_suspend
```
**Symbols:**

```
ffffffff81030010-ffffffff81030109: hv_cpu_die (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81030c40)
Location: arch/x86/hyperv/hv_init.c:213
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_suspend
```
**Symbols:**

```
ffffffff81030c40-ffffffff81030d39: hv_cpu_die (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81031760)
Location: arch/x86/hyperv/hv_init.c:205
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_suspend
```
**Symbols:**

```
ffffffff81031760-ffffffff81031888: hv_cpu_die (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:190
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_suspend
```
**Symbols:**

```
ffffffff810366e0-ffffffff810367f8: hv_cpu_die (STB_LOCAL)
ffffffff81c97de7-ffffffff81c97dfc: hv_cpu_die.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:222
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_suspend
```
**Symbols:**

```
ffffffff8103c640-ffffffff8103c7b2: hv_cpu_die (STB_LOCAL)
ffffffff81e47228-ffffffff81e4723d: hv_cpu_die.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:212
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_suspend
```
**Symbols:**

```
ffffffff81045480-ffffffff81045607: hv_cpu_die (STB_LOCAL)
ffffffff82051ed5-ffffffff82051eea: hv_cpu_die.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:215
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_suspend
```
**Symbols:**

```
ffffffff810455c0-ffffffff81045747: hv_cpu_die (STB_LOCAL)
ffffffff820d034a-ffffffff820d035f: hv_cpu_die.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:233
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_suspend
```
**Symbols:**

```
ffffffff8104bc90-ffffffff8104be17: hv_cpu_die (STB_LOCAL)
ffffffff821aace0-ffffffff821aacf5: hv_cpu_die.cold (STB_LOCAL)
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
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102de10)
Location: arch/x86/hyperv/hv_init.c:199
Inline: False
```
**Symbols:**

```
ffffffff8102de10-ffffffff8102deff: hv_cpu_die (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8101d7c0)
Location: arch/x86/hyperv/hv_init.c:199
Inline: True
```
**Symbols:**

```
ffffffff8101d7c0-ffffffff8101d8c2: hv_cpu_die (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102dc70)
Location: arch/x86/hyperv/hv_init.c:199
Inline: False
```
**Symbols:**

```
ffffffff8102dc70-ffffffff8102dd5f: hv_cpu_die (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hv_cpu_die(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102ea60)
Location: arch/x86/hyperv/hv_init.c:199
Inline: False
```
**Symbols:**

```
ffffffff8102ea60-ffffffff8102eb4f: hv_cpu_die (STB_LOCAL)
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
