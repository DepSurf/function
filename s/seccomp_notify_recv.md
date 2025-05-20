# Function: <code>seccomp_notify_recv</code>

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
In kernel/seccomp.c (ffffffff81177f37)
Location: kernel/seccomp.c:1006
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
In kernel/seccomp.c (ffffffff81184d02)
Location: kernel/seccomp.c:1011
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
In kernel/seccomp.c (ffffffff81190bae)
Location: kernel/seccomp.c:1022
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
long int seccomp_notify_recv(struct seccomp_filter *filter, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a56b0)
Location: kernel/seccomp.c:1038
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff811a56b0-ffffffff811a58a7: seccomp_notify_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int seccomp_notify_recv(struct seccomp_filter *filter, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a2660)
Location: kernel/seccomp.c:1416
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff811a2660-ffffffff811a2865: seccomp_notify_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int seccomp_notify_recv(struct seccomp_filter *filter, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a3280)
Location: kernel/seccomp.c:1446
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff811a3280-ffffffff811a3485: seccomp_notify_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int seccomp_notify_recv(struct seccomp_filter *filter, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811cc960)
Location: kernel/seccomp.c:1428
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff811cc960-ffffffff811ccb65: seccomp_notify_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int seccomp_notify_recv(struct seccomp_filter *filter, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:1454
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff81200c50-ffffffff81200e94: seccomp_notify_recv (STB_LOCAL)
ffffffff81e64e2d-ffffffff81e64e42: seccomp_notify_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int seccomp_notify_recv(struct seccomp_filter *filter, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:1454
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff81248990-ffffffff81248bd4: seccomp_notify_recv (STB_LOCAL)
ffffffff8205c93c-ffffffff8205c951: seccomp_notify_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int seccomp_notify_recv(struct seccomp_filter *filter, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:1454
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff8125fd80-ffffffff8125ffc4: seccomp_notify_recv (STB_LOCAL)
ffffffff820db2e2-ffffffff820db2f7: seccomp_notify_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int seccomp_notify_recv(struct seccomp_filter *filter, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:1497
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff81279ed0-ffffffff8127a129: seccomp_notify_recv (STB_LOCAL)
ffffffff821b7003-ffffffff821b7018: seccomp_notify_recv.cold (STB_LOCAL)
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
In kernel/seccomp.c (ffff800010208ed8)
Location: kernel/seccomp.c:1022
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
In kernel/seccomp.c (c0447b70)
Location: kernel/seccomp.c:1022
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
In kernel/seccomp.c (c000000000284e80)
Location: kernel/seccomp.c:1022
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
In kernel/seccomp.c (ffffffe00016a726)
Location: kernel/seccomp.c:1022
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
In kernel/seccomp.c (ffffffff811891ce)
Location: kernel/seccomp.c:1022
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
In kernel/seccomp.c (ffffffff8117c30e)
Location: kernel/seccomp.c:1022
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
In kernel/seccomp.c (ffffffff81186f9e)
Location: kernel/seccomp.c:1022
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
In kernel/seccomp.c (ffffffff811948ee)
Location: kernel/seccomp.c:1022
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
