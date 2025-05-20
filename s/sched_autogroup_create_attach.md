# Function: <code>sched_autogroup_create_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/auto_group.c (ffffffff810c4ae0)
Location: kernel/sched/auto_group.c:153
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
```
**Symbols:**

```
ffffffff810c4ae0-ffffffff810c4c32: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/auto_group.c (ffffffff810c87a0)
Location: kernel/sched/auto_group.c:153
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
```
**Symbols:**

```
ffffffff810c87a0-ffffffff810c88eb: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/auto_group.c (ffffffff810ce790)
Location: kernel/sched/auto_group.c:173
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
```
**Symbols:**

```
ffffffff810ce790-ffffffff810ce8db: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/autogroup.c (ffffffff810cdb40)
Location: kernel/sched/autogroup.c:173
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
```
**Symbols:**

```
ffffffff810cdb40-ffffffff810cdc5b: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/autogroup.c (ffffffff810d53c0)
Location: kernel/sched/autogroup.c:173
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
```
**Symbols:**

```
ffffffff810d53c0-ffffffff810d54e7: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff810dd8f7-ffffffff810dd918: sched_autogroup_create_attach.cold.5 (STB_LOCAL)
ffffffff810dd3b0-ffffffff810dd4bf: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff810e8067-ffffffff810e8088: sched_autogroup_create_attach.cold.4 (STB_LOCAL)
ffffffff810e7b00-ffffffff810e7c0f: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff810eefe7-ffffffff810ef008: sched_autogroup_create_attach.cold (STB_LOCAL)
ffffffff810eea70-ffffffff810eeb8e: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff810fac97-ffffffff810facb8: sched_autogroup_create_attach.cold (STB_LOCAL)
ffffffff810fa670-ffffffff810fa7d4: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff811051e7-ffffffff81105208: sched_autogroup_create_attach.cold (STB_LOCAL)
ffffffff81104a50-ffffffff81104bd8: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff81bdcebf-ffffffff81bdcee0: sched_autogroup_create_attach.cold (STB_LOCAL)
ffffffff811030d0-ffffffff81103258: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff81bcf02b-ffffffff81bcf04c: sched_autogroup_create_attach.cold (STB_LOCAL)
ffffffff81105410-ffffffff8110558e: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff81ca77f7-ffffffff81ca7818: sched_autogroup_create_attach.cold (STB_LOCAL)
ffffffff81123080-ffffffff811231fe: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/autogroup.c:192
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff81e57f19-ffffffff81e57f3a: sched_autogroup_create_attach.cold (STB_LOCAL)
ffffffff81144d00-ffffffff81144e8d: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811710f0)
Location: kernel/sched/autogroup.c:193
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff811710f0-ffffffff81171291: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811818f0)
Location: kernel/sched/autogroup.c:193
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff811818f0-ffffffff81181a91: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811901a0)
Location: kernel/sched/autogroup.c:193
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff811901a0-ffffffff81190370: sched_autogroup_create_attach (STB_GLOBAL)
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
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/autogroup.c (ffff80001015f080)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffff80001015f080-ffff80001015f208: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/autogroup.c (c03ab92c)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
c03ab92c-c03abaa8: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/autogroup.c (c0000000001b4400)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
c0000000001b4400-c0000000001b4630: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/autogroup.c (ffffffe000103384)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffe000103384-ffffffe0001034fc: sched_autogroup_create_attach (STB_GLOBAL)
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
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff810f3fc7-ffffffff810f3fe8: sched_autogroup_create_attach.cold (STB_LOCAL)
ffffffff810f3a50-ffffffff810f3b6e: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff810e41a7-ffffffff810e41c8: sched_autogroup_create_attach.cold (STB_LOCAL)
ffffffff810e3b80-ffffffff810e3ce4: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff810f11c7-ffffffff810f11e8: sched_autogroup_create_attach.cold (STB_LOCAL)
ffffffff810f0ba0-ffffffff810f0d04: sched_autogroup_create_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void sched_autogroup_create_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/autogroup.c (0)
Location: kernel/sched/autogroup.c:170
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff810fc1a7-ffffffff810fc1c8: sched_autogroup_create_attach.cold (STB_LOCAL)
ffffffff810fbc30-ffffffff810fbd4e: sched_autogroup_create_attach (STB_GLOBAL)
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
