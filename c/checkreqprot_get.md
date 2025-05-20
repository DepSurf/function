# Function: <code>checkreqprot_get</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814cf846)
Location: security/selinux/include/security.h:147
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_mmap_file
```
```
In security/selinux/selinuxfs.c (ffffffff814d7f0c)
Location: security/selinux/include/security.h:147
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d5f83)
Location: security/selinux/include/security.h:147
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_mmap_file
```
```
In security/selinux/selinuxfs.c (ffffffff814de87c)
Location: security/selinux/include/security.h:147
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
```
```
In security/selinux/ima.c (ffffffff814f5e6b)
Location: security/selinux/include/security.h:147
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_collect_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152eae7)
Location: security/selinux/include/security.h:147
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_mmap_file
```
```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:147
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
```
```
In security/selinux/ima.c (ffffffff8155094a)
Location: security/selinux/include/security.h:147
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_collect_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c5114)
Location: security/selinux/include/security.h:149
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_mmap_file
```
```
In security/selinux/selinuxfs.c (ffffffff815cfde6)
Location: security/selinux/include/security.h:149
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
```
```
In security/selinux/ima.c (ffffffff815e9dfa)
Location: security/selinux/include/security.h:149
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_collect_state
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81671cb4)
Location: security/selinux/include/security.h:149
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_mmap_file
```
```
In security/selinux/selinuxfs.c (ffffffff8167d8d6)
Location: security/selinux/include/security.h:149
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
```
```
In security/selinux/ima.c (ffffffff8169978f)
Location: security/selinux/include/security.h:149
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_collect_state
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:144
Inline: True
```
```
In security/selinux/ima.c (0)
Location: security/selinux/include/security.h:144
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:143
Inline: True
```
```
In security/selinux/ima.c (0)
Location: security/selinux/include/security.h:143
Inline: True
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
