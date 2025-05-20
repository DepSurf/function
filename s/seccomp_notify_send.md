# Function: <code>seccomp_notify_send</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81177dfb)
Location: kernel/seccomp.c:1075
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffffffff81184b9b)
Location: kernel/seccomp.c:1080
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffffffff81190a1b)
Location: kernel/seccomp.c:1098
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int seccomp_notify_send(struct seccomp_filter *filter, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a5980)
Location: kernel/seccomp.c:1114
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff811a5980-ffffffff811a5abd: seccomp_notify_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int seccomp_notify_send(struct seccomp_filter *filter, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a2870)
Location: kernel/seccomp.c:1485
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff811a2870-ffffffff811a29b3: seccomp_notify_send (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff811a391b)
Location: kernel/seccomp.c:1515
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffffffff811ccffb)
Location: kernel/seccomp.c:1497
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffffffff81200fdb)
Location: kernel/seccomp.c:1526
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffffffff81248d2b)
Location: kernel/seccomp.c:1526
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffffffff8126011f)
Location: kernel/seccomp.c:1526
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffffffff8127a2d3)
Location: kernel/seccomp.c:1570
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffff800010209058)
Location: kernel/seccomp.c:1098
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (c0447974)
Location: kernel/seccomp.c:1098
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (c000000000284cf0)
Location: kernel/seccomp.c:1098
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffffffe00016a6b2)
Location: kernel/seccomp.c:1098
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffffffff8118903b)
Location: kernel/seccomp.c:1098
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffffffff8117c17b)
Location: kernel/seccomp.c:1098
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffffffff81186e0b)
Location: kernel/seccomp.c:1098
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
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
In kernel/seccomp.c (ffffffff8119475b)
Location: kernel/seccomp.c:1098
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
