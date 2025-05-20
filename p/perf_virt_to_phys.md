# Function: <code>perf_virt_to_phys</code>

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
In kernel/events/core.c (ffffffff811c00a1)
Location: kernel/events/core.c:5967
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
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
In kernel/events/core.c (ffffffff811e061d)
Location: kernel/events/core.c:6321
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
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
In kernel/events/core.c (ffffffff811f0a71)
Location: kernel/events/core.c:6330
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
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
In kernel/events/core.c (ffffffff81208102)
Location: kernel/events/core.c:6408
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
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
In kernel/events/core.c (ffffffff81215472)
Location: kernel/events/core.c:6524
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 perf_virt_to_phys(u64 virt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81231d90)
Location: kernel/events/core.c:6924
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81231d90-ffffffff81231f90: perf_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 perf_virt_to_phys(u64 virt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123ba00)
Location: kernel/events/core.c:7008
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8123ba00-ffffffff8123bbf9: perf_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 perf_virt_to_phys(u64 virt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812400b0)
Location: kernel/events/core.c:7119
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff812400b0-ffffffff81240299: perf_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 perf_virt_to_phys(u64 virt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127aaa0)
Location: kernel/events/core.c:7243
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8127aaa0-ffffffff8127ac6d: perf_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 perf_virt_to_phys(u64 virt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cda90)
Location: kernel/events/core.c:7148
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff812cda90-ffffffff812cdc8b: perf_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 perf_virt_to_phys(u64 virt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81339020)
Location: kernel/events/core.c:7415
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81339020-ffffffff81339225: perf_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 perf_virt_to_phys(u64 virt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136a620)
Location: kernel/events/core.c:7424
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8136a620-ffffffff8136a81d: perf_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 perf_virt_to_phys(u64 virt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81392fb0)
Location: kernel/events/core.c:7505
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81392fb0-ffffffff813931aa: perf_virt_to_phys (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029f4dc)
Location: kernel/events/core.c:6524
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cf424)
Location: kernel/events/core.c:6524
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000350804)
Location: kernel/events/core.c:6524
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001ceef8)
Location: kernel/events/core.c:6524
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
</details>
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
In kernel/events/core.c (ffffffff8120dac2)
Location: kernel/events/core.c:6524
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
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
In kernel/events/core.c (ffffffff81200892)
Location: kernel/events/core.c:6524
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
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
In kernel/events/core.c (ffffffff8120b862)
Location: kernel/events/core.c:6524
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
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
In kernel/events/core.c (ffffffff8121a672)
Location: kernel/events/core.c:6524
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
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
