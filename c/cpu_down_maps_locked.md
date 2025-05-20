# Function: <code>cpu_down_maps_locked</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81091056)
Location: kernel/cpu.c:1000
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:do_cpu_down
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
In kernel/cpu.c (ffffffff810993e6)
Location: kernel/cpu.c:1016
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:do_cpu_down
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
In kernel/cpu.c (ffffffff8109dd3a)
Location: kernel/cpu.c:1028
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:do_cpu_down
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
In kernel/cpu.c (ffffffff810a428a)
Location: kernel/cpu.c:1037
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:do_cpu_down
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
In kernel/cpu.c (ffffffff810aadff)
Location: kernel/cpu.c:1053
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
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
In kernel/cpu.c (ffffffff810a668f)
Location: kernel/cpu.c:1057
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
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
In kernel/cpu.c (ffffffff810a76ff)
Location: kernel/cpu.c:1162
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
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
In kernel/cpu.c (ffffffff810b9142)
Location: kernel/cpu.c:1186
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
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
In kernel/cpu.c (ffffffff810cfabb)
Location: kernel/cpu.c:1192
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
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
In kernel/cpu.c (ffffffff810edecd)
Location: kernel/cpu.c:1218
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpu_down_maps_locked(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f7db0)
Location: kernel/cpu.c:1482
Inline: False
Direct callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
```
**Symbols:**

```
ffffffff810f7db0-ffffffff810f7e5e: cpu_down_maps_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpu_down_maps_locked(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81100f40)
Location: kernel/cpu.c:1517
Inline: False
Direct callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
```
**Symbols:**

```
ffffffff81100f40-ffffffff8110100e: cpu_down_maps_locked (STB_LOCAL)
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
In kernel/cpu.c (ffff8000100f9368)
Location: kernel/cpu.c:1037
Inline: True
Inline callers:
  - kernel/cpu.c:do_cpu_down
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
In kernel/cpu.c (c0357670)
Location: kernel/cpu.c:1037
Inline: True
Inline callers:
  - kernel/cpu.c:do_cpu_down
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
In kernel/cpu.c (c000000000140114)
Location: kernel/cpu.c:1037
Inline: True
Inline callers:
  - kernel/cpu.c:do_cpu_down
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109dbaa)
Location: kernel/cpu.c:1037
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:do_cpu_down
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
In kernel/cpu.c (ffffffff8108c5ca)
Location: kernel/cpu.c:1037
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:do_cpu_down
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
In kernel/cpu.c (ffffffff8109db5a)
Location: kernel/cpu.c:1037
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:do_cpu_down
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
In kernel/cpu.c (ffffffff810a5a4a)
Location: kernel/cpu.c:1037
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:do_cpu_down
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
