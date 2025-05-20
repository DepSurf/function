# Function: <code>root_cgroup_cputime</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void root_cgroup_cputime(struct task_cputime *cputime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81178a10)
Location: kernel/cgroup/rstat.c:398
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff81178a10-ffffffff81178aba: root_cgroup_cputime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void root_cgroup_cputime(struct task_cputime *cputime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81175660)
Location: kernel/cgroup/rstat.c:397
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff81175660-ffffffff8117570a: root_cgroup_cputime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void root_cgroup_cputime(struct task_cputime *cputime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81176110)
Location: kernel/cgroup/rstat.c:409
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff81176110-ffffffff811761b2: root_cgroup_cputime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void root_cgroup_cputime(struct task_cputime *cputime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8119d6d0)
Location: kernel/cgroup/rstat.c:409
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff8119d6d0-ffffffff8119d787: root_cgroup_cputime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void root_cgroup_cputime(struct task_cputime *cputime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811cd920)
Location: kernel/cgroup/rstat.c:414
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff811cd920-ffffffff811cd9f3: root_cgroup_cputime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void root_cgroup_cputime(struct cgroup_base_stat *bstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81210fe0)
Location: kernel/cgroup/rstat.c:455
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff81210fe0-ffffffff812110da: root_cgroup_cputime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void root_cgroup_cputime(struct cgroup_base_stat *bstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff812269d0)
Location: kernel/cgroup/rstat.c:439
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff812269d0-ffffffff81226ad2: root_cgroup_cputime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void root_cgroup_cputime(struct cgroup_base_stat *bstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8123e660)
Location: kernel/cgroup/rstat.c:486
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff8123e660-ffffffff8123e741: root_cgroup_cputime (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cgroup_base_stat *bstat</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_cputime *cputime</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
