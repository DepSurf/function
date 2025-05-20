# Function: <code>mce_disable_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mce_disable_cpu(void *h);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046200)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2372
Inline: True
```
**Symbols:**

```
ffffffff81046200-ffffffff8104624e: mce_disable_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mce_disable_cpu(void *h);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046210)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2455
Inline: True
```
**Symbols:**

```
ffffffff81046210-ffffffff8104625e: mce_disable_cpu (STB_LOCAL)
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047e0e)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2522
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810476ce)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b18e)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2262
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104dace)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2255
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104b1ce)
Location: arch/x86/kernel/cpu/mce/core.c:2278
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e0bf)
Location: arch/x86/kernel/cpu/mce/core.c:2333
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ea5f)
Location: arch/x86/kernel/cpu/mce/core.c:2333
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052d8f)
Location: arch/x86/kernel/cpu/mce/core.c:2461
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051edf)
Location: arch/x86/kernel/cpu/mce/core.c:2537
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105364f)
Location: arch/x86/kernel/cpu/mce/core.c:2548
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105bd20)
Location: arch/x86/kernel/cpu/mce/core.c:2611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810681fe)
Location: arch/x86/kernel/cpu/mce/core.c:2623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077c8e)
Location: arch/x86/kernel/cpu/mce/core.c:2623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81079f3e)
Location: arch/x86/kernel/cpu/mce/core.c:2640
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810816ae)
Location: arch/x86/kernel/cpu/mce/core.c:2666
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ebbf)
Location: arch/x86/kernel/cpu/mce/core.c:2333
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103e08f)
Location: arch/x86/kernel/cpu/mce/core.c:2333
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ea0f)
Location: arch/x86/kernel/cpu/mce/core.c:2333
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104fe4f)
Location: arch/x86/kernel/cpu/mce/core.c:2333
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
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
</ul>
