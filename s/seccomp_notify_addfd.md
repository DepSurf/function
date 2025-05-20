# Function: <code>seccomp_notify_addfd</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int seccomp_notify_addfd(struct seccomp_filter *filter, struct seccomp_notif_addfd *uaddfd, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a2aa0)
Location: kernel/seccomp.c:1553
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff811a2aa0-ffffffff811a2ce1: seccomp_notify_addfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int seccomp_notify_addfd(struct seccomp_filter *filter, struct seccomp_notif_addfd *uaddfd, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a3570)
Location: kernel/seccomp.c:1583
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff811a3570-ffffffff811a37e4: seccomp_notify_addfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int seccomp_notify_addfd(struct seccomp_filter *filter, struct seccomp_notif_addfd *uaddfd, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811ccc50)
Location: kernel/seccomp.c:1565
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff811ccc50-ffffffff811ccec4: seccomp_notify_addfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int seccomp_notify_addfd(struct seccomp_filter *filter, struct seccomp_notif_addfd *uaddfd, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff812009b0)
Location: kernel/seccomp.c:1594
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff812009b0-ffffffff81200c4a: seccomp_notify_addfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int seccomp_notify_addfd(struct seccomp_filter *filter, struct seccomp_notif_addfd *uaddfd, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff812486e0)
Location: kernel/seccomp.c:1594
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff812486e0-ffffffff8124897a: seccomp_notify_addfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int seccomp_notify_addfd(struct seccomp_filter *filter, struct seccomp_notif_addfd *uaddfd, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8125fad0)
Location: kernel/seccomp.c:1594
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff8125fad0-ffffffff8125fd6e: seccomp_notify_addfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int seccomp_notify_addfd(struct seccomp_filter *filter, struct seccomp_notif_addfd *uaddfd, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81279c20)
Location: kernel/seccomp.c:1657
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
**Symbols:**

```
ffffffff81279c20-ffffffff81279ebe: seccomp_notify_addfd (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
