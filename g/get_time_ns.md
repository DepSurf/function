# Function: <code>get_time_ns</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d5bb9)
Location: include/linux/time_namespace.h:37
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/time/namespace.c (ffffffff8115a28f)
Location: include/linux/time_namespace.h:37
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
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
In kernel/nsproxy.c (ffffffff810d0699)
Location: include/linux/time_namespace.h:36
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/time/namespace.c (ffffffff811562de)
Location: include/linux/time_namespace.h:36
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
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
In kernel/nsproxy.c (ffffffff810d2279)
Location: include/linux/time_namespace.h:36
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/time/namespace.c (ffffffff811576de)
Location: include/linux/time_namespace.h:36
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
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
In kernel/nsproxy.c (ffffffff810e53b9)
Location: include/linux/time_namespace.h:36
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/time/namespace.c (ffffffff8117c54e)
Location: include/linux/time_namespace.h:36
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
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
In kernel/nsproxy.c (ffffffff810ff1ad)
Location: include/linux/time_namespace.h:36
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/time/namespace.c (ffffffff811b1f77)
Location: include/linux/time_namespace.h:36
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
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
In kernel/nsproxy.c (ffffffff81123e9d)
Location: include/linux/time_namespace.h:36
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/time/namespace.c (ffffffff811f2da7)
Location: include/linux/time_namespace.h:36
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
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
In kernel/nsproxy.c (ffffffff81131169)
Location: include/linux/time_namespace.h:36
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/time/namespace.c (ffffffff81207527)
Location: include/linux/time_namespace.h:36
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
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
In kernel/nsproxy.c (ffffffff8113beb9)
Location: include/linux/time_namespace.h:39
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/time/namespace.c (ffffffff8121e737)
Location: include/linux/time_namespace.h:39
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
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
