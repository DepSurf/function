# Function: <code>__do_compat_sys_process_vm_readv</code>

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
In mm/process_vm_access.c (ffffffff81244615)
Location: mm/process_vm_access.c:354
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
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
In mm/process_vm_access.c (ffffffff81258d15)
Location: mm/process_vm_access.c:354
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
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
In mm/process_vm_access.c (ffffffff8126c4f5)
Location: mm/process_vm_access.c:350
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
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
In mm/process_vm_access.c (ffffffff8127b305)
Location: mm/process_vm_access.c:350
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
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
In mm/process_vm_access.c (ffffffff812ad475)
Location: mm/process_vm_access.c:352
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
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
In mm/process_vm_access.c (ffff800010312830)
Location: mm/process_vm_access.c:350
Inline: True
Inline callers:
  - mm/process_vm_access.c:__arm64_compat_sys_process_vm_readv
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
In mm/process_vm_access.c (c0000000003e3800)
Location: mm/process_vm_access.c:350
Inline: True
Inline callers:
  - mm/process_vm_access.c:__se_compat_sys_process_vm_readv
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
In mm/process_vm_access.c (ffffffff81273955)
Location: mm/process_vm_access.c:350
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
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
In mm/process_vm_access.c (ffffffff812658c5)
Location: mm/process_vm_access.c:350
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
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
In mm/process_vm_access.c (ffffffff812716f5)
Location: mm/process_vm_access.c:350
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
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
In mm/process_vm_access.c (ffffffff81281165)
Location: mm/process_vm_access.c:350
Inline: True
Inline callers:
  - mm/process_vm_access.c:__x32_compat_sys_process_vm_readv
  - mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv
```
</details>
</li>
</ul>

## Differences
