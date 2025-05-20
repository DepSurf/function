# Function: <code>kernel_can_power_off</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool kernel_can_power_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff8110317f)
Location: kernel/reboot.c:649
Inline: True
Inline callers:
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff811021f0-ffffffff81102225: kernel_can_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool kernel_can_power_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81128695)
Location: kernel/reboot.c:666
Inline: True
Inline callers:
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff811274c0-ffffffff811274f5: kernel_can_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool kernel_can_power_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81135b26)
Location: kernel/reboot.c:666
Inline: True
Inline callers:
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81134960-ffffffff81134995: kernel_can_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool kernel_can_power_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81140ba6)
Location: kernel/reboot.c:681
Inline: True
Inline callers:
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_power_off
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff8113f950-ffffffff8113f985: kernel_can_power_off (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
