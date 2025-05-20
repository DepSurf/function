# Function: <code>xen_set_upcall_vector</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int xen_set_upcall_vector(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff83eea951)
Location: drivers/xen/events/events_base.c:2224
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81a225e0-ffffffff81a22695: xen_set_upcall_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int xen_set_upcall_vector(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff83710341)
Location: drivers/xen/events/events_base.c:2221
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81a6b970-ffffffff81a6ba25: xen_set_upcall_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int xen_set_upcall_vector(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff83943cc1)
Location: drivers/xen/events/events_base.c:2198
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81abda10-ffffffff81abdac5: xen_set_upcall_vector (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
