# Function: <code>userfaultfd_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8125a1ad)
Location: fs/userfaultfd.c:1009
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812829dc)
Location: fs/userfaultfd.c:1019
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812964fc)
Location: fs/userfaultfd.c:1054
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812a3d30)
Location: fs/userfaultfd.c:1537
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff812c71b0)
Location: fs/userfaultfd.c:1621
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff812eff1d)
Location: fs/userfaultfd.c:1626
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff81304e5d)
Location: fs/userfaultfd.c:1647
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff81326efd)
Location: fs/userfaultfd.c:1667
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff81339c66)
Location: fs/userfaultfd.c:1669
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int userfaultfd_wake(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81372ac0)
Location: fs/userfaultfd.c:1677
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81372ac0-ffffffff81372bf5: userfaultfd_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int userfaultfd_wake(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81380940)
Location: fs/userfaultfd.c:1637
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81380940-ffffffff81380a67: userfaultfd_wake (STB_LOCAL)
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
In fs/userfaultfd.c (ffffffff8138858b)
Location: fs/userfaultfd.c:1657
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff813d58cc)
Location: fs/userfaultfd.c:1656
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff8145fa9d)
Location: fs/userfaultfd.c:1652
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff814efb6b)
Location: fs/userfaultfd.c:1689
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff8152689f)
Location: fs/userfaultfd.c:1707
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff8155ae41)
Location: fs/userfaultfd.c:1684
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffff8000103f8b64)
Location: fs/userfaultfd.c:1669
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (c05ccc44)
Location: fs/userfaultfd.c:1669
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (c0000000004fff90)
Location: fs/userfaultfd.c:1669
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffe0002a78f8)
Location: fs/userfaultfd.c:1669
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff81332246)
Location: fs/userfaultfd.c:1669
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff81322e06)
Location: fs/userfaultfd.c:1669
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff8132fd16)
Location: fs/userfaultfd.c:1669
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In fs/userfaultfd.c (ffffffff8134268f)
Location: fs/userfaultfd.c:1669
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
