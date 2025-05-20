# Function: <code>unshare_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107dc20)
Location: kernel/fork.c:1942
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:unshare_files
```
**Symbols:**

```
ffffffff8107dc20-ffffffff8107dca1: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107f810)
Location: kernel/fork.c:2005
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:SyS_unshare
```
**Symbols:**

```
ffffffff8107f810-ffffffff8107f891: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81083ef0)
Location: kernel/fork.c:2167
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:SyS_unshare
```
**Symbols:**

```
ffffffff81083ef0-ffffffff81083f71: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080e40)
Location: kernel/fork.c:2295
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:SyS_unshare
```
**Symbols:**

```
ffffffff81080e40-ffffffff81080ec1: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810874d0)
Location: kernel/fork.c:2304
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:SyS_unshare
```
**Symbols:**

```
ffffffff810874d0-ffffffff81087551: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108a9f0)
Location: kernel/fork.c:2379
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
ffffffff8108a9f0-ffffffff8108aa71: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81092990)
Location: kernel/fork.c:2487
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
ffffffff81092990-ffffffff81092a11: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096960)
Location: kernel/fork.c:2778
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
ffffffff81096960-ffffffff810969e2: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109d030)
Location: kernel/fork.c:2795
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
ffffffff8109d030-ffffffff8109d0b2: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a7df7)
Location: kernel/fork.c:2920
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
ffffffff810a3de0-ffffffff810a3e61: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct **new_fdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3b73)
Location: kernel/fork.c:2899
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff810a36d0-ffffffff810a3751: unshare_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct **new_fdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a47c3)
Location: kernel/fork.c:2931
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff810a4300-ffffffff810a4381: unshare_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct **new_fdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b5fe3)
Location: kernel/fork.c:3024
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff810b5b20-ffffffff810b5ba1: unshare_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct **new_fdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cc503)
Location: kernel/fork.c:3101
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff810cc010-ffffffff810cc097: unshare_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct **new_fdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e9be3)
Location: kernel/fork.c:3137
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff810e96b0-ffffffff810e9737: unshare_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct **new_fdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f57e3)
Location: kernel/fork.c:3373
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff810f52c0-ffffffff810f5347: unshare_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int unshare_fd(long unsigned int unshare_flags, unsigned int max_fds, struct files_struct **new_fdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810feb93)
Location: kernel/fork.c:3363
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff810fe660-ffffffff810fe6e7: unshare_fd (STB_GLOBAL)
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f1330)
Location: kernel/fork.c:2795
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
ffff8000100f1330-ffff8000100f13c8: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0350770)
Location: kernel/fork.c:2795
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
c0350770-c0350820: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000136ee0)
Location: kernel/fork.c:2795
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
c000000000136ee0-c000000000136fb8: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000be9e6)
Location: kernel/fork.c:2795
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
ffffffe0000be9e6-ffffffe0000bea40: unshare_fd (STB_LOCAL)
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
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096950)
Location: kernel/fork.c:2795
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
ffffffff81096950-ffffffff810969d2: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810853d0)
Location: kernel/fork.c:2795
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
ffffffff810853d0-ffffffff81085452: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096900)
Location: kernel/fork.c:2795
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
ffffffff81096900-ffffffff81096982: unshare_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unshare_fd(long unsigned int unshare_flags, struct files_struct **new_fdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e7a0)
Location: kernel/fork.c:2795
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
```
**Symbols:**

```
ffffffff8109e7a0-ffffffff8109e822: unshare_fd (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int max_fds</code>
</li>
<li>
<b>Param reordered. </b>
<code>unshare_flags, new_fdp</code> ➡️ <code>unshare_flags, max_fds, new_fdp</code>
</li>
</ul>
</details>
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
