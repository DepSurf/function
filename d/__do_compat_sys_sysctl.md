# Function: <code>__do_compat_sys_sysctl</code>

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
In kernel/sysctl_binary.c (ffffffff8109912e)
Location: kernel/sysctl_binary.c:1443
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
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
In kernel/sysctl_binary.c (ffffffff810a14ae)
Location: kernel/sysctl_binary.c:1444
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
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
In kernel/sysctl_binary.c (ffffffff810a5efe)
Location: kernel/sysctl_binary.c:1444
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
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
In kernel/sysctl_binary.c (ffffffff810ac4de)
Location: kernel/sysctl_binary.c:1444
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
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
In kernel/sysctl_binary.c (ffffffff810b40be)
Location: kernel/sysctl_binary.c:139
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
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
In kernel/sysctl_binary.c (ffff80001010554c)
Location: kernel/sysctl_binary.c:1444
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
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
In kernel/sysctl_binary.c (c00000000014cc98)
Location: kernel/sysctl_binary.c:1444
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__se_compat_sys_sysctl
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
In kernel/sysctl_binary.c (ffffffff810a686e)
Location: kernel/sysctl_binary.c:1444
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
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
In kernel/sysctl_binary.c (ffffffff8109524e)
Location: kernel/sysctl_binary.c:1444
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
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
In kernel/sysctl_binary.c (ffffffff810a5dae)
Location: kernel/sysctl_binary.c:1444
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
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
In kernel/sysctl_binary.c (ffffffff810ade6e)
Location: kernel/sysctl_binary.c:1444
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__x32_compat_sys_sysctl
  - kernel/sysctl_binary.c:__ia32_compat_sys_sysctl
```
</details>
</li>
</ul>

## Differences
