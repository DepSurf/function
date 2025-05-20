# Function: <code>do_proc_douintvec</code>

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
In kernel/sysctl.c (ffffffff8108d8a3)
Location: kernel/sysctl.c:2435
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff81094223)
Location: kernel/sysctl.c:2425
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff81097b25)
Location: kernel/sysctl.c:2430
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff8109fe75)
Location: kernel/sysctl.c:2478
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff810a4555)
Location: kernel/sysctl.c:2564
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff810aab35)
Location: kernel/sysctl.c:2566
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff810b2bc5)
Location: kernel/sysctl.c:778
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff810ae3f5)
Location: kernel/sysctl.c:777
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff810b0835)
Location: kernel/sysctl.c:789
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_dou8vec_minmax
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff810c15f5)
Location: kernel/sysctl.c:813
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_dou8vec_minmax
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810d8ca5)
Location: kernel/sysctl.c:693
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dou8vec_minmax
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
Direct callers:
  - fs/pipe.c:proc_dopipe_max_size
```
**Symbols:**

```
ffffffff810d99e0-ffffffff810d9a1c: do_proc_douintvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810f8e95)
Location: kernel/sysctl.c:680
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dou8vec_minmax
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
Direct callers:
  - fs/pipe.c:proc_dopipe_max_size
```
**Symbols:**

```
ffffffff810f98c0-ffffffff810f98fc: do_proc_douintvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81105275)
Location: kernel/sysctl.c:679
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dou8vec_minmax
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
Direct callers:
  - fs/pipe.c:proc_dopipe_max_size
```
**Symbols:**

```
ffffffff81105bd0-ffffffff81105c0c: do_proc_douintvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8110ebc5)
Location: kernel/sysctl.c:679
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dou8vec_minmax
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
Direct callers:
  - fs/pipe.c:proc_dopipe_max_size
```
**Symbols:**

```
ffffffff8110f520-ffffffff8110f55c: do_proc_douintvec (STB_GLOBAL)
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
In kernel/sysctl.c (ffff8000101030b0)
Location: kernel/sysctl.c:2566
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (c035f128)
Location: kernel/sysctl.c:2566
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (c00000000014adf0)
Location: kernel/sysctl.c:2566
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffe0000caaf2)
Location: kernel/sysctl.c:2566
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff810a4455)
Location: kernel/sysctl.c:2566
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff81092e35)
Location: kernel/sysctl.c:2566
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff810a4405)
Location: kernel/sysctl.c:2566
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
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
In kernel/sysctl.c (ffffffff810ac4c5)
Location: kernel/sysctl.c:2566
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
