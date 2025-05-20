# Function: <code>nsset_cred</code>

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
In kernel/nsproxy.c (ffffffff810d668c)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/user_namespace.c (ffffffff81184634)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
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
In kernel/nsproxy.c (ffffffff810d123e)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/user_namespace.c (ffffffff81181654)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
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
In kernel/nsproxy.c (ffffffff810d2e1e)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/user_namespace.c (ffffffff81182774)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
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
In kernel/nsproxy.c (ffffffff810e5f5e)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/user_namespace.c (ffffffff811aa744)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
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
In kernel/nsproxy.c (ffffffff810ffdeb)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/user_namespace.c (ffffffff811dbd84)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
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
In kernel/nsproxy.c (ffffffff81124b5b)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/user_namespace.c (ffffffff812215d4)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
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
In kernel/nsproxy.c (ffffffff81131ea6)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/user_namespace.c (ffffffff81237a84)
Location: include/linux/nsproxy.h:60
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
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
In kernel/nsproxy.c (ffffffff8113ccd6)
Location: include/linux/nsproxy.h:61
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/user_namespace.c (ffffffff812512db)
Location: include/linux/nsproxy.h:61
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
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
