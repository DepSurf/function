# Function: <code>init_hvm_pv_info</code>

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
In arch/x86/xen/enlighten.c (ffffffff81f60e03)
Location: arch/x86/xen/enlighten.c:1771
Inline: True
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
In arch/x86/xen/enlighten.c (ffffffff81f88a5b)
Location: arch/x86/xen/enlighten.c:1792
Inline: True
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
In arch/x86/xen/enlighten.c (ffffffff81fc3e49)
Location: arch/x86/xen/enlighten.c:1797
Inline: True
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
In arch/x86/xen/enlighten_hvm.c (ffffffff820a3b86)
Location: arch/x86/xen/enlighten_hvm.c:69
Inline: True
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
In arch/x86/xen/enlighten_hvm.c (ffffffff826aa285)
Location: arch/x86/xen/enlighten_hvm.c:70
Inline: True
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
In arch/x86/xen/enlighten_hvm.c (ffffffff826d33e8)
Location: arch/x86/xen/enlighten_hvm.c:83
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff8288930c)
Location: arch/x86/xen/enlighten_hvm.c:85
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff828a068d)
Location: arch/x86/xen/enlighten_hvm.c:85
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff828a377d)
Location: arch/x86/xen/enlighten_hvm.c:85
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_hvm_pv_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff82cc9a25)
Location: arch/x86/xen/enlighten_hvm.c:86
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
**Symbols:**

```
ffffffff82cc9a25-ffffffff82cc9b67: init_hvm_pv_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_hvm_pv_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff82fb588a)
Location: arch/x86/xen/enlighten_hvm.c:87
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
**Symbols:**

```
ffffffff82fb588a-ffffffff82fb59cc: init_hvm_pv_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_hvm_pv_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff831c0095)
Location: arch/x86/xen/enlighten_hvm.c:87
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
**Symbols:**

```
ffffffff831c0095-ffffffff831c01d7: init_hvm_pv_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_hvm_pv_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff832a0847)
Location: arch/x86/xen/enlighten_hvm.c:87
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
**Symbols:**

```
ffffffff832a0847-ffffffff832a09a7: init_hvm_pv_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_hvm_pv_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8344f82d)
Location: arch/x86/xen/enlighten_hvm.c:89
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
**Symbols:**

```
ffffffff8344f82d-ffffffff8344f99e: init_hvm_pv_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_hvm_pv_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff83e6b290)
Location: arch/x86/xen/enlighten_hvm.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
**Symbols:**

```
ffffffff83e6b290-ffffffff83e6b4f8: init_hvm_pv_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_hvm_pv_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8368bd30)
Location: arch/x86/xen/enlighten_hvm.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
**Symbols:**

```
ffffffff8368bd30-ffffffff8368bf98: init_hvm_pv_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_hvm_pv_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff838bb8f0)
Location: arch/x86/xen/enlighten_hvm.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
**Symbols:**

```
ffffffff838bb8f0-ffffffff838bbb58: init_hvm_pv_info (STB_LOCAL)
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
In arch/x86/xen/enlighten_hvm.c (ffffffff8289179e)
Location: arch/x86/xen/enlighten_hvm.c:92
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a477d)
Location: arch/x86/xen/enlighten_hvm.c:85
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff828a4751)
Location: arch/x86/xen/enlighten_hvm.c:85
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
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
