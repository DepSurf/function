# Function: <code>xen_do_read_msr</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 xen_do_read_msr(unsigned int msr, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81036ff0)
Location: arch/x86/xen/enlighten_pv.c:931
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
**Symbols:**

```
ffffffff81036ff0-ffffffff8103709d: xen_do_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 xen_do_read_msr(unsigned int msr, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81036f40)
Location: arch/x86/xen/enlighten_pv.c:986
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
**Symbols:**

```
ffffffff81036f40-ffffffff81036fed: xen_do_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 xen_do_read_msr(unsigned int msr, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8103d1c0)
Location: arch/x86/xen/enlighten_pv.c:1012
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
**Symbols:**

```
ffffffff8103d1c0-ffffffff8103d26d: xen_do_read_msr (STB_LOCAL)
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
