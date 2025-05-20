# Function: <code>exact_copy_from_user</code>

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
In fs/namespace.c (ffffffff8122ea47)
Location: fs/namespace.c:2587
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
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
In fs/namespace.c (ffffffff81257250)
Location: fs/namespace.c:2573
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
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
In fs/namespace.c (ffffffff8126a6ed)
Location: fs/namespace.c:2692
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
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
In fs/namespace.c (ffffffff81277e90)
Location: fs/namespace.c:2634
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
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
In fs/namespace.c (ffffffff8129a8d0)
Location: fs/namespace.c:2699
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c099f)
Location: fs/namespace.c:2730
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d5bef)
Location: fs/namespace.c:2700
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f43d0)
Location: fs/namespace.c:2966
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81305f80)
Location: fs/namespace.c:2997
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int exact_copy_from_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b4718)
Location: fs/namespace.c:2997
Inline: False
Direct callers:
  - fs/namespace.c:copy_mount_options
```
**Symbols:**

```
ffff8000103b4718-ffff8000103b4924: exact_copy_from_user (STB_LOCAL)
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
In fs/namespace.c (c0597104)
Location: fs/namespace.c:2997
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b69d0)
Location: fs/namespace.c:2997
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027b97a)
Location: fs/namespace.c:2997
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fe560)
Location: fs/namespace.c:2997
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ef180)
Location: fs/namespace.c:2997
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fc350)
Location: fs/namespace.c:2997
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130d6b0)
Location: fs/namespace.c:2997
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
