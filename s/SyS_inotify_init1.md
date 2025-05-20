# Function: <code>SyS_inotify_init1</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_inotify_init1(long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81252330)
Location: fs/notify/inotify/inotify_user.c:669
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
```
**Symbols:**

```
ffffffff81252330-ffffffff812523a0: SyS_inotify_init1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_inotify_init1(long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8127ab6e)
Location: fs/notify/inotify/inotify_user.c:669
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
```
**Symbols:**

```
ffffffff8127aaf0-ffffffff8127ab60: SyS_inotify_init1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_inotify_init1(long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8128e71e)
Location: fs/notify/inotify/inotify_user.c:669
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
```
**Symbols:**

```
ffffffff8128e6a0-ffffffff8128e710: SyS_inotify_init1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_inotify_init1(long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8129b59e)
Location: fs/notify/inotify/inotify_user.c:638
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
```
**Symbols:**

```
ffffffff8129b520-ffffffff8129b590: SyS_inotify_init1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_inotify_init1(long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812be9ae)
Location: fs/notify/inotify/inotify_user.c:638
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
```
**Symbols:**

```
ffffffff812be930-ffffffff812be9a0: SyS_inotify_init1 (STB_GLOBAL)
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
