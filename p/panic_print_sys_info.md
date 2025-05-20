# Function: <code>panic_print_sys_info</code>

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
In kernel/panic.c (ffffffff81096e72)
Location: kernel/panic.c:135
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (ffffffff8109b3f0)
Location: kernel/panic.c:137
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (ffffffff810a191c)
Location: kernel/panic.c:138
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (ffffffff810a8735)
Location: kernel/panic.c:148
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (ffffffff81bdb2ed)
Location: kernel/panic.c:148
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (ffffffff81bcd3df)
Location: kernel/panic.c:148
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (ffffffff81ca3ba6)
Location: kernel/panic.c:149
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff81e53347)
Location: kernel/panic.c:175
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff81e53131-ffffffff81e5319e: panic_print_sys_info.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff810ea493)
Location: kernel/panic.c:207
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff810ea0e0-ffffffff810ea15b: panic_print_sys_info.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void panic_print_sys_info(bool console_flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810f5ce0)
Location: kernel/panic.c:207
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff810f5ce0-ffffffff810f5d7c: panic_print_sys_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff810ff427)
Location: kernel/panic.c:208
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff810ff090-ffffffff810ff10b: panic_print_sys_info.part.0 (STB_LOCAL)
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
In kernel/panic.c (ffff8000100f6b14)
Location: kernel/panic.c:138
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (c0354b08)
Location: kernel/panic.c:138
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (c00000000013c9c8)
Location: kernel/panic.c:138
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (ffffffe0000c26d0)
Location: kernel/panic.c:138
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (ffffffff8109b23c)
Location: kernel/panic.c:138
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (ffffffff81089c76)
Location: kernel/panic.c:138
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (ffffffff8109b1ec)
Location: kernel/panic.c:138
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In kernel/panic.c (ffffffff810a2e63)
Location: kernel/panic.c:138
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
