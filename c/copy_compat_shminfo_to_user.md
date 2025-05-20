# Function: <code>copy_compat_shminfo_to_user</code>

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
In ipc/shm.c (ffffffff813aee4b)
Location: ipc/shm.c:1133
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
In ipc/shm.c (ffffffff813df176)
Location: ipc/shm.c:1205
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
In ipc/shm.c (ffffffff813f978d)
Location: ipc/shm.c:1234
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
In ipc/shm.c (ffffffff81425dea)
Location: ipc/shm.c:1247
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
In ipc/shm.c (ffffffff8143fb3a)
Location: ipc/shm.c:1247
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
In ipc/shm.c (ffffffff8149018a)
Location: ipc/shm.c:1247
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
In ipc/shm.c (ffffffff814ad8aa)
Location: ipc/shm.c:1246
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
In ipc/shm.c (ffffffff814b3728)
Location: ipc/shm.c:1246
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
In ipc/shm.c (ffffffff8150bd98)
Location: ipc/shm.c:1342
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
In ipc/shm.c (ffffffff8159dec9)
Location: ipc/shm.c:1336
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
In ipc/shm.c (ffffffff816474b9)
Location: ipc/shm.c:1352
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
In ipc/shm.c (ffffffff8167fa88)
Location: ipc/shm.c:1352
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
In ipc/shm.c (ffffffff816bbe78)
Location: ipc/shm.c:1348
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
In ipc/shm.c (ffff8000105282cc)
Location: ipc/shm.c:1247
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
In ipc/shm.c (c000000000672df8)
Location: ipc/shm.c:1247
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
In ipc/shm.c (ffffffff8143811a)
Location: ipc/shm.c:1247
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
In ipc/shm.c (ffffffff81428b8a)
Location: ipc/shm.c:1247
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
In ipc/shm.c (ffffffff814342ba)
Location: ipc/shm.c:1247
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
In ipc/shm.c (ffffffff8144b3ca)
Location: ipc/shm.c:1247
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
```
</details>
</li>
</ul>

## Differences
