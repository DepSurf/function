# Function: <code>vmware_paravirt_ops_setup</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81fd0cf7)
Location: arch/x86/kernel/cpu/vmware.c:105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff820b181d)
Location: arch/x86/kernel/cpu/vmware.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff826b806e)
Location: arch/x86/kernel/cpu/vmware.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff826e1d5c)
Location: arch/x86/kernel/cpu/vmware.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff82898695)
Location: arch/x86/kernel/cpu/vmware.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff828b026f)
Location: arch/x86/kernel/cpu/vmware.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff828b35f6)
Location: arch/x86/kernel/cpu/vmware.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vmware_paravirt_ops_setup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff82cd8485)
Location: arch/x86/kernel/cpu/vmware.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
**Symbols:**

```
ffffffff82cd8485-ffffffff82cd85a3: vmware_paravirt_ops_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vmware_paravirt_ops_setup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff82fc4857)
Location: arch/x86/kernel/cpu/vmware.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
**Symbols:**

```
ffffffff82fc4857-ffffffff82fc4975: vmware_paravirt_ops_setup (STB_LOCAL)
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
In arch/x86/kernel/cpu/vmware.c (ffffffff831cf120)
Location: arch/x86/kernel/cpu/vmware.c:329
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff832b147b)
Location: arch/x86/kernel/cpu/vmware.c:329
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff8346275d)
Location: arch/x86/kernel/cpu/vmware.c:329
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff83e84b52)
Location: arch/x86/kernel/cpu/vmware.c:329
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff836a80b2)
Location: arch/x86/kernel/cpu/vmware.c:329
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff838d85f0)
Location: arch/x86/kernel/cpu/vmware.c:329
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff828a1615)
Location: arch/x86/kernel/cpu/vmware.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff828997ee)
Location: arch/x86/kernel/cpu/vmware.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff828b45d8)
Location: arch/x86/kernel/cpu/vmware.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff828b45f9)
Location: arch/x86/kernel/cpu/vmware.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
