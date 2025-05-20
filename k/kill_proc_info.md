# Function: <code>kill_proc_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int kill_proc_info(int sig, struct siginfo *info, pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108fab3)
Location: kernel/signal.c:1310
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8108fc00-ffffffff8108fc2a: kill_proc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int kill_proc_info(int sig, struct siginfo *info, pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092b33)
Location: kernel/signal.c:1310
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff81092c80-ffffffff81092caa: kill_proc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kill_proc_info(int sig, struct siginfo *info, pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097ac3)
Location: kernel/signal.c:1316
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff81097c10-ffffffff81097c3a: kill_proc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094e03)
Location: kernel/signal.c:1334
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109bca3)
Location: kernel/signal.c:1335
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109fd56)
Location: kernel/signal.c:1333
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810a80b3)
Location: kernel/signal.c:1417
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810ad974)
Location: kernel/signal.c:1455
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810b3f94)
Location: kernel/signal.c:1460
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810bd114)
Location: kernel/signal.c:1460
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
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
In kernel/signal.c (ffffffff810b8484)
Location: kernel/signal.c:1461
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
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
In kernel/signal.c (ffffffff810b9a04)
Location: kernel/signal.c:1463
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
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
In kernel/signal.c (ffffffff810cc014)
Location: kernel/signal.c:1489
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
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
In kernel/signal.c (ffffffff810e3113)
Location: kernel/signal.c:1490
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
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
In kernel/signal.c (ffffffff81103633)
Location: kernel/signal.c:1491
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
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
In kernel/signal.c (ffffffff8110f873)
Location: kernel/signal.c:1497
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
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
In kernel/signal.c (ffffffff811191e3)
Location: kernel/signal.c:1503
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
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
In kernel/signal.c (ffff8000101100cc)
Location: kernel/signal.c:1460
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0369a28)
Location: kernel/signal.c:1460
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001577f8)
Location: kernel/signal.c:1460
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d1958)
Location: kernel/signal.c:1460
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810ae304)
Location: kernel/signal.c:1460
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff8109cc54)
Location: kernel/signal.c:1460
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810ad864)
Location: kernel/signal.c:1460
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810b5a94)
Location: kernel/signal.c:1460
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_sigqueueinfo
```
</details>
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
</ul>
