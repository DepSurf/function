# Function: <code>printk_safe_flush_buffer</code>

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
In kernel/printk/printk_safe.c (ffffffff810e4bbe)
Location: kernel/printk/printk_safe.c:134
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk_safe.c (ffffffff810ece5e)
Location: kernel/printk/printk_safe.c:131
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk_safe.c (ffffffff810f526d)
Location: kernel/printk/printk_safe.c:134
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk_safe.c (ffffffff81100a17)
Location: kernel/printk/printk_safe.c:134
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk_safe.c (ffffffff811091fe)
Location: kernel/printk/printk_safe.c:122
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk_safe.c (ffffffff811155de)
Location: kernel/printk/printk_safe.c:122
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int printk_safe_flush_buffer(const char *start, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:123
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
**Symbols:**

```
ffffffff81120e50-ffffffff81120ee5: printk_safe_flush_buffer (STB_LOCAL)
ffffffff811212e2-ffffffff81121350: printk_safe_flush_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int printk_safe_flush_buffer(const char *start, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:125
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
**Symbols:**

```
ffffffff8111bab0-ffffffff8111bb45: printk_safe_flush_buffer (STB_LOCAL)
ffffffff81be1470-ffffffff81be14de: printk_safe_flush_buffer.cold (STB_LOCAL)
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
In kernel/printk/printk_safe.c (ffffffff8111bf8e)
Location: kernel/printk/printk_safe.c:125
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffff8000101769d0)
Location: kernel/printk/printk_safe.c:122
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk_safe.c (c03c8958)
Location: kernel/printk/printk_safe.c:122
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk_safe.c (c0000000001d0384)
Location: kernel/printk/printk_safe.c:122
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk_safe.c (ffffffe000111c8c)
Location: kernel/printk/printk_safe.c:122
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk_safe.c (ffffffff8110dbbe)
Location: kernel/printk/printk_safe.c:122
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk_safe.c (ffffffff810fe91e)
Location: kernel/printk/printk_safe.c:122
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk_safe.c (ffffffff8110baae)
Location: kernel/printk/printk_safe.c:122
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk_safe.c (ffffffff81116fbe)
Location: kernel/printk/printk_safe.c:122
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
