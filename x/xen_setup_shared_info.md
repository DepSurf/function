# Function: <code>xen_setup_shared_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_setup_shared_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d5a0)
Location: arch/x86/xen/enlighten.c:1095
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101d5a0-ffffffff8101d607: xen_setup_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_setup_shared_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c940)
Location: arch/x86/xen/enlighten.c:1119
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101c940-ffffffff8101c9a4: xen_setup_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_setup_shared_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d070)
Location: arch/x86/xen/enlighten.c:1110
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101d070-ffffffff8101d0d4: xen_setup_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_setup_shared_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101fb10)
Location: arch/x86/xen/enlighten_pv.c:925
Inline: False
Direct callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
**Symbols:**

```
ffffffff8101fb10-ffffffff8101fb5c: xen_setup_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_setup_shared_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81020770)
Location: arch/x86/xen/enlighten_pv.c:974
Inline: False
Direct callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
**Symbols:**

```
ffffffff81020770-ffffffff810207c9: xen_setup_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_setup_shared_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81021200)
Location: arch/x86/xen/enlighten_pv.c:950
Inline: False
Direct callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
**Symbols:**

```
ffffffff81021200-ffffffff81021260: xen_setup_shared_info (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
