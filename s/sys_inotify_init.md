# Function: <code>sys_inotify_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int sys_inotify_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812523a0)
Location: fs/notify/inotify/inotify_user.c:694
Inline: False
```
**Symbols:**

```
ffffffff812523a0-ffffffff812523f9: sys_inotify_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int sys_inotify_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8127ab60)
Location: fs/notify/inotify/inotify_user.c:694
Inline: False
```
**Symbols:**

```
ffffffff8127ab60-ffffffff8127abb9: sys_inotify_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int sys_inotify_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8128e710)
Location: fs/notify/inotify/inotify_user.c:694
Inline: False
```
**Symbols:**

```
ffffffff8128e710-ffffffff8128e769: sys_inotify_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int sys_inotify_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8129b590)
Location: fs/notify/inotify/inotify_user.c:663
Inline: False
```
**Symbols:**

```
ffffffff8129b590-ffffffff8129b5e9: sys_inotify_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int sys_inotify_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812be9a0)
Location: fs/notify/inotify/inotify_user.c:663
Inline: False
```
**Symbols:**

```
ffffffff812be9a0-ffffffff812be9f9: sys_inotify_init (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int sys_inotify_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (c05c36e0)
Location: fs/notify/inotify/inotify_user.c:693
Inline: False
```
**Symbols:**

```
c05c36e0-c05c3700: sys_inotify_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int sys_inotify_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (c0000000004f3890)
Location: fs/notify/inotify/inotify_user.c:693
Inline: False
```
**Symbols:**

```
c0000000004f3890-c0000000004f38c4: sys_inotify_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int sys_inotify_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffe0002a08fe)
Location: fs/notify/inotify/inotify_user.c:693
Inline: False
```
**Symbols:**

```
ffffffe0002a08fe-ffffffe0002a0922: sys_inotify_init (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
