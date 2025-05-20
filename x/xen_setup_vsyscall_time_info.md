# Function: <code>xen_setup_vsyscall_time_info</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff826a9dc4)
Location: arch/x86/xen/time.c:419
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
In arch/x86/xen/time.c (ffffffff826d2f2a)
Location: arch/x86/xen/time.c:419
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
In arch/x86/xen/time.c (ffffffff82888fba)
Location: arch/x86/xen/time.c:432
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
In arch/x86/xen/time.c (ffffffff828a0263)
Location: arch/x86/xen/time.c:432
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
In arch/x86/xen/time.c (ffffffff828a3353)
Location: arch/x86/xen/time.c:432
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_setup_vsyscall_time_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81020a07)
Location: arch/x86/xen/time.c:440
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
```
**Symbols:**

```
ffffffff81020a07-ffffffff81020ad8: xen_setup_vsyscall_time_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_setup_vsyscall_time_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81bd26f4)
Location: arch/x86/xen/time.c:441
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
```
**Symbols:**

```
ffffffff81bd26f4-ffffffff81bd27c5: xen_setup_vsyscall_time_info (STB_LOCAL)
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
In arch/x86/xen/time.c (ffffffff831bfd42)
Location: arch/x86/xen/time.c:436
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
In arch/x86/xen/time.c (ffffffff832a0459)
Location: arch/x86/xen/time.c:436
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
In arch/x86/xen/time.c (ffffffff8344f31c)
Location: arch/x86/xen/time.c:436
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
In arch/x86/xen/time.c (ffffffff83e6ace6)
Location: arch/x86/xen/time.c:436
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
In arch/x86/xen/time.c (ffffffff8368b7bd)
Location: arch/x86/xen/time.c:444
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
In arch/x86/xen/time.c (ffffffff838bb37d)
Location: arch/x86/xen/time.c:444
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
In arch/x86/xen/time.c (ffffffff82891353)
Location: arch/x86/xen/time.c:432
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
In arch/x86/xen/time.c (ffffffff828a4353)
Location: arch/x86/xen/time.c:432
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
In arch/x86/xen/time.c (ffffffff828a4343)
Location: arch/x86/xen/time.c:432
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
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
