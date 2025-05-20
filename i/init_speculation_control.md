# Function: <code>init_speculation_control</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040de1)
Location: arch/x86/kernel/cpu/common.c:753
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
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
In arch/x86/kernel/cpu/common.c (ffffffff81042658)
Location: arch/x86/kernel/cpu/common.c:770
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
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
In arch/x86/kernel/cpu/common.c (ffffffff81043c78)
Location: arch/x86/kernel/cpu/common.c:770
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
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
In arch/x86/kernel/cpu/common.c (ffffffff8104611f)
Location: arch/x86/kernel/cpu/common.c:834
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
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
In arch/x86/kernel/cpu/common.c (ffffffff8104687f)
Location: arch/x86/kernel/cpu/common.c:834
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_speculation_control(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a0d0)
Location: arch/x86/kernel/cpu/common.c:839
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
**Symbols:**

```
ffffffff8104a0d0-ffffffff8104a1bd: init_speculation_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_speculation_control(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81049570)
Location: arch/x86/kernel/cpu/common.c:857
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
**Symbols:**

```
ffffffff81049570-ffffffff8104965d: init_speculation_control (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff8104b2f4)
Location: arch/x86/kernel/cpu/common.c:855
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
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
In arch/x86/kernel/cpu/common.c (ffffffff810523e4)
Location: arch/x86/kernel/cpu/common.c:858
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_speculation_control(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105d210)
Location: arch/x86/kernel/cpu/common.c:966
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
**Symbols:**

```
ffffffff8105d210-ffffffff8105d2cb: init_speculation_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_speculation_control(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106b670)
Location: arch/x86/kernel/cpu/common.c:987
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
**Symbols:**

```
ffffffff8106b670-ffffffff8106b72b: init_speculation_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_speculation_control(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106d020)
Location: arch/x86/kernel/cpu/common.c:976
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
**Symbols:**

```
ffffffff8106d020-ffffffff8106d0db: init_speculation_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_speculation_control(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81074110)
Location: arch/x86/kernel/cpu/common.c:973
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
**Symbols:**

```
ffffffff81074110-ffffffff810741cb: init_speculation_control (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff810469ff)
Location: arch/x86/kernel/cpu/common.c:834
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
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
In arch/x86/kernel/cpu/common.c (ffffffff81035b06)
Location: arch/x86/kernel/cpu/common.c:834
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
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
In arch/x86/kernel/cpu/common.c (ffffffff8104683f)
Location: arch/x86/kernel/cpu/common.c:834
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
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
In arch/x86/kernel/cpu/common.c (ffffffff81047c3f)
Location: arch/x86/kernel/cpu/common.c:834
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
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
