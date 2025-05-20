# Function: <code>update_tasks_flags</code>

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
In kernel/cpuset.c (ffffffff8111c11a)
Location: kernel/cpuset.c:1293
Inline: True
Inline callers:
  - kernel/cpuset.c:update_flag
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
In kernel/cpuset.c (ffffffff8112401e)
Location: kernel/cpuset.c:1295
Inline: True
Inline callers:
  - kernel/cpuset.c:update_flag
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
In kernel/cpuset.c (ffffffff8112cf45)
Location: kernel/cpuset.c:1295
Inline: True
Inline callers:
  - kernel/cpuset.c:update_flag
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8112e19f)
Location: kernel/cgroup/cpuset.c:1283
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_flag
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811397b0)
Location: kernel/cgroup/cpuset.c:1293
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff811397b0-ffffffff8113981a: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81147f90)
Location: kernel/cgroup/cpuset.c:1294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff81147f90-ffffffff81147ffa: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81153b70)
Location: kernel/cgroup/cpuset.c:1817
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff81153b70-ffffffff81153bda: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811600c0)
Location: kernel/cgroup/cpuset.c:1778
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff811600c0-ffffffff81160133: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116bd90)
Location: kernel/cgroup/cpuset.c:1852
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff8116bd90-ffffffff8116be09: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117dc30)
Location: kernel/cgroup/cpuset.c:1854
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff8117dc30-ffffffff8117dc99: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117aa80)
Location: kernel/cgroup/cpuset.c:1877
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff8117aa80-ffffffff8117aae9: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117b600)
Location: kernel/cgroup/cpuset.c:1877
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff8117b600-ffffffff8117b669: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a3150)
Location: kernel/cgroup/cpuset.c:1928
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff811a3150-ffffffff811a31b9: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d35b0)
Location: kernel/cgroup/cpuset.c:1968
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff811d35b0-ffffffff811d363b: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81218190)
Location: kernel/cgroup/cpuset.c:2157
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff81218190-ffffffff8121822a: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8122d8f0)
Location: kernel/cgroup/cpuset.c:2192
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff8122d8f0-ffffffff8122d98a: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81245c40)
Location: kernel/cgroup/cpuset.c:2973
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff81245c40-ffffffff81245cda: update_tasks_flags (STB_LOCAL)
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
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e0fc8)
Location: kernel/cgroup/cpuset.c:1852
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffff8000101e0fc8-ffff8000101e1048: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0422e34)
Location: kernel/cgroup/cpuset.c:1852
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_flag
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c00000000024edc0)
Location: kernel/cgroup/cpuset.c:1852
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
c00000000024edc0-c00000000024ee68: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe000156cf6)
Location: kernel/cgroup/cpuset.c:1852
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffe000156cf6-ffffffe000156d9a: update_tasks_flags (STB_LOCAL)
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
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811643b0)
Location: kernel/cgroup/cpuset.c:1852
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff811643b0-ffffffff81164429: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81157600)
Location: kernel/cgroup/cpuset.c:1852
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff81157600-ffffffff81157679: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81162180)
Location: kernel/cgroup/cpuset.c:1852
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff81162180-ffffffff811621f9: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116f700)
Location: kernel/cgroup/cpuset.c:1852
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_flag
```
**Symbols:**

```
ffffffff8116f700-ffffffff8116f779: update_tasks_flags (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
