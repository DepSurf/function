# Function: <code>SyS_fanotify_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_fanotify_mark(long int fanotify_fd, long int flags, long long int mask, long int dfd, long int pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812540b0)
Location: fs/notify/fanotify/fanotify_user.c:804
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff812540b0-ffffffff8125431e: SyS_fanotify_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_fanotify_mark(long int fanotify_fd, long int flags, long long int mask, long int dfd, long int pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127cb80)
Location: fs/notify/fanotify/fanotify_user.c:816
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff8127c880-ffffffff8127cb39: SyS_fanotify_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_fanotify_mark(long int fanotify_fd, long int flags, long long int mask, long int dfd, long int pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81290720)
Location: fs/notify/fanotify/fanotify_user.c:815
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff81290420-ffffffff812906d9: SyS_fanotify_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_fanotify_mark(long int fanotify_fd, long int flags, long long int mask, long int dfd, long int pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129d5b0)
Location: fs/notify/fanotify/fanotify_user.c:819
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff8129d2c0-ffffffff8129d56a: SyS_fanotify_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_fanotify_mark(long int fanotify_fd, long int flags, long long int mask, long int dfd, long int pathname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812c0a30)
Location: fs/notify/fanotify/fanotify_user.c:823
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff812c0780-ffffffff812c09e5: SyS_fanotify_mark (STB_GLOBAL)
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
