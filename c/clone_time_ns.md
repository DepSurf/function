# Function: <code>clone_time_ns</code>

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
struct time_namespace *clone_time_ns(struct user_namespace *user_ns, struct time_namespace *old_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81159ba0)
Location: kernel/time/namespace.c:78
Inline: False
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
```
**Symbols:**

```
ffffffff81159ba0-ffffffff81159ce0: clone_time_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct time_namespace *clone_time_ns(struct user_namespace *user_ns, struct time_namespace *old_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81155bb0)
Location: kernel/time/namespace.c:78
Inline: False
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
```
**Symbols:**

```
ffffffff81155bb0-ffffffff81155d36: clone_time_ns (STB_LOCAL)
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
In kernel/time/namespace.c (ffffffff811571b4)
Location: kernel/time/namespace.c:78
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
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
In kernel/time/namespace.c (ffffffff8117c004)
Location: kernel/time/namespace.c:78
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
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
In kernel/time/namespace.c (ffffffff811b1754)
Location: kernel/time/namespace.c:78
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
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
In kernel/time/namespace.c (ffffffff811f24a4)
Location: kernel/time/namespace.c:78
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
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
In kernel/time/namespace.c (ffffffff81206c24)
Location: kernel/time/namespace.c:78
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
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
In kernel/time/namespace.c (ffffffff8121de34)
Location: kernel/time/namespace.c:78
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
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
</ul>
