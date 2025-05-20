# Function: <code>__se_sys_rt_sigtimedwait</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a1be5)
Location: kernel/signal.c:3099
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa4a6)
Location: kernel/signal.c:3361
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af539)
Location: kernel/signal.c:3490
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5b59)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9459)
Location: kernel/signal.c:3513
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4709)
Location: kernel/signal.c:3533
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6319)
Location: kernel/signal.c:3555
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c91a9)
Location: kernel/signal.c:3643
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e05d6)
Location: kernel/signal.c:3626
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81105df4)
Location: kernel/signal.c:3628
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811120d4)
Location: kernel/signal.c:3652
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111bac4)
Location: kernel/signal.c:3663
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_rt_sigtimedwait(long int uthese, long int uinfo, long int uts, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0369314)
Location: kernel/signal.c:3495
Inline: False
```
**Symbols:**

```
c0369314-c0369440: __se_sys_rt_sigtimedwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_rt_sigtimedwait(long int uthese, long int uinfo, long int uts, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000159980)
Location: kernel/signal.c:3495
Inline: False
```
**Symbols:**

```
c000000000159980-c000000000159ae0: __se_sys_rt_sigtimedwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_rt_sigtimedwait(long int uthese, long int uinfo, long int uts, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d1340)
Location: kernel/signal.c:3495
Inline: False
```
**Symbols:**

```
ffffffe0000d1340-ffffffe0000d15ba: __se_sys_rt_sigtimedwait (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afec9)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109e7e9)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af429)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b76f9)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
