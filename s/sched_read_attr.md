# Function: <code>sched_read_attr</code>

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
In kernel/sched/core.c (ffffffff810add47)
Location: kernel/sched/core.c:4313
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_getattr
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
In kernel/sched/core.c (ffffffff810b06fb)
Location: kernel/sched/core.c:4563
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_getattr
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
In kernel/sched/core.c (ffffffff810b688b)
Location: kernel/sched/core.c:4600
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_getattr
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
In kernel/sched/core.c (ffffffff810b2b13)
Location: kernel/sched/core.c:4497
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9f13)
Location: kernel/sched/core.c:4541
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sched_read_attr(struct sched_attr *uattr, struct sched_attr *attr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bc8c0)
Location: kernel/sched/core.c:4676
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810bc8c0-ffffffff810bc975: sched_read_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sched_read_attr(struct sched_attr *uattr, struct sched_attr *attr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c3e80)
Location: kernel/sched/core.c:4661
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810c3e80-ffffffff810c3f35: sched_read_attr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
