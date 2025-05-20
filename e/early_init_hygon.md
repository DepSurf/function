# Function: <code>early_init_hygon</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff81048290)
Location: arch/x86/kernel/cpu/hygon.c:255
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81048290-ffffffff810483ea: early_init_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b030)
Location: arch/x86/kernel/cpu/hygon.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8104b030-ffffffff8104b184: early_init_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104ba30)
Location: arch/x86/kernel/cpu/hygon.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8104ba30-ffffffff8104bb84: early_init_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff81050310)
Location: arch/x86/kernel/cpu/hygon.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81050310-ffffffff8105047b: early_init_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f3e0)
Location: arch/x86/kernel/cpu/hygon.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8104f3e0-ffffffff8104f54b: early_init_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff81050ea0)
Location: arch/x86/kernel/cpu/hygon.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81050ea0-ffffffff8105100b: early_init_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (0)
Location: arch/x86/kernel/cpu/hygon.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff810592c0-ffffffff8105944f: early_init_hygon (STB_LOCAL)
ffffffff81c9b379-ffffffff81c9b39e: early_init_hygon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (0)
Location: arch/x86/kernel/cpu/hygon.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81065970-ffffffff81065b15: early_init_hygon (STB_LOCAL)
ffffffff81e4a8b1-ffffffff81e4a8d6: early_init_hygon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (0)
Location: arch/x86/kernel/cpu/hygon.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81074ca0-ffffffff81074e45: early_init_hygon (STB_LOCAL)
ffffffff82052cbd-ffffffff82052ce2: early_init_hygon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (0)
Location: arch/x86/kernel/cpu/hygon.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81076e10-ffffffff81076fb5: early_init_hygon (STB_LOCAL)
ffffffff820d11a2-ffffffff820d11c7: early_init_hygon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (0)
Location: arch/x86/kernel/cpu/hygon.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8107e390-ffffffff8107e535: early_init_hygon (STB_LOCAL)
ffffffff821abce5-ffffffff821abd0a: early_init_hygon.cold (STB_LOCAL)
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
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bba0)
Location: arch/x86/kernel/cpu/hygon.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8104bba0-ffffffff8104bcf4: early_init_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103add0)
Location: arch/x86/kernel/cpu/hygon.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8103add0-ffffffff8103aef8: early_init_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b9e0)
Location: arch/x86/kernel/cpu/hygon.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8104b9e0-ffffffff8104bb34: early_init_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void early_init_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104cdf0)
Location: arch/x86/kernel/cpu/hygon.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8104cdf0-ffffffff8104cf44: early_init_hygon (STB_LOCAL)
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
