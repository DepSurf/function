# Function: <code>copy_compat_semid_from_user</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813ad219)
Location: ipc/sem.c:1636
Inline: True
Inline callers:
  - ipc/sem.c:C_SYSC_semctl
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
In ipc/sem.c (ffffffff813dcd39)
Location: ipc/sem.c:1703
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff813f7424)
Location: ipc/sem.c:1710
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff81423543)
Location: ipc/sem.c:1719
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff8143d283)
Location: ipc/sem.c:1719
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff8148de69)
Location: ipc/sem.c:1735
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff814ab5a9)
Location: ipc/sem.c:1734
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff814b0549)
Location: ipc/sem.c:1736
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff81508619)
Location: ipc/sem.c:1739
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff8159a66b)
Location: ipc/sem.c:1737
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff8164391b)
Location: ipc/sem.c:1737
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff8167be05)
Location: ipc/sem.c:1737
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff816b81d5)
Location: ipc/sem.c:1737
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffff80001052510c)
Location: ipc/sem.c:1719
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (c00000000066e340)
Location: ipc/sem.c:1719
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff81435863)
Location: ipc/sem.c:1719
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff814262e3)
Location: ipc/sem.c:1719
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff81431a03)
Location: ipc/sem.c:1719
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
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
In ipc/sem.c (ffffffff81448ad3)
Location: ipc/sem.c:1719
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
</details>
</li>
</ul>

## Differences
