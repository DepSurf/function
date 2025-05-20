# Function: <code>guarantee_online_mems</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8111b730)
Location: kernel/cpuset.c:354
Inline: False
Direct callers:
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_mems_allowed
```
**Symbols:**

```
ffffffff8111b730-ffffffff8111b761: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff81123620)
Location: kernel/cpuset.c:365
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_mems_allowed
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81123620-ffffffff81123651: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112b710)
Location: kernel/cpuset.c:365
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_mems_allowed
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8112b710-ffffffff8112b76e: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8112cd50)
Location: kernel/cgroup/cpuset.c:368
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8112cd50-ffffffff8112cdb1: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81139c00)
Location: kernel/cgroup/cpuset.c:379
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81139c00-ffffffff81139c61: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811483e0)
Location: kernel/cgroup/cpuset.c:379
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff811483e0-ffffffff81148441: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811540b0)
Location: kernel/cgroup/cpuset.c:436
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff811540b0-ffffffff81154111: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81160600)
Location: kernel/cgroup/cpuset.c:398
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81160600-ffffffff8116065a: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116c2d0)
Location: kernel/cgroup/cpuset.c:410
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8116c2d0-ffffffff8116c32a: guarantee_online_mems (STB_LOCAL)
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
In kernel/cgroup/cpuset.c (ffffffff8117e230)
Location: kernel/cgroup/cpuset.c:414
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8117b0a0)
Location: kernel/cgroup/cpuset.c:414
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff81180697)
Location: kernel/cgroup/cpuset.c:414
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811a8487)
Location: kernel/cgroup/cpuset.c:442
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811d95ee)
Location: kernel/cgroup/cpuset.c:460
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8121e9ee)
Location: kernel/cgroup/cpuset.c:543
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff81234ade)
Location: kernel/cgroup/cpuset.c:543
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8124e6fe)
Location: kernel/cgroup/cpuset.c:573
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
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
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e0408)
Location: kernel/cgroup/cpuset.c:410
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffff8000101e0408-ffff8000101e0450: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0421e10)
Location: kernel/cgroup/cpuset.c:410
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
c0421e10-c0421e54: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c00000000024f230)
Location: kernel/cgroup/cpuset.c:410
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
c00000000024f230-c00000000024f2cc: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe000157314)
Location: kernel/cgroup/cpuset.c:410
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffe000157314-ffffffe000157356: guarantee_online_mems (STB_LOCAL)
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
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811648f0)
Location: kernel/cgroup/cpuset.c:410
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff811648f0-ffffffff8116494a: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81157b30)
Location: kernel/cgroup/cpuset.c:410
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81157b30-ffffffff81157b8a: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811626c0)
Location: kernel/cgroup/cpuset.c:410
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff811626c0-ffffffff8116271a: guarantee_online_mems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset *cs, nodemask_t *pmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116fc30)
Location: kernel/cgroup/cpuset.c:410
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8116fc30-ffffffff8116fc8a: guarantee_online_mems (STB_LOCAL)
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
