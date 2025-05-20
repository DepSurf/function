# Function: <code>userfaultfd_copy</code>

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
In fs/userfaultfd.c (ffffffff8125a339)
Location: fs/userfaultfd.c:1041
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
In fs/userfaultfd.c (ffffffff81282b4f)
Location: fs/userfaultfd.c:1051
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
In fs/userfaultfd.c (ffffffff8129666f)
Location: fs/userfaultfd.c:1086
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
In fs/userfaultfd.c (ffffffff812a3e0d)
Location: fs/userfaultfd.c:1569
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
In fs/userfaultfd.c (ffffffff812c7290)
Location: fs/userfaultfd.c:1653
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
In fs/userfaultfd.c (ffffffff812efeec)
Location: fs/userfaultfd.c:1658
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
In fs/userfaultfd.c (ffffffff81304e2c)
Location: fs/userfaultfd.c:1679
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
In fs/userfaultfd.c (ffffffff81326c83)
Location: fs/userfaultfd.c:1699
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
In fs/userfaultfd.c (ffffffff81339a13)
Location: fs/userfaultfd.c:1701
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
int userfaultfd_copy(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81372c00)
Location: fs/userfaultfd.c:1709
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81372c00-ffffffff81372dfd: userfaultfd_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int userfaultfd_copy(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81380a70)
Location: fs/userfaultfd.c:1669
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81380a70-ffffffff81380c6b: userfaultfd_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int userfaultfd_copy(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81387700)
Location: fs/userfaultfd.c:1689
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81387700-ffffffff813878fb: userfaultfd_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int userfaultfd_copy(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813d49d0)
Location: fs/userfaultfd.c:1688
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff813d49d0-ffffffff813d4bc8: userfaultfd_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int userfaultfd_copy(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8145f660)
Location: fs/userfaultfd.c:1684
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8145f660-ffffffff8145f8ab: userfaultfd_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int userfaultfd_copy(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814ef700)
Location: fs/userfaultfd.c:1721
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff814ef700-ffffffff814ef94b: userfaultfd_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int userfaultfd_copy(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81526430)
Location: fs/userfaultfd.c:1739
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81526430-ffffffff8152668f: userfaultfd_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int userfaultfd_copy(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8155a840)
Location: fs/userfaultfd.c:1716
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8155a840-ffffffff8155aad7: userfaultfd_copy (STB_LOCAL)
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
In fs/userfaultfd.c (ffff8000103f8814)
Location: fs/userfaultfd.c:1701
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
In fs/userfaultfd.c (c05cc820)
Location: fs/userfaultfd.c:1701
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
In fs/userfaultfd.c (c0000000004ffc30)
Location: fs/userfaultfd.c:1701
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
In fs/userfaultfd.c (ffffffe0002a7720)
Location: fs/userfaultfd.c:1701
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
In fs/userfaultfd.c (ffffffff81331ff3)
Location: fs/userfaultfd.c:1701
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
In fs/userfaultfd.c (ffffffff81322bb3)
Location: fs/userfaultfd.c:1701
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
In fs/userfaultfd.c (ffffffff8132fac3)
Location: fs/userfaultfd.c:1701
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
In fs/userfaultfd.c (ffffffff81342443)
Location: fs/userfaultfd.c:1701
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
