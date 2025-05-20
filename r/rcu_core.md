# Function: <code>rcu_core</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111c600)
Location: kernel/rcu/tree.c:2278
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff8111c600-ffffffff8111ca45: rcu_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81128d70)
Location: kernel/rcu/tree.c:2340
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff81128d70-ffffffff81128fd7: rcu_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81136ce0)
Location: kernel/rcu/tree.c:2603
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff81136ce0-ffffffff81136e9d: rcu_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132340)
Location: kernel/rcu/tree.c:2737
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff81132340-ffffffff811324d1: rcu_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133580)
Location: kernel/rcu/tree.c:2756
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff81133580-ffffffff811337fb: rcu_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2707
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff81155960-ffffffff81155bf8: rcu_core (STB_LOCAL)
ffffffff81caf4b5-ffffffff81caf4f9: rcu_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2784
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff8117e330-ffffffff8117e6b0: rcu_core (STB_LOCAL)
ffffffff81e5fd8d-ffffffff81e5fdd2: rcu_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2452
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff811b91b0-ffffffff811b9530: rcu_core (STB_LOCAL)
ffffffff8205a2d8-ffffffff8205a31d: rcu_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2345
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff811cb4d0-ffffffff811cb83c: rcu_core (STB_LOCAL)
ffffffff820d8af1-ffffffff820d8b30: rcu_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2411
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff811df040-ffffffff811df3c9: rcu_core (STB_LOCAL)
ffffffff821b40dc-ffffffff821b4106: rcu_core.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff800010190108)
Location: kernel/rcu/tree.c:2340
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffff800010190108-ffff80001019043c: rcu_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dd9c0)
Location: kernel/rcu/tree.c:2340
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
c03dd9c0-c03ddff8: rcu_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001eb080)
Location: kernel/rcu/tree.c:2340
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
c0000000001eb080-c0000000001eb71c: rcu_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000122b2a)
Location: kernel/rcu/tree.c:2340
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffe000122b2a-ffffffe000122f44: rcu_core (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81121350)
Location: kernel/rcu/tree.c:2340
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff81121350-ffffffff811215b7: rcu_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81112ae0)
Location: kernel/rcu/tree.c:2340
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff81112ae0-ffffffff81112db0: rcu_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f240)
Location: kernel/rcu/tree.c:2340
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff8111f240-ffffffff8111f4a7: rcu_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_core();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112b2f0)
Location: kernel/rcu/tree.c:2340
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core_si
```
**Symbols:**

```
ffffffff8112b2f0-ffffffff8112b5f2: rcu_core (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
