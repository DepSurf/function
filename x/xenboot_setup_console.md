# Function: <code>xenboot_setup_console</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xenboot_setup_console(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81fd2e46)
Location: drivers/tty/hvc/hvc_xen.c:619
Inline: True
```
**Symbols:**

```
ffffffff81fd2e46-ffffffff81fd2e86: xenboot_setup_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xenboot_setup_console(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff82010a50)
Location: drivers/tty/hvc/hvc_xen.c:619
Inline: True
```
**Symbols:**

```
ffffffff82010a50-ffffffff82010a90: xenboot_setup_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xenboot_setup_console(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff820f2540)
Location: drivers/tty/hvc/hvc_xen.c:619
Inline: False
```
**Symbols:**

```
ffffffff820f2540-ffffffff820f2586: xenboot_setup_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xenboot_setup_console(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff826fbd39)
Location: drivers/tty/hvc/hvc_xen.c:606
Inline: False
```
**Symbols:**

```
ffffffff826fbd39-ffffffff826fbd7f: xenboot_setup_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xenboot_setup_console(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff82725e0d)
Location: drivers/tty/hvc/hvc_xen.c:606
Inline: False
```
**Symbols:**

```
ffffffff82725e0d-ffffffff82725e46: xenboot_setup_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xenboot_setup_console(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff828ddfd2)
Location: drivers/tty/hvc/hvc_xen.c:606
Inline: False
```
**Symbols:**

```
ffffffff828ddfd2-ffffffff828de00b: xenboot_setup_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xenboot_setup_console(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff828f88c1)
Location: drivers/tty/hvc/hvc_xen.c:606
Inline: False
```
**Symbols:**

```
ffffffff828f88c1-ffffffff828f88fa: xenboot_setup_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xenboot_setup_console(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff829017c2)
Location: drivers/tty/hvc/hvc_xen.c:606
Inline: False
```
**Symbols:**

```
ffffffff829017c2-ffffffff829017fb: xenboot_setup_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xenboot_setup_console(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff82d18ae0)
Location: drivers/tty/hvc/hvc_xen.c:606
Inline: False
```
**Symbols:**

```
ffffffff82d18ae0-ffffffff82d18b19: xenboot_setup_console (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int xenboot_setup_console(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff828e8fa9)
Location: drivers/tty/hvc/hvc_xen.c:606
Inline: False
```
**Symbols:**

```
ffffffff828e8fa9-ffffffff828e8fe2: xenboot_setup_console (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xenboot_setup_console(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff828fcae5)
Location: drivers/tty/hvc/hvc_xen.c:606
Inline: False
```
**Symbols:**

```
ffffffff828fcae5-ffffffff828fcb1e: xenboot_setup_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xenboot_setup_console(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff82902a83)
Location: drivers/tty/hvc/hvc_xen.c:606
Inline: False
```
**Symbols:**

```
ffffffff82902a83-ffffffff82902abc: xenboot_setup_console (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
