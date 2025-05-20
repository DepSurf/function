# Function: <code>__do_compat_sys_recvmmsg_time32</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81953cb5)
Location: net/compat.c:710
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff8198a205)
Location: net/compat.c:710
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff81a62595)
Location: net/compat.c:535
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff81a6a835)
Location: net/compat.c:415
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff81a52f75)
Location: net/compat.c:415
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff81b0bc45)
Location: net/compat.c:415
Inline: True
Inline callers:
  - net/compat.c:__x64_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff81c92365)
Location: net/compat.c:415
Inline: True
Inline callers:
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff81e4d9c5)
Location: net/compat.c:413
Inline: True
Inline callers:
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff81ea9015)
Location: net/compat.c:414
Inline: True
Inline callers:
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff81f6bad5)
Location: net/compat.c:414
Inline: True
Inline callers:
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffff800010c328f8)
Location: net/compat.c:710
Inline: True
Inline callers:
  - net/compat.c:__arm64_compat_sys_recvmmsg_time32
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
In net/compat.c (c000000000d2bc5c)
Location: net/compat.c:710
Inline: True
Inline callers:
  - net/compat.c:__se_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff8192a075)
Location: net/compat.c:710
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff818e3e25)
Location: net/compat.c:710
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff8197b205)
Location: net/compat.c:710
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
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
In net/compat.c (ffffffff8199d755)
Location: net/compat.c:710
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
```
</details>
</li>
</ul>

## Differences
