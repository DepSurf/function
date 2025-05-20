# Function: <code>do_kernel_power_off</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_kernel_power_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81103240)
Location: kernel/reboot.c:622
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_power_off
```
**Symbols:**

```
ffffffff81103240-ffffffff8110329a: do_kernel_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_kernel_power_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff811288a0)
Location: kernel/reboot.c:639
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_power_off
```
**Symbols:**

```
ffffffff811288a0-ffffffff811288fa: do_kernel_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_kernel_power_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81135d50)
Location: kernel/reboot.c:639
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_power_off
```
**Symbols:**

```
ffffffff81135d50-ffffffff81135daa: do_kernel_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_kernel_power_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81140df0)
Location: kernel/reboot.c:654
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_machine_power_off
  - arch/x86/kernel/reboot.c:native_machine_power_off
```
**Symbols:**

```
ffffffff81140df0-ffffffff81140e4a: do_kernel_power_off (STB_GLOBAL)
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
