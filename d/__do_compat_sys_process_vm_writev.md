# Function: <code>__do_compat_sys_process_vm_writev</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff81244675)
Location: mm/process_vm_access.c:365
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
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
In mm/process_vm_access.c (ffffffff81258d75)
Location: mm/process_vm_access.c:365
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
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
In mm/process_vm_access.c (ffffffff8126c555)
Location: mm/process_vm_access.c:361
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
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
In mm/process_vm_access.c (ffffffff8127b365)
Location: mm/process_vm_access.c:361
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
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
In mm/process_vm_access.c (ffffffff812ad4a5)
Location: mm/process_vm_access.c:363
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffff800010312878)
Location: mm/process_vm_access.c:361
Inline: True
Inline callers:
  - mm/process_vm_access.c:__arm64_compat_sys_process_vm_writev
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (c0000000003e3830)
Location: mm/process_vm_access.c:361
Inline: True
Inline callers:
  - mm/process_vm_access.c:__se_compat_sys_process_vm_writev
```
</details>
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
In mm/process_vm_access.c (ffffffff812739b5)
Location: mm/process_vm_access.c:361
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
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
In mm/process_vm_access.c (ffffffff81265925)
Location: mm/process_vm_access.c:361
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
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
In mm/process_vm_access.c (ffffffff81271755)
Location: mm/process_vm_access.c:361
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
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
In mm/process_vm_access.c (ffffffff812811c5)
Location: mm/process_vm_access.c:361
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_writev
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev
```
</details>
</li>
</ul>

## Differences
