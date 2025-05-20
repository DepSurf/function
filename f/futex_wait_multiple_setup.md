# Function: <code>futex_wait_multiple_setup</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int futex_wait_multiple_setup(struct futex_vector *vs, int count, int *woken);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811b6980)
Location: kernel/futex/waitwake.c:399
Inline: False
Direct callers:
  - kernel/futex/waitwake.c:futex_wait_multiple
```
**Symbols:**

```
ffffffff811b6980-ffffffff811b6c0f: futex_wait_multiple_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int futex_wait_multiple_setup(struct futex_vector *vs, int count, int *woken);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811f7ae0)
Location: kernel/futex/waitwake.c:399
Inline: False
Direct callers:
  - kernel/futex/waitwake.c:futex_wait_multiple
```
**Symbols:**

```
ffffffff811f7ae0-ffffffff811f7d6f: futex_wait_multiple_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int futex_wait_multiple_setup(struct futex_vector *vs, int count, int *woken);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff8120bff0)
Location: kernel/futex/waitwake.c:399
Inline: False
Direct callers:
  - kernel/futex/waitwake.c:futex_wait_multiple
```
**Symbols:**

```
ffffffff8120bff0-ffffffff8120c27f: futex_wait_multiple_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int futex_wait_multiple_setup(struct futex_vector *vs, int count, int *woken);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff81224020)
Location: kernel/futex/waitwake.c:414
Inline: False
Direct callers:
  - kernel/futex/waitwake.c:futex_wait_multiple
  - io_uring/futex.c:io_futexv_wait
  - io_uring/futex.c:io_futexv_wait
```
**Symbols:**

```
ffffffff81224020-ffffffff812242a4: futex_wait_multiple_setup (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
