# Function: <code>userfaultfd_continue</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int userfaultfd_continue(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81387c90)
Location: fs/userfaultfd.c:1845
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81387c90-ffffffff81387e9d: userfaultfd_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int userfaultfd_continue(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813d4fa0)
Location: fs/userfaultfd.c:1850
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff813d4fa0-ffffffff813d51aa: userfaultfd_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int userfaultfd_continue(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8145d560)
Location: fs/userfaultfd.c:1846
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8145d560-ffffffff8145d7a8: userfaultfd_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int userfaultfd_continue(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814ed080)
Location: fs/userfaultfd.c:1883
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff814ed080-ffffffff814ed2c8: userfaultfd_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int userfaultfd_continue(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff815261b0)
Location: fs/userfaultfd.c:1904
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff815261b0-ffffffff81526417: userfaultfd_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int userfaultfd_continue(struct userfaultfd_ctx *ctx, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8155a5c0)
Location: fs/userfaultfd.c:1879
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8155a5c0-ffffffff8155a829: userfaultfd_continue (STB_LOCAL)
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
