# Function: <code>init_listener</code>

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
In kernel/seccomp.c (ffffffff81179562)
Location: kernel/seccomp.c:1198
Inline: True
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
In kernel/seccomp.c (ffffffff811863f3)
Location: kernel/seccomp.c:1203
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff8119213d)
Location: kernel/seccomp.c:1226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *init_listener(struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a6580)
Location: kernel/seccomp.c:1244
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff811a6580-ffffffff811a66c5: init_listener (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *init_listener(struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a3aa0)
Location: kernel/seccomp.c:1712
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff811a3aa0-ffffffff811a3baa: init_listener (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff811a54a4)
Location: kernel/seccomp.c:1760
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff811cebf4)
Location: kernel/seccomp.c:1742
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff81202d52)
Location: kernel/seccomp.c:1771
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff8124abb2)
Location: kernel/seccomp.c:1771
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff81261eb2)
Location: kernel/seccomp.c:1771
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff8127c0e1)
Location: kernel/seccomp.c:1836
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffff800010209a34)
Location: kernel/seccomp.c:1226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (c0448ae4)
Location: kernel/seccomp.c:1226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (c000000000286d08)
Location: kernel/seccomp.c:1226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffe00016bbf4)
Location: kernel/seccomp.c:1226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff8118a75d)
Location: kernel/seccomp.c:1226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff8117d887)
Location: kernel/seccomp.c:1226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff8118852d)
Location: kernel/seccomp.c:1226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff81195e82)
Location: kernel/seccomp.c:1226
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
