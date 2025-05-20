# Function: <code>__se_compat_sys_arch_prctl</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102c265)
Location: arch/x86/kernel/process_64.c:715
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff8102d3e5)
Location: arch/x86/kernel/process_64.c:820
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff8102f115)
Location: arch/x86/kernel/process_64.c:811
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff8102fa75)
Location: arch/x86/kernel/process_64.c:811
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff81032245)
Location: arch/x86/kernel/process_64.c:722
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff81032d05)
Location: arch/x86/kernel/process_64.c:828
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff81034815)
Location: arch/x86/kernel/process_64.c:828
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff81039b15)
Location: arch/x86/kernel/process_64.c:854
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__x64_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff81040ad5)
Location: arch/x86/kernel/process_64.c:853
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff81049df5)
Location: arch/x86/kernel/process_64.c:854
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff8104a415)
Location: arch/x86/kernel/process_64.c:917
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff81051675)
Location: arch/x86/kernel/process_64.c:925
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff8102fbd5)
Location: arch/x86/kernel/process_64.c:811
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff8101f5f5)
Location: arch/x86/kernel/process_64.c:811
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff8102fa35)
Location: arch/x86/kernel/process_64.c:811
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
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
In arch/x86/kernel/process_64.c (ffffffff81030885)
Location: arch/x86/kernel/process_64.c:811
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl
```
</details>
</li>
</ul>

## Differences
