# Function: <code>find_io_range</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/logic_pio.c (ffffffff8149b6a0)
Location: lib/logic_pio.c:121
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff814d0940)
Location: lib/logic_pio.c:121
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff814e5270)
Location: lib/logic_pio.c:121
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff81511cc0)
Location: lib/logic_pio.c:140
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff81532700)
Location: lib/logic_pio.c:140
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff815ed230)
Location: lib/logic_pio.c:142
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff81611a19)
Location: lib/logic_pio.c:145
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff815f50f9)
Location: lib/logic_pio.c:145
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff81662519)
Location: lib/logic_pio.c:145
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff8177c289)
Location: lib/logic_pio.c:145
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff82025549)
Location: lib/logic_pio.c:145
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff820a5659)
Location: lib/logic_pio.c:145
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff8217d7b9)
Location: lib/logic_pio.c:142
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
struct logic_pio_hwaddr *find_io_range(long unsigned int pio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/logic_pio.c (ffff80001063e1b8)
Location: lib/logic_pio.c:140
Inline: False
Direct callers:
  - lib/logic_pio.c:logic_outsl
  - lib/logic_pio.c:logic_insl
  - lib/logic_pio.c:logic_outl
  - lib/logic_pio.c:logic_inl
  - lib/logic_pio.c:logic_outsw
  - lib/logic_pio.c:logic_insw
  - lib/logic_pio.c:logic_outw
  - lib/logic_pio.c:logic_inw
  - lib/logic_pio.c:logic_outsb
  - lib/logic_pio.c:logic_insb
  - lib/logic_pio.c:logic_outb
  - lib/logic_pio.c:logic_inb
  - lib/logic_pio.c:logic_pio_to_hwaddr
```
**Symbols:**

```
ffff80001063e1b8-ffff80001063e224: find_io_range (STB_LOCAL)
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
In lib/logic_pio.c (c07e441c)
Location: lib/logic_pio.c:140
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (c0000000007e8468)
Location: lib/logic_pio.c:140
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffe00046bbde)
Location: lib/logic_pio.c:140
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff8152ace0)
Location: lib/logic_pio.c:140
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff8151afc0)
Location: lib/logic_pio.c:140
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff81526d70)
Location: lib/logic_pio.c:140
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
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
In lib/logic_pio.c (ffffffff81540720)
Location: lib/logic_pio.c:140
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_to_hwaddr
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
