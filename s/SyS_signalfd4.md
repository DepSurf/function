# Function: <code>SyS_signalfd4</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_signalfd4(long int ufd, long int user_mask, long int sizemask, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff812576d0)
Location: fs/signalfd.c:255
Inline: True
Inline callers:
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:compat_SyS_signalfd
```
**Symbols:**

```
ffffffff812576d0-ffffffff81257894: SyS_signalfd4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_signalfd4(long int ufd, long int user_mask, long int sizemask, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff812805ee)
Location: fs/signalfd.c:255
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
**Symbols:**

```
ffffffff8127ffd0-ffffffff81280194: SyS_signalfd4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_signalfd4(long int ufd, long int user_mask, long int sizemask, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8129415e)
Location: fs/signalfd.c:255
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
**Symbols:**

```
ffffffff81293b40-ffffffff81293d04: SyS_signalfd4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_signalfd4(long int ufd, long int user_mask, long int sizemask, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff812a1436)
Location: fs/signalfd.c:255
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
**Symbols:**

```
ffffffff812a0e30-ffffffff812a0fe1: SyS_signalfd4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_signalfd4(long int ufd, long int user_mask, long int sizemask, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff812c4763)
Location: fs/signalfd.c:250
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
**Symbols:**

```
ffffffff812c4180-ffffffff812c4331: SyS_signalfd4 (STB_GLOBAL)
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
