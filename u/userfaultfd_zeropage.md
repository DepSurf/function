# Function: <code>userfaultfd_zeropage</code>

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
In fs/userfaultfd.c (ffffffff8125a551)
Location: fs/userfaultfd.c:1089
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
In fs/userfaultfd.c (ffffffff81282dc8)
Location: fs/userfaultfd.c:1101
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
In fs/userfaultfd.c (ffffffff812968e8)
Location: fs/userfaultfd.c:1136
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
In fs/userfaultfd.c (ffffffff812a40a8)
Location: fs/userfaultfd.c:1621
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
In fs/userfaultfd.c (ffffffff812c752e)
Location: fs/userfaultfd.c:1705
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
In fs/userfaultfd.c (ffffffff812f01d2)
Location: fs/userfaultfd.c:1714
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
In fs/userfaultfd.c (ffffffff81305112)
Location: fs/userfaultfd.c:1735
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
In fs/userfaultfd.c (ffffffff81326e40)
Location: fs/userfaultfd.c:1755
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
In fs/userfaultfd.c (ffffffff81339d53)
Location: fs/userfaultfd.c:1757
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
int userfaultfd_zeropage(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81373450)
Location: fs/userfaultfd.c:1766
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81373450-ffffffff8137363c: userfaultfd_zeropage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int userfaultfd_zeropage(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81381300)
Location: fs/userfaultfd.c:1726
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81381300-ffffffff813814e6: userfaultfd_zeropage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int userfaultfd_zeropage(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81387900)
Location: fs/userfaultfd.c:1746
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81387900-ffffffff81387aff: userfaultfd_zeropage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int userfaultfd_zeropage(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813d4bd0)
Location: fs/userfaultfd.c:1745
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff813d4bd0-ffffffff813d4dcc: userfaultfd_zeropage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int userfaultfd_zeropage(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8145f420)
Location: fs/userfaultfd.c:1741
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8145f420-ffffffff8145f660: userfaultfd_zeropage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int userfaultfd_zeropage(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814ef260)
Location: fs/userfaultfd.c:1778
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff814ef260-ffffffff814ef4a0: userfaultfd_zeropage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int userfaultfd_zeropage(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81523d50)
Location: fs/userfaultfd.c:1799
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81523d50-ffffffff81523f9c: userfaultfd_zeropage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int userfaultfd_zeropage(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8155aaf0)
Location: fs/userfaultfd.c:1774
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8155aaf0-ffffffff8155ad4a: userfaultfd_zeropage (STB_LOCAL)
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
In fs/userfaultfd.c (ffff8000103f8c38)
Location: fs/userfaultfd.c:1757
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
In fs/userfaultfd.c (c05ccacc)
Location: fs/userfaultfd.c:1757
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
In fs/userfaultfd.c (c0000000005000b0)
Location: fs/userfaultfd.c:1757
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
In fs/userfaultfd.c (ffffffe0002a772a)
Location: fs/userfaultfd.c:1757
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
In fs/userfaultfd.c (ffffffff81332333)
Location: fs/userfaultfd.c:1757
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
In fs/userfaultfd.c (ffffffff81322ef3)
Location: fs/userfaultfd.c:1757
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
In fs/userfaultfd.c (ffffffff8132fe03)
Location: fs/userfaultfd.c:1757
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
In fs/userfaultfd.c (ffffffff8134276d)
Location: fs/userfaultfd.c:1757
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
