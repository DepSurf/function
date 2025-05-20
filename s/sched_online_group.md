# Function: <code>sched_online_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0410)
Location: kernel/sched/core.c:7725
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810b0410-ffffffff810b04e2: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3010)
Location: kernel/sched/core.c:7754
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_alloc
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810b3010-ffffffff810b30ed: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9600)
Location: kernel/sched/core.c:7907
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_alloc
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810b9600-ffffffff810b96dd: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4220)
Location: kernel/sched/core.c:6120
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810b4220-ffffffff810b42db: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb4d0)
Location: kernel/sched/core.c:6188
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810bb4d0-ffffffff810bb58b: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c2980)
Location: kernel/sched/core.c:6308
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810c2980-ffffffff810c2a3b: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbc80)
Location: kernel/sched/core.c:6289
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810cbc80-ffffffff810cbd3b: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:6764
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810d46c5-ffffffff810d46e0: sched_online_group.cold (STB_LOCAL)
ffffffff810d3d10-ffffffff810d3dda: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de230)
Location: kernel/sched/core.c:6967
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810de230-ffffffff810de2f2: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e6800)
Location: kernel/sched/core.c:7201
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810e6800-ffffffff810e68c2: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e4700)
Location: kernel/sched/core.c:8166
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810e4700-ffffffff810e47c2: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e66a0)
Location: kernel/sched/core.c:8535
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810e66a0-ffffffff810e6762: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fdc00)
Location: kernel/sched/core.c:9763
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810fdc00-ffffffff810fdcc2: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8111a640)
Location: kernel/sched/core.c:10086
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff8111a640-ffffffff8111a709: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81141ef0)
Location: kernel/sched/core.c:10266
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff81141ef0-ffffffff81141fb9: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114dbc0)
Location: kernel/sched/core.c:10410
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff8114dbc0-ffffffff8114dc89: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811599d0)
Location: kernel/sched/core.c:10374
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff811599d0-ffffffff81159a99: sched_online_group (STB_GLOBAL)
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
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013dcd8)
Location: kernel/sched/core.c:6967
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffff80001013dcd8-ffff80001013dde4: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038dc84)
Location: kernel/sched/core.c:6967
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
c038dc84-c038dd44: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018cd00)
Location: kernel/sched/core.c:6967
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
c00000000018cd00-c00000000018cde0: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ecb0e)
Location: kernel/sched/core.c:6967
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffe0000ecb0e-ffffffe0000ecbbc: sched_online_group (STB_GLOBAL)
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
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8420)
Location: kernel/sched/core.c:6967
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810d8420-ffffffff810d84e2: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6e30)
Location: kernel/sched/core.c:6967
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810c6e30-ffffffff810c6ef2: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4bd0)
Location: kernel/sched/core.c:6967
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810d4bd0-ffffffff810d4c92: sched_online_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sched_online_group(struct task_group *tg, struct task_group *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0000)
Location: kernel/sched/core.c:6967
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
ffffffff810e0000-ffffffff810e00c2: sched_online_group (STB_GLOBAL)
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
