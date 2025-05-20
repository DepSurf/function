# Function: <code>SyS_rt_sigpending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_rt_sigpending(long int uset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090dc0)
Location: kernel/signal.c:2625
Inline: True
Inline callers:
  - kernel/signal.c:compat_SyS_rt_sigpending
  - kernel/signal.c:SyS_sigpending
```
**Symbols:**

```
ffffffff81090dc0-ffffffff81090e89: SyS_rt_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_rt_sigpending(long int uset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094e6c)
Location: kernel/signal.c:2625
Inline: True
Inline callers:
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:compat_SyS_rt_sigpending
```
**Symbols:**

```
ffffffff81093e70-ffffffff81093f4e: SyS_rt_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_rt_sigpending(long int uset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099e6c)
Location: kernel/signal.c:2638
Inline: True
Inline callers:
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:compat_SyS_rt_sigpending
```
**Symbols:**

```
ffffffff81098e50-ffffffff81098f2e: SyS_rt_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_rt_sigpending(long int uset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81096fcc)
Location: kernel/signal.c:2659
Inline: True
Inline callers:
  - kernel/signal.c:compat_SyS_sigpending
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:compat_SyS_rt_sigpending
```
**Symbols:**

```
ffffffff81096100-ffffffff810961e0: SyS_rt_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_rt_sigpending(long int uset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109dcad)
Location: kernel/signal.c:2643
Inline: True
Inline callers:
  - kernel/signal.c:SyS_sigpending
```
**Symbols:**

```
ffffffff8109cf40-ffffffff8109cfd0: SyS_rt_sigpending (STB_GLOBAL)
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
