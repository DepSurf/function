# Function: <code>xen_setup_callback_vector</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_setup_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718aec)
Location: drivers/xen/events/events_base.c:1653
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff81718aec-ffffffff81718b07: xen_setup_callback_vector.cold (STB_LOCAL)
ffffffff81718990-ffffffff817189fd: xen_setup_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_setup_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81c04ffd)
Location: drivers/xen/events/events_base.c:2137
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff81c04ffd-ffffffff81c05018: xen_setup_callback_vector.cold (STB_LOCAL)
ffffffff81735ff0-ffffffff8173601d: xen_setup_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_setup_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81bf6c7e)
Location: drivers/xen/events/events_base.c:2184
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff81bf6c7e-ffffffff81bf6c99: xen_setup_callback_vector.cold (STB_LOCAL)
ffffffff81719a80-ffffffff81719aad: xen_setup_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_setup_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81cf5976)
Location: drivers/xen/events/events_base.c:2190
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff81cf5976-ffffffff81cf5991: xen_setup_callback_vector.cold (STB_LOCAL)
ffffffff81797ca0-ffffffff81797ccd: xen_setup_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_setup_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81ebdabf)
Location: drivers/xen/events/events_base.c:2190
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff81ebdabf-ffffffff81ebdad8: xen_setup_callback_vector.cold (STB_LOCAL)
ffffffff818d0d20-ffffffff818d0d61: xen_setup_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_setup_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a225a2)
Location: drivers/xen/events/events_base.c:2193
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
**Symbols:**

```
ffffffff82094797-ffffffff820947ab: xen_setup_callback_vector.cold (STB_LOCAL)
ffffffff81a22560-ffffffff81a225c5: xen_setup_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_setup_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a6b932)
Location: drivers/xen/events/events_base.c:2190
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
**Symbols:**

```
ffffffff8211556d-ffffffff82115581: xen_setup_callback_vector.cold (STB_LOCAL)
ffffffff81a6b8f0-ffffffff81a6b955: xen_setup_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_setup_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abd9d2)
Location: drivers/xen/events/events_base.c:2167
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
**Symbols:**

```
ffffffff821f31f3-ffffffff821f3207: xen_setup_callback_vector.cold (STB_LOCAL)
ffffffff81abd990-ffffffff81abd9f5: xen_setup_callback_vector (STB_GLOBAL)
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
