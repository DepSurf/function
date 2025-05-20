# Function: <code>get_cpu_vendor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040240)
Location: arch/x86/kernel/cpu/common.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81040240-ffffffff810402e5: get_cpu_vendor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040090)
Location: arch/x86/kernel/cpu/common.c:607
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81040090-ffffffff8104013e: get_cpu_vendor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103fad0)
Location: arch/x86/kernel/cpu/common.c:610
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff8103fad0-ffffffff8103fb7e: get_cpu_vendor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103da50)
Location: arch/x86/kernel/cpu/common.c:653
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff8103da50-ffffffff8103dafc: get_cpu_vendor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810405d0)
Location: arch/x86/kernel/cpu/common.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff810405d0-ffffffff8104067c: get_cpu_vendor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:709
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81041e60-ffffffff81041ef8: get_cpu_vendor (STB_LOCAL)
ffffffff8104342c-ffffffff81043447: get_cpu_vendor.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:709
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81043480-ffffffff81043518: get_cpu_vendor (STB_LOCAL)
ffffffff81044aac-ffffffff81044ac7: get_cpu_vendor.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:773
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff81045980-ffffffff81045a11: get_cpu_vendor (STB_LOCAL)
ffffffff81047035-ffffffff81047050: get_cpu_vendor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:773
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff810460d0-ffffffff81046161: get_cpu_vendor (STB_LOCAL)
ffffffff810477de-ffffffff810477f9: get_cpu_vendor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:778
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:generic_identify
```
**Symbols:**

```
ffffffff81049f10-ffffffff81049fa1: get_cpu_vendor (STB_LOCAL)
ffffffff8104b53e-ffffffff8104b559: get_cpu_vendor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:796
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:generic_identify
```
**Symbols:**

```
ffffffff810493b0-ffffffff81049441: get_cpu_vendor (STB_LOCAL)
ffffffff81bd4f0c-ffffffff81bd4f27: get_cpu_vendor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:794
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff8104ac80-ffffffff8104ad11: get_cpu_vendor (STB_LOCAL)
ffffffff81bc72c0-ffffffff81bc72db: get_cpu_vendor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:797
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81051be0-ffffffff81051d28: get_cpu_vendor (STB_LOCAL)
ffffffff81c9a99a-ffffffff81c9a9c9: get_cpu_vendor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:905
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8105d400-ffffffff8105d560: get_cpu_vendor (STB_LOCAL)
ffffffff81e49e35-ffffffff81e49e64: get_cpu_vendor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:926
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8106b890-ffffffff8106ba0b: get_cpu_vendor (STB_LOCAL)
ffffffff820528b4-ffffffff820528c8: get_cpu_vendor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:915
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8106d1c0-ffffffff8106d33b: get_cpu_vendor (STB_LOCAL)
ffffffff820d0d5b-ffffffff820d0d6f: get_cpu_vendor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:912
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff810742b0-ffffffff8107442b: get_cpu_vendor (STB_LOCAL)
ffffffff821ab87f-ffffffff821ab893: get_cpu_vendor.cold (STB_LOCAL)
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
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:773
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81046250-ffffffff810462e1: get_cpu_vendor (STB_LOCAL)
ffffffff8104794e-ffffffff81047969: get_cpu_vendor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:773
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81035540-ffffffff810355d1: get_cpu_vendor (STB_LOCAL)
ffffffff81036c4e-ffffffff81036c69: get_cpu_vendor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:773
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81046090-ffffffff81046121: get_cpu_vendor (STB_LOCAL)
ffffffff8104778e-ffffffff810477a9: get_cpu_vendor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void get_cpu_vendor(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:773
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81047490-ffffffff81047521: get_cpu_vendor (STB_LOCAL)
ffffffff81048b9e-ffffffff81048bb9: get_cpu_vendor.cold (STB_LOCAL)
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
