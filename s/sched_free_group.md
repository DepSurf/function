# Function: <code>sched_free_group</code>

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
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa3b0)
Location: kernel/sched/core.c:7724
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffff810aa3b0-ffffffff810aa3e4: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b03b0)
Location: kernel/sched/core.c:7877
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffff810b03b0-ffffffff810b03e4: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ac7c0)
Location: kernel/sched/core.c:6090
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffff810ac7c0-ffffffff810ac7f4: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b35b0)
Location: kernel/sched/core.c:6158
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffff810b35b0-ffffffff810b35e4: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba7a0)
Location: kernel/sched/core.c:6278
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffff810ba7a0-ffffffff810ba7d4: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c3960)
Location: kernel/sched/core.c:6259
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffff810c3960-ffffffff810c3994: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c9a50)
Location: kernel/sched/core.c:6734
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffff810c9a50-ffffffff810c9a86: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2b60)
Location: kernel/sched/core.c:6935
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffff810d2b60-ffffffff810d2b96: sched_free_group (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810dd3d5)
Location: kernel/sched/core.c:7169
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
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
In kernel/sched/core.c (ffffffff810d9cae)
Location: kernel/sched/core.c:8134
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
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
In kernel/sched/core.c (ffffffff810db89e)
Location: kernel/sched/core.c:8503
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
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
In kernel/sched/core.c (ffffffff810fdb2b)
Location: kernel/sched/core.c:9715
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_free_group_rcu
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
In kernel/sched/core.c (ffffffff8111a567)
Location: kernel/sched/core.c:10038
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_free_group_rcu
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
In kernel/sched/core.c (ffffffff81141df7)
Location: kernel/sched/core.c:10218
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_free_group_rcu
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
In kernel/sched/core.c (ffffffff8114dac7)
Location: kernel/sched/core.c:10362
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_free_group_rcu
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
In kernel/sched/core.c (ffffffff811598d7)
Location: kernel/sched/core.c:10326
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_free_group_rcu
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
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010132da0)
Location: kernel/sched/core.c:6935
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffff800010132da0-ffff800010132dec: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038261c)
Location: kernel/sched/core.c:6935
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
c038261c-c0382660: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017db30)
Location: kernel/sched/core.c:6935
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
c00000000017db30-c00000000017db9c: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e5946)
Location: kernel/sched/core.c:6935
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffe0000e5946-ffffffe0000e5996: sched_free_group (STB_LOCAL)
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
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ccee0)
Location: kernel/sched/core.c:6935
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffff810ccee0-ffffffff810ccf16: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb6e0)
Location: kernel/sched/core.c:6935
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffff810bb6e0-ffffffff810bb716: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc400)
Location: kernel/sched/core.c:6935
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffff810cc400-ffffffff810cc436: sched_free_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sched_free_group(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4ca0)
Location: kernel/sched/core.c:6935
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_free_group_rcu
  - kernel/sched/core.c:sched_create_group
```
**Symbols:**

```
ffffffff810d4ca0-ffffffff810d4cd6: sched_free_group (STB_LOCAL)
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
