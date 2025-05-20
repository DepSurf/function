# Function: <code>vt_k_ioctl</code>

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
int vt_k_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg, bool perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff81760450)
Location: drivers/tty/vt/vt_ioctl.c:284
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81760450-ffffffff817609ec: vt_k_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vt_k_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg, bool perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff81744070)
Location: drivers/tty/vt/vt_ioctl.c:283
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81744070-ffffffff8174461b: vt_k_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vt_k_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg, bool perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff817c4eb0)
Location: drivers/tty/vt/vt_ioctl.c:283
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff817c4eb0-ffffffff817c5441: vt_k_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vt_k_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg, bool perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff81901d30)
Location: drivers/tty/vt/vt_ioctl.c:283
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81901d30-ffffffff819022b9: vt_k_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vt_k_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg, bool perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff81a5bcc0)
Location: drivers/tty/vt/vt_ioctl.c:283
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81a5bcc0-ffffffff81a5c249: vt_k_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vt_k_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg, bool perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff81aa62e0)
Location: drivers/tty/vt/vt_ioctl.c:283
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81aa62e0-ffffffff81aa6864: vt_k_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vt_k_ioctl(struct tty_struct *tty, unsigned int cmd, long unsigned int arg, bool perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt_ioctl.c (ffffffff81af8d70)
Location: drivers/tty/vt/vt_ioctl.c:283
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81af8d70-ffffffff81af92f4: vt_k_ioctl (STB_LOCAL)
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
