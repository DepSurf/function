# Function: <code>__compat_sys_recvfrom</code>

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
In net/compat.c (ffffffff818ca16e)
Location: net/compat.c:794
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff818f52c8)
Location: net/compat.c:799
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff81953f2f)
Location: net/compat.c:680
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff8198a485)
Location: net/compat.c:680
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff81a62815)
Location: net/compat.c:505
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff81a6a935)
Location: net/compat.c:385
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff81a53065)
Location: net/compat.c:385
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff81b0bd7f)
Location: net/compat.c:385
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x64_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x64_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff81c924cd)
Location: net/compat.c:385
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff81e4db3d)
Location: net/compat.c:383
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff81ea9294)
Location: net/compat.c:384
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff81f6bd54)
Location: net/compat.c:384
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffff800010c33174)
Location: net/compat.c:680
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__arm64_compat_sys_recvfrom
  - net/compat.c:__arm64_compat_sys_recv
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
In net/compat.c (c000000000d2c150)
Location: net/compat.c:680
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__se_compat_sys_recvfrom
  - net/compat.c:__se_compat_sys_recv
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
In net/compat.c (ffffffff8192a2f5)
Location: net/compat.c:680
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff818e40a5)
Location: net/compat.c:680
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff8197b485)
Location: net/compat.c:680
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
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
In net/compat.c (ffffffff8199d9d5)
Location: net/compat.c:680
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
</details>
</li>
</ul>

## Differences
