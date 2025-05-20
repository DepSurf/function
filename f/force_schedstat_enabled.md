# Function: <code>force_schedstat_enabled</code>

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
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af300)
Location: kernel/sched/core.c:2294
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff810af300-ffffffff810af329: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5440)
Location: kernel/sched/core.c:2304
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff810b5440-ffffffff810b5469: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b1660)
Location: kernel/sched/core.c:2255
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff810b1660-ffffffff810b168a: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b8a90)
Location: kernel/sched/core.c:2274
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff810b8a90-ffffffff810b8ab8: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c05a0)
Location: kernel/sched/core.c:2250
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff810c05a0-ffffffff810c05c8: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c9910)
Location: kernel/sched/core.c:2244
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff810c9910-ffffffff810c9938: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2653
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff810d45a8-ffffffff810d45c2: force_schedstat_enabled.cold (STB_LOCAL)
ffffffff810d1540-ffffffff810d1554: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2773
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff810deb9d-ffffffff810debb7: force_schedstat_enabled.cold (STB_LOCAL)
ffffffff810db4f0-ffffffff810db504: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2932
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff810e6e1e-ffffffff810e6e38: force_schedstat_enabled.cold (STB_LOCAL)
ffffffff810e4370-ffffffff810e4384: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:3642
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff81bdc654-ffffffff81bdc66e: force_schedstat_enabled.cold (STB_LOCAL)
ffffffff810e1db0-ffffffff810e1dc4: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:3663
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff81bce7d7-ffffffff81bce7f1: force_schedstat_enabled.cold (STB_LOCAL)
ffffffff810e3bc0-ffffffff810e3bd4: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:4277
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff81ca5ed0-ffffffff81ca5eea: force_schedstat_enabled.cold (STB_LOCAL)
ffffffff810fa820-ffffffff810fa831: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:4409
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff81e55825-ffffffff81e55847: force_schedstat_enabled.cold (STB_LOCAL)
ffffffff81116d80-ffffffff81116d99: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113e200)
Location: kernel/sched/core.c:4537
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff8113e200-ffffffff8113e236: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114ad00)
Location: kernel/sched/core.c:4615
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff8114ad00-ffffffff8114ad36: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81156900)
Location: kernel/sched/core.c:4636
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
  - kernel/latencytop.c:sysctl_latencytop
```
**Symbols:**

```
ffffffff81156900-ffffffff81156936: force_schedstat_enabled (STB_GLOBAL)
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
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013b1e0)
Location: kernel/sched/core.c:2773
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffff80001013b1e0-ffff80001013b218: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038a9d8)
Location: kernel/sched/core.c:2773
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
c038a9d8-c038aa14: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000188ea0)
Location: kernel/sched/core.c:2773
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
c000000000188ea0-c000000000188ef4: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ea6d2)
Location: kernel/sched/core.c:2773
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffe0000ea6d2-ffffffe0000ea712: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2773
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff810d8d8d-ffffffff810d8da7: force_schedstat_enabled.cold (STB_LOCAL)
ffffffff810d59a0-ffffffff810d59b4: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2773
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff810c7798-ffffffff810c77b2: force_schedstat_enabled.cold (STB_LOCAL)
ffffffff810c3ff0-ffffffff810c4004: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2773
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
```
**Symbols:**

```
ffffffff810d50cd-ffffffff810d50e7: force_schedstat_enabled.cold (STB_LOCAL)
ffffffff810d27e0-ffffffff810d27f4: force_schedstat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void force_schedstat_enabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2773
Inline: False
Direct callers:
  - kernel/profile.c:profile_setup
  - kernel/latencytop.c:sysctl_latencytop
```
**Symbols:**

```
ffffffff810e097c-ffffffff810e0996: force_schedstat_enabled.cold (STB_LOCAL)
ffffffff810dd290-ffffffff810dd2a4: force_schedstat_enabled (STB_GLOBAL)
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
