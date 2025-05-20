# Function: <code>cgroup_css_set_fork</code>

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
int cgroup_css_set_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81177da0)
Location: kernel/cgroup/cgroup.c:5931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff81177da0-ffffffff811781d2: cgroup_css_set_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_css_set_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174ac0)
Location: kernel/cgroup/cgroup.c:5923
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff81174ac0-ffffffff81174f09: cgroup_css_set_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_css_set_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175680)
Location: kernel/cgroup/cgroup.c:5898
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff81175680-ffffffff81175a57: cgroup_css_set_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_css_set_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119cc10)
Location: kernel/cgroup/cgroup.c:6113
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff8119cc10-ffffffff8119cffb: cgroup_css_set_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_css_set_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811ccf00)
Location: kernel/cgroup/cgroup.c:6127
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff811ccf00-ffffffff811cd324: cgroup_css_set_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_css_set_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812104c0)
Location: kernel/cgroup/cgroup.c:6373
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff812104c0-ffffffff812108e2: cgroup_css_set_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_css_set_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81225ed0)
Location: kernel/cgroup/cgroup.c:6354
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff81225ed0-ffffffff812262f5: cgroup_css_set_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_css_set_fork(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123db60)
Location: kernel/cgroup/cgroup.c:6389
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_can_fork
```
**Symbols:**

```
ffffffff8123db60-ffffffff8123df85: cgroup_css_set_fork (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
