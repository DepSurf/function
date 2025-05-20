# Function: <code>SyS_rt_sigsuspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_rt_sigsuspend(long int unewset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092260)
Location: kernel/signal.c:3523
Inline: True
Inline callers:
  - kernel/signal.c:compat_SyS_rt_sigsuspend
```
**Symbols:**

```
ffffffff81092260-ffffffff810922cb: SyS_rt_sigsuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_rt_sigsuspend(long int unewset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095436)
Location: kernel/signal.c:3528
Inline: True
Inline callers:
  - kernel/signal.c:compat_SyS_rt_sigsuspend
```
**Symbols:**

```
ffffffff810953c0-ffffffff8109542b: SyS_rt_sigsuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_rt_sigsuspend(long int unewset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a426)
Location: kernel/signal.c:3555
Inline: True
Inline callers:
  - kernel/signal.c:compat_SyS_rt_sigsuspend
```
**Symbols:**

```
ffffffff8109a3b0-ffffffff8109a41b: SyS_rt_sigsuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_rt_sigsuspend(long int unewset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810975bc)
Location: kernel/signal.c:3610
Inline: True
Inline callers:
  - kernel/signal.c:compat_SyS_rt_sigsuspend
```
**Symbols:**

```
ffffffff81097530-ffffffff81097599: SyS_rt_sigsuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int SyS_rt_sigsuspend(long int unewset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109e220)
Location: kernel/signal.c:3625
Inline: False
```
**Symbols:**

```
ffffffff8109e220-ffffffff8109e289: SyS_rt_sigsuspend (STB_GLOBAL)
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
