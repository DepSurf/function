# Function: <code>snapshot_set_swap_area</code>

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
int snapshot_set_swap_area(struct snapshot_data *data, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff8111ba80)
Location: kernel/power/user.c:210
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff8111ba80-ffffffff8111bb66: snapshot_set_swap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int snapshot_set_swap_area(struct snapshot_data *data, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff81116400)
Location: kernel/power/user.c:203
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81116400-ffffffff811164c5: snapshot_set_swap_area (STB_LOCAL)
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
In kernel/power/user.c (ffffffff81116cba)
Location: kernel/power/user.c:203
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
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
In kernel/power/user.c (ffffffff8113707a)
Location: kernel/power/user.c:203
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
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
In kernel/power/user.c (ffffffff811594df)
Location: kernel/power/user.c:209
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
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
In kernel/power/user.c (ffffffff8118b70f)
Location: kernel/power/user.c:213
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
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
In kernel/power/user.c (ffffffff8119cfa2)
Location: kernel/power/user.c:213
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
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
In kernel/power/user.c (ffffffff811ac0f2)
Location: kernel/power/user.c:213
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
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
