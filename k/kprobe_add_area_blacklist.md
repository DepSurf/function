# Function: <code>kprobe_add_area_blacklist</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff828b23d9)
Location: kernel/kprobes.c:2120
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
```
**Symbols:**

```
ffffffff8116b3c0-ffffffff8116b40e: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff828cb106)
Location: kernel/kprobes.c:2124
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
```
**Symbols:**

```
ffffffff81178130-ffffffff8117817e: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff828d35e8)
Location: kernel/kprobes.c:2167
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
```
**Symbols:**

```
ffffffff81184050-ffffffff8118409e: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81197f83)
Location: kernel/kprobes.c:2224
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:init_kprobes
```
**Symbols:**

```
ffffffff81198080-ffffffff811980ce: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8119518d)
Location: kernel/kprobes.c:2248
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:init_kprobes
```
**Symbols:**

```
ffffffff81195280-ffffffff811952ce: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8119619d)
Location: kernel/kprobes.c:2253
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:init_kprobes
```
**Symbols:**

```
ffffffff81196290-ffffffff811962de: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bf114)
Location: kernel/kprobes.c:2247
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:init_kprobes
```
**Symbols:**

```
ffffffff811bf220-ffffffff811bf26e: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811f24ee)
Location: kernel/kprobes.c:2465
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:init_kprobes
```
**Symbols:**

```
ffffffff811f2600-ffffffff811f2666: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff83eb1f16)
Location: kernel/kprobes.c:2472
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:init_kprobes
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
```
**Symbols:**

```
ffffffff81239330-ffffffff81239396: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff836d6ec6)
Location: kernel/kprobes.c:2485
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:init_kprobes
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
```
**Symbols:**

```
ffffffff81250340-ffffffff812503a6: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff83909336)
Location: kernel/kprobes.c:2470
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:init_kprobes
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
```
**Symbols:**

```
ffffffff8126a190-ffffffff8126a1f6: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffff80001144bca0)
Location: kernel/kprobes.c:2167
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
Direct callers:
  - arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist
  - arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist
  - arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist
  - arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist
  - arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist
  - arch/arm64/kernel/probes/kprobes.c:arch_populate_kprobe_blacklist
```
**Symbols:**

```
ffff8000101f9630-ffff8000101f96a4: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c15261f0)
Location: kernel/kprobes.c:2167
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
```
**Symbols:**

```
c04398c0-c043990c: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c000000001371954)
Location: kernel/kprobes.c:2167
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
```
**Symbols:**

```
c000000000270e00-c000000000270ea4: kprobe_add_area_blacklist (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff828bc499)
Location: kernel/kprobes.c:2167
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
```
**Symbols:**

```
ffffffff8117c670-ffffffff8117c6be: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff828b4b2c)
Location: kernel/kprobes.c:2167
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
```
**Symbols:**

```
ffffffff8116f810-ffffffff8116f85e: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff828cf21c)
Location: kernel/kprobes.c:2167
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
```
**Symbols:**

```
ffffffff8117a440-ffffffff8117a48e: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int kprobe_add_area_blacklist(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff828d4616)
Location: kernel/kprobes.c:2167
Inline: True
Inline callers:
  - kernel/kprobes.c:init_kprobes
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
  - arch/x86/kernel/kprobes/core.c:arch_populate_kprobe_blacklist
```
**Symbols:**

```
ffffffff81187d80-ffffffff81187dce: kprobe_add_area_blacklist (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
