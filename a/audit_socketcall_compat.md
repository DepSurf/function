# Function: <code>audit_socketcall_compat</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817fb1cc)
Location: include/linux/audit.h:387
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
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
In net/compat.c (ffffffff81878b4c)
Location: include/linux/audit.h:380
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
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
In net/compat.c (ffffffff818ca01e)
Location: include/linux/audit.h:384
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
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
In net/compat.c (ffffffff818f503c)
Location: include/linux/audit.h:383
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
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
In net/compat.c (ffffffff81953ede)
Location: include/linux/audit.h:416
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff8198a42e)
Location: include/linux/audit.h:409
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff81a627be)
Location: include/linux/audit.h:428
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff81a6a8de)
Location: include/linux/audit.h:445
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff81a5300e)
Location: include/linux/audit.h:445
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff81b0bce9)
Location: include/linux/audit.h:445
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff81c92433)
Location: include/linux/audit.h:472
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff81e4daa3)
Location: include/linux/audit.h:469
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff81ea90f3)
Location: include/linux/audit.h:468
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff81f6bbb3)
Location: include/linux/audit.h:467
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffff800010c32fc8)
Location: include/linux/audit.h:409
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (c000000000d2bf2c)
Location: include/linux/audit.h:409
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff8192a29e)
Location: include/linux/audit.h:409
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff818e404e)
Location: include/linux/audit.h:409
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff8197b42e)
Location: include/linux/audit.h:409
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In net/compat.c (ffffffff8199d97e)
Location: include/linux/audit.h:409
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
</details>
</li>
</ul>

## Differences
