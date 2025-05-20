# Function: <code>do_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81083410)
Location: kernel/exit.c:1466
Inline: False
Direct callers:
  - kernel/exit.c:SyS_waitid
  - kernel/exit.c:SyS_waitpid
```
**Symbols:**

```
ffffffff81083410-ffffffff81083643: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810864a0)
Location: kernel/exit.c:1551
Inline: False
Direct callers:
  - kernel/exit.c:SyS_waitpid
  - kernel/exit.c:SyS_waitid
```
**Symbols:**

```
ffffffff810864a0-ffffffff810866d5: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108b410)
Location: kernel/exit.c:1541
Inline: False
Direct callers:
  - kernel/exit.c:SyS_waitpid
  - kernel/exit.c:SyS_waitid
```
**Symbols:**

```
ffffffff8108b410-ffffffff8108b641: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81088190)
Location: kernel/exit.c:1497
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff81088190-ffffffff810883b4: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108ef10)
Location: kernel/exit.c:1496
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff8108ef10-ffffffff8108f13d: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81092a10)
Location: kernel/exit.c:1496
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff81092a10-ffffffff81092c4a: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109ad00)
Location: kernel/exit.c:1499
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff8109ad00-ffffffff8109af3a: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f370)
Location: kernel/exit.c:1503
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff8109f370-ffffffff8109f597: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a5900)
Location: kernel/exit.c:1419
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff810a5900-ffffffff810a5b27: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ad430)
Location: kernel/exit.c:1423
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff810ad430-ffffffff810ad64d: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8b00)
Location: kernel/exit.c:1442
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff810a8b00-ffffffff810a8d12: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a9b00)
Location: kernel/exit.c:1482
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff810a9b00-ffffffff810a9de9: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810bb630)
Location: kernel/exit.c:1482
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff810bb630-ffffffff810bb92a: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d2070)
Location: kernel/exit.c:1486
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff810d2070-ffffffff810d238f: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810f0ae0)
Location: kernel/exit.c:1580
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff810f0ae0-ffffffff810f0dff: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fca90)
Location: kernel/exit.c:1585
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff810fca90-ffffffff810fcdaf: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81107190)
Location: kernel/exit.c:1612
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff81107190-ffffffff81107298: do_wait (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fb928)
Location: kernel/exit.c:1419
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffff8000100fb928-ffff8000100fbbd8: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c035989c)
Location: kernel/exit.c:1419
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
c035989c-c0359b90: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000142f00)
Location: kernel/exit.c:1419
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
c000000000142f00-c0000000001431f8: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c547a)
Location: kernel/exit.c:1419
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffe0000c547a-ffffffe0000c5652: do_wait (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f220)
Location: kernel/exit.c:1419
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff8109f220-ffffffff8109f447: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108dc50)
Location: kernel/exit.c:1419
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff8108dc50-ffffffff8108de77: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f1d0)
Location: kernel/exit.c:1419
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff8109f1d0-ffffffff8109f3f7: do_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_wait(struct wait_opts *wo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7120)
Location: kernel/exit.c:1419
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
```
**Symbols:**

```
ffffffff810a7120-ffffffff810a735f: do_wait (STB_LOCAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
