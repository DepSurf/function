# Function: <code>compat_SyS_fanotify_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int compat_SyS_fanotify_mark(long int fanotify_fd, long int flags, long int mask0, long int mask1, long int dfd, long int pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81254320)
Location: fs/notify/fanotify/fanotify_user.c:913
Inline: False
```
**Symbols:**

```
ffffffff81254320-ffffffff812545cb: compat_SyS_fanotify_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int compat_SyS_fanotify_mark(long int fanotify_fd, long int flags, long int mask0, long int mask1, long int dfd, long int pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127cb40)
Location: fs/notify/fanotify/fanotify_user.c:925
Inline: False
```
**Symbols:**

```
ffffffff8127cb40-ffffffff8127cdf1: compat_SyS_fanotify_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int compat_SyS_fanotify_mark(long int fanotify_fd, long int flags, long int mask0, long int mask1, long int dfd, long int pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812906e0)
Location: fs/notify/fanotify/fanotify_user.c:924
Inline: False
```
**Symbols:**

```
ffffffff812906e0-ffffffff81290991: compat_SyS_fanotify_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_SyS_fanotify_mark(long int fanotify_fd, long int flags, long int mask0, long int mask1, long int dfd, long int pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129d570)
Location: fs/notify/fanotify/fanotify_user.c:928
Inline: False
```
**Symbols:**

```
ffffffff8129d570-ffffffff8129d816: compat_SyS_fanotify_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_SyS_fanotify_mark(long int fanotify_fd, long int flags, long int mask0, long int mask1, long int dfd, long int pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812c09f0)
Location: fs/notify/fanotify/fanotify_user.c:932
Inline: False
```
**Symbols:**

```
ffffffff812c09f0-ffffffff812c0c95: compat_SyS_fanotify_mark (STB_GLOBAL)
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
