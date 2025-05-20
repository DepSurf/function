# Function: <code>__seccomp_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81143b70)
Location: kernel/seccomp.c:559
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81143b70-ffffffff81143dc5: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8114da40)
Location: kernel/seccomp.c:558
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8114da40-ffffffff8114dc90: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8114ff30)
Location: kernel/seccomp.c:631
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8114ff30-ffffffff811502b8: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8115cbd0)
Location: kernel/seccomp.c:649
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8115cbd0-ffffffff8115d14d: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8116b430)
Location: kernel/seccomp.c:655
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8116b430-ffffffff8116b8c7: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81178aa0)
Location: kernel/seccomp.c:782
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81178aa0-ffffffff811790cf: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:787
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81185820-ffffffff81185e6c: __seccomp_filter (STB_LOCAL)
ffffffff81186c2c-ffffffff81186c5d: __seccomp_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81191750)
Location: kernel/seccomp.c:796
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81191750-ffffffff81191dcb: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a66d0)
Location: kernel/seccomp.c:806
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811a66d0-ffffffff811a6c10: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a3ce0)
Location: kernel/seccomp.c:1155
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811a3ce0-ffffffff811a4204: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a46b0)
Location: kernel/seccomp.c:1185
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811a46b0-ffffffff811a4c50: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:1165
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811cdf00-ffffffff811ce397: __seccomp_filter (STB_LOCAL)
ffffffff81cb3f94-ffffffff81cb3fa8: __seccomp_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:1191
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81202240-ffffffff81202612: __seccomp_filter (STB_LOCAL)
ffffffff81e64e80-ffffffff81e64ef2: __seccomp_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:1191
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81249f10-ffffffff8124a44f: __seccomp_filter (STB_LOCAL)
ffffffff8205c98f-ffffffff8205ca0b: __seccomp_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:1191
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81261200-ffffffff81261749: __seccomp_filter (STB_LOCAL)
ffffffff820db335-ffffffff820db3ac: __seccomp_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:1203
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8127b400-ffffffff8127b949: __seccomp_filter (STB_LOCAL)
ffffffff821b7056-ffffffff821b70cd: __seccomp_filter.cold (STB_LOCAL)
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
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffff800010209188)
Location: kernel/seccomp.c:796
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffff800010209188-ffff80001020975c: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c0447d48)
Location: kernel/seccomp.c:796
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
c0447d48-c0448544: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c000000000286150)
Location: kernel/seccomp.c:796
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
c000000000286150-c000000000286908: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffe00016b23c)
Location: kernel/seccomp.c:796
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffe00016b23c-ffffffe00016b7b0: __seccomp_filter (STB_LOCAL)
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
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81189d70)
Location: kernel/seccomp.c:796
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81189d70-ffffffff8118a3eb: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8117cea0)
Location: kernel/seccomp.c:796
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8117cea0-ffffffff8117d51b: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81187b40)
Location: kernel/seccomp.c:796
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81187b40-ffffffff811881bb: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __seccomp_filter(int this_syscall, const struct seccomp_data *sd, const bool recheck_after_trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81195480)
Location: kernel/seccomp.c:796
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81195480-ffffffff81195b19: __seccomp_filter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
