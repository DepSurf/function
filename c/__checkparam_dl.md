# Function: <code>__checkparam_dl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a9a4f)
Location: kernel/sched/core.c:3724
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ac5ef)
Location: kernel/sched/core.c:3977
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b270d)
Location: kernel/sched/core.c:4014
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c9050)
Location: kernel/sched/deadline.c:2535
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810c9050-ffffffff810c9091: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d0740)
Location: kernel/sched/deadline.c:2522
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810d0740-ffffffff810d0781: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d8c70)
Location: kernel/sched/deadline.c:2607
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810d8c70-ffffffff810d8cbc: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e2770)
Location: kernel/sched/deadline.c:2610
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810e2770-ffffffff810e27bc: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e9280)
Location: kernel/sched/deadline.c:2601
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810e9280-ffffffff810e92cc: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f4d60)
Location: kernel/sched/deadline.c:2648
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810f4d60-ffffffff810f4dac: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fe470)
Location: kernel/sched/deadline.c:2647
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810fe470-ffffffff810fe4bc: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fcc70)
Location: kernel/sched/deadline.c:2782
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810fcc70-ffffffff810fccea: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810feff0)
Location: kernel/sched/deadline.c:2766
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810feff0-ffffffff810ff06a: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff8111aec0)
Location: kernel/sched/deadline.c:2780
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff8111aec0-ffffffff8111af3a: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8113ae50)
Location: kernel/sched/deadline.c:2922
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff8113ae50-ffffffff8113aee2: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81165750)
Location: kernel/sched/deadline.c:2922
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff81165750-ffffffff811657e2: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81175f10)
Location: kernel/sched/deadline.c:2948
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff81175f10-ffffffff81175fa2: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81184170)
Location: kernel/sched/deadline.c:3045
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff81184170-ffffffff81184202: __checkparam_dl (STB_GLOBAL)
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
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010157490)
Location: kernel/sched/deadline.c:2648
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffff800010157490-ffff800010157504: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a5224)
Location: kernel/sched/deadline.c:2648
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
c03a5224-c03a52d4: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001ac030)
Location: kernel/sched/deadline.c:2648
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
c0000000001ac030-c0000000001ac0a8: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fe2dc)
Location: kernel/sched/deadline.c:2648
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffe0000fe2dc-ffffffe0000fe334: __checkparam_dl (STB_GLOBAL)
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
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ee160)
Location: kernel/sched/deadline.c:2648
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810ee160-ffffffff810ee1ac: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810de1f0)
Location: kernel/sched/deadline.c:2648
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810de1f0-ffffffff810de23c: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eb290)
Location: kernel/sched/deadline.c:2648
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810eb290-ffffffff810eb2dc: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f6290)
Location: kernel/sched/deadline.c:2648
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810f6290-ffffffff810f62dc: __checkparam_dl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
