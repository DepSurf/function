# Function: <code>rcu_inkernel_boot_has_ended</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rcu_inkernel_boot_has_ended();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112fb90)
Location: kernel/rcu/update.c:216
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff8112fb90-ffffffff8112fba2: rcu_inkernel_boot_has_ended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rcu_inkernel_boot_has_ended();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112b9f0)
Location: kernel/rcu/update.c:204
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff8112b9f0-ffffffff8112ba02: rcu_inkernel_boot_has_ended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rcu_inkernel_boot_has_ended();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112bd20)
Location: kernel/rcu/update.c:206
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff8112bd20-ffffffff8112bd32: rcu_inkernel_boot_has_ended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool rcu_inkernel_boot_has_ended();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:206
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff81cadf15-ffffffff81cadf35: rcu_inkernel_boot_has_ended.cold (STB_LOCAL)
ffffffff8114cf50-ffffffff8114cf68: rcu_inkernel_boot_has_ended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool rcu_inkernel_boot_has_ended();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:206
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff81e5e4bf-ffffffff81e5e4e9: rcu_inkernel_boot_has_ended.cold (STB_LOCAL)
ffffffff81173580-ffffffff811735a2: rcu_inkernel_boot_has_ended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool rcu_inkernel_boot_has_ended();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:206
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff82059ce2-ffffffff82059d0c: rcu_inkernel_boot_has_ended.cold (STB_LOCAL)
ffffffff811a97e0-ffffffff811a9802: rcu_inkernel_boot_has_ended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool rcu_inkernel_boot_has_ended();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:244
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff820d84c3-ffffffff820d84ed: rcu_inkernel_boot_has_ended.cold (STB_LOCAL)
ffffffff811bb6d0-ffffffff811bb6f2: rcu_inkernel_boot_has_ended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool rcu_inkernel_boot_has_ended();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:245
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff821b3744-ffffffff821b376e: rcu_inkernel_boot_has_ended.cold (STB_LOCAL)
ffffffff811cb780-ffffffff811cb7a2: rcu_inkernel_boot_has_ended (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
