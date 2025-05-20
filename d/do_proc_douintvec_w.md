# Function: <code>do_proc_douintvec_w</code>

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
In kernel/sysctl.c (ffffffff8108d708)
Location: kernel/sysctl.c:2306
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff8109401a)
Location: kernel/sysctl.c:2296
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff810979de)
Location: kernel/sysctl.c:2301
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff8109fd2e)
Location: kernel/sysctl.c:2349
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff810a4401)
Location: kernel/sysctl.c:2435
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff810aa9e1)
Location: kernel/sysctl.c:2437
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int do_proc_douintvec_w(unsigned int *tbl_data, struct ctl_table *table, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:654
Inline: False
Direct callers:
  - kernel/sysctl.c:__do_proc_douintvec
```
**Symbols:**

```
ffffffff810b28b0-ffffffff810b29e7: do_proc_douintvec_w (STB_LOCAL)
ffffffff810b3cba-ffffffff810b3cf0: do_proc_douintvec_w.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int do_proc_douintvec_w(unsigned int *tbl_data, struct ctl_table *table, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:653
Inline: False
Direct callers:
  - kernel/sysctl.c:__do_proc_douintvec
```
**Symbols:**

```
ffffffff810ae0e0-ffffffff810ae217: do_proc_douintvec_w (STB_LOCAL)
ffffffff81bdb8f6-ffffffff81bdb92c: do_proc_douintvec_w.cold (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff810b053c)
Location: kernel/sysctl.c:665
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff810c1301)
Location: kernel/sysctl.c:689
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff810d88fa)
Location: kernel/sysctl.c:569
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff810f8bb0)
Location: kernel/sysctl.c:556
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff81104f80)
Location: kernel/sysctl.c:555
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff8110e8d0)
Location: kernel/sysctl.c:555
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffff800010102f3c)
Location: kernel/sysctl.c:2437
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (c035efc0)
Location: kernel/sysctl.c:2437
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (c00000000014abe0)
Location: kernel/sysctl.c:2437
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffe0000ca9be)
Location: kernel/sysctl.c:2437
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff810a4301)
Location: kernel/sysctl.c:2437
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff81092ce1)
Location: kernel/sysctl.c:2437
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff810a42b1)
Location: kernel/sysctl.c:2437
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
In kernel/sysctl.c (ffffffff810ac371)
Location: kernel/sysctl.c:2437
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_douintvec
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
