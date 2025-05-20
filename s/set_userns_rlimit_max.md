# Function: <code>set_userns_rlimit_max</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff83ea4d3e)
Location: include/linux/user_namespace.h:143
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
  - kernel/fork.c:fork_init
  - kernel/fork.c:fork_init
  - kernel/fork.c:fork_init
```
```
In kernel/user_namespace.c (ffffffff8122190a)
Location: include/linux/user_namespace.h:143
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
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
In kernel/fork.c (ffffffff836c90be)
Location: include/linux/user_namespace.h:143
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
  - kernel/fork.c:fork_init
  - kernel/fork.c:fork_init
  - kernel/fork.c:fork_init
```
```
In kernel/user_namespace.c (ffffffff81237dbf)
Location: include/linux/user_namespace.h:143
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
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
In kernel/fork.c (ffffffff838f9cf9)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
  - kernel/fork.c:fork_init
  - kernel/fork.c:fork_init
  - kernel/fork.c:fork_init
```
```
In kernel/user_namespace.c (ffffffff812518bf)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
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
