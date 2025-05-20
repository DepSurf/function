# Function: <code>compat_SyS_rt_sigsuspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int compat_SyS_rt_sigsuspend(long int unewset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810922d0)
Location: kernel/signal.c:3537
Inline: False
```
**Symbols:**

```
ffffffff810922d0-ffffffff8109233a: compat_SyS_rt_sigsuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int compat_SyS_rt_sigsuspend(long int unewset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095430)
Location: kernel/signal.c:3542
Inline: False
```
**Symbols:**

```
ffffffff81095430-ffffffff8109549a: compat_SyS_rt_sigsuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int compat_SyS_rt_sigsuspend(long int unewset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a420)
Location: kernel/signal.c:3569
Inline: False
```
**Symbols:**

```
ffffffff8109a420-ffffffff8109a48a: compat_SyS_rt_sigsuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_SyS_rt_sigsuspend(long int unewset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810975a0)
Location: kernel/signal.c:3624
Inline: False
```
**Symbols:**

```
ffffffff810975a0-ffffffff81097608: compat_SyS_rt_sigsuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_SyS_rt_sigsuspend(long int unewset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109e290)
Location: kernel/signal.c:3639
Inline: False
```
**Symbols:**

```
ffffffff8109e290-ffffffff8109e2f2: compat_SyS_rt_sigsuspend (STB_GLOBAL)
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
