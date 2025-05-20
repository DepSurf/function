# Function: <code>unix_open_file</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81880d9b)
Location: net/unix/af_unix.c:2599
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff81901f2b)
Location: net/unix/af_unix.c:2578
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff8195c598)
Location: net/unix/af_unix.c:2568
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff8198e178)
Location: net/unix/af_unix.c:2585
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff819f970e)
Location: net/unix/af_unix.c:2521
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff81a3036e)
Location: net/unix/af_unix.c:2533
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unix_open_file(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b23940)
Location: net/unix/af_unix.c:2584
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff81b23940-ffffffff81b23a4c: unix_open_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unix_open_file(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b32310)
Location: net/unix/af_unix.c:2575
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff81b32310-ffffffff81b3241c: unix_open_file (STB_LOCAL)
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
In net/unix/af_unix.c (ffffffff81b20841)
Location: net/unix/af_unix.c:2624
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff81be56b9)
Location: net/unix/af_unix.c:2948
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff81d7c65d)
Location: net/unix/af_unix.c:3032
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff81f496cd)
Location: net/unix/af_unix.c:3068
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff81fa933d)
Location: net/unix/af_unix.c:2983
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff820767cd)
Location: net/unix/af_unix.c:3000
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffff800010cf0158)
Location: net/unix/af_unix.c:2533
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (c0df7574)
Location: net/unix/af_unix.c:2533
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (c000000000e15d10)
Location: net/unix/af_unix.c:2533
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffe00083ca2c)
Location: net/unix/af_unix.c:2533
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff819cf9fe)
Location: net/unix/af_unix.c:2533
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff8198c7be)
Location: net/unix/af_unix.c:2533
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff81a3a47e)
Location: net/unix/af_unix.c:2533
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
In net/unix/af_unix.c (ffffffff81a45b5e)
Location: net/unix/af_unix.c:2533
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
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
