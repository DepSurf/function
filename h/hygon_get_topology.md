# Function: <code>hygon_get_topology</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff81048495)
Location: arch/x86/kernel/cpu/hygon.c:63
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b235)
Location: arch/x86/kernel/cpu/hygon.c:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bc35)
Location: arch/x86/kernel/cpu/hygon.c:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hygon_get_topology(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff810501d0)
Location: arch/x86/kernel/cpu/hygon.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff810501d0-ffffffff8105030c: hygon_get_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hygon_get_topology(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f550)
Location: arch/x86/kernel/cpu/hygon.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8104f550-ffffffff8104f698: hygon_get_topology (STB_LOCAL)
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
In arch/x86/kernel/cpu/hygon.c (ffffffff810510bc)
Location: arch/x86/kernel/cpu/hygon.c:63
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
In arch/x86/kernel/cpu/hygon.c (ffffffff81059526)
Location: arch/x86/kernel/cpu/hygon.c:63
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
In arch/x86/kernel/cpu/hygon.c (ffffffff81065be8)
Location: arch/x86/kernel/cpu/hygon.c:63
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
In arch/x86/kernel/cpu/hygon.c (ffffffff81074f28)
Location: arch/x86/kernel/cpu/hygon.c:63
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
In arch/x86/kernel/cpu/hygon.c (ffffffff81077098)
Location: arch/x86/kernel/cpu/hygon.c:63
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e5fd)
Location: arch/x86/kernel/cpu/hygon.c:64
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bda5)
Location: arch/x86/kernel/cpu/hygon.c:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8103afa1)
Location: arch/x86/kernel/cpu/hygon.c:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bbe5)
Location: arch/x86/kernel/cpu/hygon.c:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104cff5)
Location: arch/x86/kernel/cpu/hygon.c:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
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
</ul>
