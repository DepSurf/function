# Function: <code>copy_compat_shmid_from_user</code>

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
In ipc/shm.c (ffffffff813aede5)
Location: ipc/shm.c:1205
Inline: True
Inline callers:
  - ipc/shm.c:C_SYSC_shmctl
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
In ipc/shm.c (ffffffff813df0d1)
Location: ipc/shm.c:1280
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff813f988c)
Location: ipc/shm.c:1309
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff81425d86)
Location: ipc/shm.c:1322
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff8143fad6)
Location: ipc/shm.c:1322
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff81490126)
Location: ipc/shm.c:1322
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff814ad846)
Location: ipc/shm.c:1321
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff814b36c4)
Location: ipc/shm.c:1321
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff8150bd34)
Location: ipc/shm.c:1417
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff8159de64)
Location: ipc/shm.c:1411
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff81647454)
Location: ipc/shm.c:1427
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff8167f98c)
Location: ipc/shm.c:1427
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff816bbd7c)
Location: ipc/shm.c:1423
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffff800010528274)
Location: ipc/shm.c:1322
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (c000000000672d60)
Location: ipc/shm.c:1322
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff814380b6)
Location: ipc/shm.c:1322
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff81428b26)
Location: ipc/shm.c:1322
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff81434256)
Location: ipc/shm.c:1322
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/shm.c (ffffffff8144b366)
Location: ipc/shm.c:1322
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
```
</details>
</li>
</ul>

## Differences
