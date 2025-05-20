# Function: <code>compat_fetch_robust_entry</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113789b)
Location: kernel/futex.c:3677
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
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
In kernel/futex.c (ffffffff8114281e)
Location: kernel/futex.c:3715
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
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
In kernel/futex.c (ffffffff8114bf3a)
Location: kernel/futex.c:3967
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
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
In kernel/futex.c (ffffffff8115b95e)
Location: kernel/futex.c:3880
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
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
In kernel/futex.c (ffffffff8115842e)
Location: kernel/futex.c:3806
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
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
In kernel/futex.c (ffffffff811596ab)
Location: kernel/futex.c:3812
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
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
In kernel/futex.c (ffffffff8117e37b)
Location: kernel/futex.c:4049
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
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
In kernel/futex/core.c (ffffffff811b2fdd)
Location: kernel/futex/core.c:841
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
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
In kernel/futex/core.c (ffffffff811f3ecd)
Location: kernel/futex/core.c:849
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
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
In kernel/futex/core.c (ffffffff8120865d)
Location: kernel/futex/core.c:849
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
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
In kernel/futex/core.c (ffffffff8121f4ed)
Location: kernel/futex/core.c:874
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
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
int compat_fetch_robust_entry(compat_uptr_t *uentry, struct robust_list **entry, compat_uptr_t *head, unsigned int *pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b7690)
Location: kernel/futex.c:3967
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
**Symbols:**

```
ffff8000101b7690-ffff8000101b77fc: compat_fetch_robust_entry (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021f6f0)
Location: kernel/futex.c:3967
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/futex.c (ffffffff8114455a)
Location: kernel/futex.c:3967
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
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
In kernel/futex.c (ffffffff81136d8a)
Location: kernel/futex.c:3967
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
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
In kernel/futex.c (ffffffff8114240a)
Location: kernel/futex.c:3967
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
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
In kernel/futex.c (ffffffff8114e483)
Location: kernel/futex.c:3967
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
