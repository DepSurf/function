# Function: <code>vmware_set_capabilities</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff820b18bf)
Location: arch/x86/kernel/cpu/vmware.c:128
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
In arch/x86/kernel/cpu/vmware.c (ffffffff826b8110)
Location: arch/x86/kernel/cpu/vmware.c:128
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
In arch/x86/kernel/cpu/vmware.c (ffffffff826e1dfe)
Location: arch/x86/kernel/cpu/vmware.c:128
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
In arch/x86/kernel/cpu/vmware.c (ffffffff82898737)
Location: arch/x86/kernel/cpu/vmware.c:128
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
In arch/x86/kernel/cpu/vmware.c (ffffffff828b0311)
Location: arch/x86/kernel/cpu/vmware.c:128
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
In arch/x86/kernel/cpu/vmware.c (ffffffff828b3698)
Location: arch/x86/kernel/cpu/vmware.c:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff82cd86c4)
Location: arch/x86/kernel/cpu/vmware.c:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff82fc4a96)
Location: arch/x86/kernel/cpu/vmware.c:377
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
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
In arch/x86/kernel/cpu/vmware.c (ffffffff831cf249)
Location: arch/x86/kernel/cpu/vmware.c:378
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
In arch/x86/kernel/cpu/vmware.c (ffffffff832b15ea)
Location: arch/x86/kernel/cpu/vmware.c:378
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vmware_set_capabilities();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff834624d3)
Location: arch/x86/kernel/cpu/vmware.c:378
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
**Symbols:**

```
ffffffff834624d3-ffffffff8346254e: vmware_set_capabilities (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vmware_set_capabilities();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff83e84850)
Location: arch/x86/kernel/cpu/vmware.c:378
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
**Symbols:**

```
ffffffff83e84850-ffffffff83e848da: vmware_set_capabilities (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vmware_set_capabilities();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff836a7da0)
Location: arch/x86/kernel/cpu/vmware.c:378
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
**Symbols:**

```
ffffffff836a7da0-ffffffff836a7e2a: vmware_set_capabilities (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vmware_set_capabilities();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff838d82f0)
Location: arch/x86/kernel/cpu/vmware.c:378
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
**Symbols:**

```
ffffffff838d82f0-ffffffff838d837a: vmware_set_capabilities (STB_LOCAL)
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
In arch/x86/kernel/cpu/vmware.c (ffffffff828a16b7)
Location: arch/x86/kernel/cpu/vmware.c:163
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
In arch/x86/kernel/cpu/vmware.c (ffffffff82899890)
Location: arch/x86/kernel/cpu/vmware.c:163
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
In arch/x86/kernel/cpu/vmware.c (ffffffff828b467a)
Location: arch/x86/kernel/cpu/vmware.c:163
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
In arch/x86/kernel/cpu/vmware.c (ffffffff828b469b)
Location: arch/x86/kernel/cpu/vmware.c:163
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
