# Function: <code>compat_SyS_waitid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int compat_SyS_waitid(long int which, long int pid, long int uinfo, long int options, long int uru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811110f0)
Location: kernel/compat.c:567
Inline: False
```
**Symbols:**

```
ffffffff811110f0-ffffffff81111100: compat_SyS_waitid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int compat_SyS_waitid(long int which, long int pid, long int uinfo, long int options, long int uru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81118820)
Location: kernel/compat.c:567
Inline: False
```
**Symbols:**

```
ffffffff81118820-ffffffff81118830: compat_SyS_waitid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int compat_SyS_waitid(long int which, long int pid, long int uinfo, long int options, long int uru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111ff40)
Location: kernel/compat.c:575
Inline: False
```
**Symbols:**

```
ffffffff8111ff40-ffffffff8111ff50: compat_SyS_waitid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_SyS_waitid(long int which, long int pid, long int infop, long int options, long int uru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810899d0)
Location: kernel/exit.c:1718
Inline: False
```
**Symbols:**

```
ffffffff810899d0-ffffffff810899e0: compat_SyS_waitid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_SyS_waitid(long int which, long int pid, long int infop, long int options, long int uru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81090750)
Location: kernel/exit.c:1715
Inline: False
```
**Symbols:**

```
ffffffff81090750-ffffffff81090760: compat_SyS_waitid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long int infop</code>
</li>
<li>
<b>Param removed. </b>
<code>long int uinfo</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
