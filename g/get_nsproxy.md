# Function: <code>get_nsproxy</code>

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
In kernel/nsproxy.c (ffffffff810a109b)
Location: include/linux/nsproxy.h:82
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810a47ab)
Location: include/linux/nsproxy.h:82
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810aa40b)
Location: include/linux/nsproxy.h:82
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810a6f8b)
Location: include/linux/nsproxy.h:82
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810ad714)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810b4474)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810bd5c4)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810c361b)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810cc72b)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810d5fd5)
Location: include/linux/nsproxy.h:109
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:copy_namespaces
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d0b03)
Location: include/linux/nsproxy.h:109
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:copy_namespaces
```
```
In fs/io_uring.c (ffffffff813959a6)
Location: include/linux/nsproxy.h:109
Inline: True
Inline callers:
  - fs/io_uring.c:io_grab_identity
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
In kernel/nsproxy.c (ffffffff810d26e3)
Location: include/linux/nsproxy.h:109
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810e5823)
Location: include/linux/nsproxy.h:109
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810ff640)
Location: include/linux/nsproxy.h:109
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff81124370)
Location: include/linux/nsproxy.h:110
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff81131670)
Location: include/linux/nsproxy.h:110
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff8113c400)
Location: include/linux/nsproxy.h:110
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:copy_namespaces
```
</details>
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
In kernel/nsproxy.c (ffff80001012b448)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (c037ba08)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (c000000000173e5c)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffe0000e02bc)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
```
</details>
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
In kernel/nsproxy.c (ffffffff810c6aab)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810b52cb)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810c5ffb)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
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
In kernel/nsproxy.c (ffffffff810ce44e)
Location: include/linux/nsproxy.h:83
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
```
</details>
</li>
</ul>

## Differences
