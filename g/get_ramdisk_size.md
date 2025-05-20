# Function: <code>get_ramdisk_size</code>

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
In arch/x86/kernel/setup.c (ffffffff81f65de7)
Location: arch/x86/kernel/setup.c:312
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff81f8dc60)
Location: arch/x86/kernel/setup.c:314
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff81fc9024)
Location: arch/x86/kernel/setup.c:314
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff820a9788)
Location: arch/x86/kernel/setup.c:318
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff826b02d2)
Location: arch/x86/kernel/setup.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff826d9965)
Location: arch/x86/kernel/setup.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff8288fd49)
Location: arch/x86/kernel/setup.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828a7543)
Location: arch/x86/kernel/setup.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828aa594)
Location: arch/x86/kernel/setup.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 get_ramdisk_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff82ccf2f8)
Location: arch/x86/kernel/setup.c:246
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_initrd
  - arch/x86/kernel/setup.c:relocate_initrd
```
**Symbols:**

```
ffffffff82ccf2f8-ffffffff82ccf31f: get_ramdisk_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 get_ramdisk_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff82fbb1be)
Location: arch/x86/kernel/setup.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_initrd
  - arch/x86/kernel/setup.c:relocate_initrd
```
**Symbols:**

```
ffffffff82fbb1be-ffffffff82fbb1e5: get_ramdisk_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 get_ramdisk_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff831c5a36)
Location: arch/x86/kernel/setup.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff831c5a36-ffffffff831c5a5d: get_ramdisk_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 get_ramdisk_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff832a67b6)
Location: arch/x86/kernel/setup.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
```
**Symbols:**

```
ffffffff832a67b6-ffffffff832a67dd: get_ramdisk_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 get_ramdisk_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff83455a11)
Location: arch/x86/kernel/setup.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
```
**Symbols:**

```
ffffffff83455a11-ffffffff83455a3e: get_ramdisk_size (STB_LOCAL)
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
In arch/x86/kernel/setup.c (ffffffff83e749d3)
Location: arch/x86/kernel/setup.c:252
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
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
In arch/x86/kernel/setup.c (ffffffff836964a5)
Location: arch/x86/kernel/setup.c:246
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
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
In arch/x86/kernel/setup.c (ffffffff838c60fb)
Location: arch/x86/kernel/setup.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
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
In arch/x86/kernel/setup.c (ffffffff828985a4)
Location: arch/x86/kernel/setup.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828908b4)
Location: arch/x86/kernel/setup.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828ab594)
Location: arch/x86/kernel/setup.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828ab5a4)
Location: arch/x86/kernel/setup.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
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
</ul>
