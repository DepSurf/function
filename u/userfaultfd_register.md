# Function: <code>userfaultfd_register</code>

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
In fs/userfaultfd.c (ffffffff8125a67e)
Location: fs/userfaultfd.c:717
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
In fs/userfaultfd.c (ffffffff81282f29)
Location: fs/userfaultfd.c:721
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
In fs/userfaultfd.c (ffffffff81296a49)
Location: fs/userfaultfd.c:756
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
In fs/userfaultfd.c (ffffffff812a3f6d)
Location: fs/userfaultfd.c:1190
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
In fs/userfaultfd.c (ffffffff812c73f3)
Location: fs/userfaultfd.c:1274
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
In fs/userfaultfd.c (ffffffff812f0397)
Location: fs/userfaultfd.c:1279
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
In fs/userfaultfd.c (ffffffff813052e7)
Location: fs/userfaultfd.c:1284
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:1300
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81325770-ffffffff81325c52: userfaultfd_register (STB_LOCAL)
ffffffff81327e9e-ffffffff81327ebc: userfaultfd_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81338610)
Location: fs/userfaultfd.c:1302
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81338610-ffffffff81338aee: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81372500)
Location: fs/userfaultfd.c:1304
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81372500-ffffffff81372a40: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81380350)
Location: fs/userfaultfd.c:1268
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81380350-ffffffff813808b3: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81386dd0)
Location: fs/userfaultfd.c:1277
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81386dd0-ffffffff81387461: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813d4060)
Location: fs/userfaultfd.c:1272
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff813d4060-ffffffff813d472c: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8145ed90)
Location: fs/userfaultfd.c:1263
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8145ed90-ffffffff8145f41a: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814eeab0)
Location: fs/userfaultfd.c:1283
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff814eeab0-ffffffff814ef246: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff815259e0)
Location: fs/userfaultfd.c:1312
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff815259e0-ffffffff81526195: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81559db0)
Location: fs/userfaultfd.c:1314
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81559db0-ffffffff8155a5ae: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffff8000103f81e8)
Location: fs/userfaultfd.c:1302
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffff8000103f81e8-ffff8000103f8790: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c05cc2d0)
Location: fs/userfaultfd.c:1302
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
c05cc2d0-c05cc79c: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c0000000004fee40)
Location: fs/userfaultfd.c:1302
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
c0000000004fee40-c0000000004ff510: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffe0002a6f76)
Location: fs/userfaultfd.c:1302
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffe0002a6f76-ffffffe0002a72f8: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81330bf0)
Location: fs/userfaultfd.c:1302
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81330bf0-ffffffff813310ce: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81321c40)
Location: fs/userfaultfd.c:1302
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81321c40-ffffffff8132211e: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8132e6c0)
Location: fs/userfaultfd.c:1302
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8132e6c0-ffffffff8132eb9e: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81341eb0)
Location: fs/userfaultfd.c:1302
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81341eb0-ffffffff813423c5: userfaultfd_register (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
