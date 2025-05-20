# Function: <code>xenboot_console_setup</code>

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
int xenboot_console_setup(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff83006759)
Location: drivers/tty/hvc/hvc_xen.c:606
Inline: False
```
**Symbols:**

```
ffffffff83006759-ffffffff83006792: xenboot_console_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xenboot_console_setup(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff832112dc)
Location: drivers/tty/hvc/hvc_xen.c:606
Inline: False
```
**Symbols:**

```
ffffffff832112dc-ffffffff83211315: xenboot_console_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xenboot_console_setup(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff832fa3aa)
Location: drivers/tty/hvc/hvc_xen.c:641
Inline: False
```
**Symbols:**

```
ffffffff832fa3aa-ffffffff832fa3d8: xenboot_console_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenboot_console_setup(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff834b2c41)
Location: drivers/tty/hvc/hvc_xen.c:642
Inline: False
```
**Symbols:**

```
ffffffff834b2c41-ffffffff834b2c7f: xenboot_console_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenboot_console_setup(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff83eed740)
Location: drivers/tty/hvc/hvc_xen.c:654
Inline: False
```
**Symbols:**

```
ffffffff83eed740-ffffffff83eed77e: xenboot_console_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenboot_console_setup(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff83713400)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
```
**Symbols:**

```
ffffffff83713400-ffffffff8371343e: xenboot_console_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenboot_console_setup(struct console *console, char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff83946e50)
Location: drivers/tty/hvc/hvc_xen.c:687
Inline: False
```
**Symbols:**

```
ffffffff83946e50-ffffffff83946e8e: xenboot_console_setup (STB_LOCAL)
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
