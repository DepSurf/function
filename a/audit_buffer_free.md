# Function: <code>audit_buffer_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_buffer_free(struct audit_buffer *ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811209c0)
Location: kernel/audit.c:1228
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_start
```
**Symbols:**

```
ffffffff811209c0-ffffffff81120a4d: audit_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_buffer_free(struct audit_buffer *ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81128910)
Location: kernel/audit.c:1242
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_start
```
**Symbols:**

```
ffffffff81128910-ffffffff81128998: audit_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_buffer_free(struct audit_buffer *ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811325c0)
Location: kernel/audit.c:1392
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
```
**Symbols:**

```
ffffffff811325c0-ffffffff81132648: audit_buffer_free (STB_LOCAL)
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
In kernel/audit.c (ffffffff81134460)
Location: kernel/audit.c:1603
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff81141220)
Location: kernel/audit.c:1611
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff8114fbb0)
Location: kernel/audit.c:1665
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff8115c88d)
Location: kernel/audit.c:1662
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff81168f70)
Location: kernel/audit.c:1662
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff81174e10)
Location: kernel/audit.c:1664
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff81187010)
Location: kernel/audit.c:1739
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_buffer_alloc
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
In kernel/audit.c (ffffffff81184380)
Location: kernel/audit.c:1750
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_buffer_alloc
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
In kernel/audit.c (ffffffff81185150)
Location: kernel/audit.c:1750
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff811ad540)
Location: kernel/audit.c:1787
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff811df2d2)
Location: kernel/audit.c:1767
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_log_start
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
In kernel/audit.c (ffffffff81224f77)
Location: kernel/audit.c:1765
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_log_start
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
In kernel/audit.c (ffffffff8123bf60)
Location: kernel/audit.c:1765
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_log_start
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
In kernel/audit.c (ffffffff81255e30)
Location: kernel/audit.c:1783
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_log_start
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
In kernel/audit.c (ffff8000101e9ae0)
Location: kernel/audit.c:1664
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (c0429980)
Location: kernel/audit.c:1664
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (c00000000025aa9c)
Location: kernel/audit.c:1664
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffe00015e7c2)
Location: kernel/audit.c:1664
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff8116d430)
Location: kernel/audit.c:1664
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff811605d0)
Location: kernel/audit.c:1664
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff8116b200)
Location: kernel/audit.c:1664
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff811789f0)
Location: kernel/audit.c:1664
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_end
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
