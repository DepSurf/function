# Function: <code>emergency_vmx_disable_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8105076b)
Location: arch/x86/kernel/reboot.c:503
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8105091c)
Location: arch/x86/kernel/reboot.c:524
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/kernel/reboot.c (ffffffff8105318c)
Location: arch/x86/kernel/reboot.c:524
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/kernel/reboot.c (ffffffff81052c6b)
Location: arch/x86/kernel/reboot.c:542
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/kernel/reboot.c (ffffffff81056969)
Location: arch/x86/kernel/reboot.c:546
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/kernel/reboot.c (ffffffff81059780)
Location: arch/x86/kernel/reboot.c:546
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/kernel/reboot.c (ffffffff8105f421)
Location: arch/x86/kernel/reboot.c:546
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/kernel/reboot.c (ffffffff81062833)
Location: arch/x86/kernel/reboot.c:567
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/kernel/reboot.c (ffffffff810630a3)
Location: arch/x86/kernel/reboot.c:567
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void emergency_vmx_disable_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81068f40)
Location: arch/x86/kernel/reboot.c:575
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81068f40-ffffffff81068fce: emergency_vmx_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void emergency_vmx_disable_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8106ab90)
Location: arch/x86/kernel/reboot.c:584
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8106ab90-ffffffff8106ac41: emergency_vmx_disable_all (STB_LOCAL)
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
In arch/x86/kernel/reboot.c (ffffffff8106b81d)
Location: arch/x86/kernel/reboot.c:584
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/kernel/reboot.c (ffffffff8107631a)
Location: arch/x86/kernel/reboot.c:577
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/kernel/reboot.c (ffffffff8108505e)
Location: arch/x86/kernel/reboot.c:577
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/x86/kernel/reboot.c (ffffffff81062b93)
Location: arch/x86/kernel/reboot.c:567
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/kernel/reboot.c (ffffffff81052f63)
Location: arch/x86/kernel/reboot.c:567
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/kernel/reboot.c (ffffffff81063043)
Location: arch/x86/kernel/reboot.c:567
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/kernel/reboot.c (ffffffff81064603)
Location: arch/x86/kernel/reboot.c:567
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
