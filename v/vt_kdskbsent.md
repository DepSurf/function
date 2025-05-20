# Function: <code>vt_kdskbsent</code>

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
char *vt_kdskbsent(char *kbs, unsigned char cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81763d70)
Location: drivers/tty/vt/keyboard.c:2023
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
**Symbols:**

```
ffffffff81763d70-ffffffff81763dfa: vt_kdskbsent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *vt_kdskbsent(char *kbs, unsigned char cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff817476b0)
Location: drivers/tty/vt/keyboard.c:2033
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
**Symbols:**

```
ffffffff817476b0-ffffffff8174773a: vt_kdskbsent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *vt_kdskbsent(char *kbs, unsigned char cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff817c86f0)
Location: drivers/tty/vt/keyboard.c:2033
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
**Symbols:**

```
ffffffff817c86f0-ffffffff817c877a: vt_kdskbsent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *vt_kdskbsent(char *kbs, unsigned char cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81905a10)
Location: drivers/tty/vt/keyboard.c:2045
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
**Symbols:**

```
ffffffff81905a10-ffffffff81905aae: vt_kdskbsent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *vt_kdskbsent(char *kbs, unsigned char cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81a601f0)
Location: drivers/tty/vt/keyboard.c:2045
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
**Symbols:**

```
ffffffff81a601f0-ffffffff81a6028e: vt_kdskbsent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *vt_kdskbsent(char *kbs, unsigned char cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81aaa8c0)
Location: drivers/tty/vt/keyboard.c:2045
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
**Symbols:**

```
ffffffff81aaa8c0-ffffffff81aaa95e: vt_kdskbsent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *vt_kdskbsent(char *kbs, unsigned char cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81afd350)
Location: drivers/tty/vt/keyboard.c:2043
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
**Symbols:**

```
ffffffff81afd350-ffffffff81afd3ee: vt_kdskbsent (STB_LOCAL)
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
